[English](README.md) · [Deutsch](README.de.md)

# A postmortem of three recent issues

Report Q002279 · Source anthropic.com · Date 2025-09-17 · [Open original](https://www.anthropic.com/research/a-postmortem-of-three-recent-issues)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic führt zeitweise Qualitätsprobleme bei Claude im August und September auf drei Infrastrukturfehler zurück: Fehlleitung von Sonnet-4-Anfragen, fehlerhafte Token-Erzeugung auf TPUs und einen Compilerfehler bei der Token-Auswahl. Das Unternehmen berichtet, die Probleme behoben oder zurückgerollt zu haben, und kündigt bessere Tests und Überwachung an; die Ursachenanalyse und Folgen stammen aus Anthropics eigener Darstellung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 61 % | 99 / 100 % | 100 / 100 % | 53 / 76 % | 39 / 61 % | 52 / 70 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 51 % | 92 / 98 % | 99 / 100 % | 42 / 67 % | 12 / 28 % | 29 / 47 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 29 / 51 % | 62 / 83 % | 96 / 98 % | 37 / 61 % | 15 / 29 % | 17 / 29 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 92 / 94 % | 40 / 64 % | 0 / 0 % | 22 / 40 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 38 / 65 % | 87 / 97 % | 21 / 46 % | 0 / 0 % | 12 / 23 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 52 / 79 % | 85 / 92 % | 52 / 70 % | 16 / 29 % | 30 / 42 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 39 / 61 % | 41 / 56 % | 85 / 93 % | 58 / 79 % | 35 / 53 % | 34 / 55 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 83 / 89 % | 27 / 50 % | 11 / 22 % | 21 / 40 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 37 / 63 % | 79 / 85 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 77 / 83 % | 11 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 31 / 56 % | 69 / 96 % | 68 / 80 % | 40 / 61 % | 0 / 0 % | 18 / 33 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 51 / 97 % | 60 / 90 % | 24 / 50 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 39 / 55 % | 14 / 34 % | 5 / 10 % | 6 / 13 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 26 / 47 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 24 / 55 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 16 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 13 / 55 % | 0 / 0 % | 8 / 20 % | 3 / 8 % | 7 / 15 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 32 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 11 / 22 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 10 / 35 % | 8 / 21 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | – | – |
