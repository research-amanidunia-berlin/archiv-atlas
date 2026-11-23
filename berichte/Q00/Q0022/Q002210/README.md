[English](README.md) · [Deutsch](README.de.md)

# Testing and mitigating elections-related risks

Report Q002210 · Source anthropic.com · Date 2024-06-06 · [Open original](https://www.anthropic.com/news/testing-and-mitigating-elections-related-risks)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic schildert, wie es Wahlrisiken durch Fachtests und automatisierte Prüfungen untersucht und daraus Änderungen an Modellen, Richtlinien und Durchsetzung ableitet. Laut den berichteten Vergleichen verbesserten bestimmte Maßnahmen den Hinweis auf den Wissensstand um 47,2 Prozent und passende Verweise auf zuverlässige Quellen um 10,4 Prozent; der Bericht betont zugleich, dass einzelne Schutzmaßnahmen nicht vollständig wirken und die Tests Ungenauigkeiten enthalten können.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 42 / 64 % | 100 / 100 % | 100 / 100 % | 70 / 84 % | 67 / 80 % | 78 / 87 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 40 / 60 % | 98 / 100 % | 100 / 100 % | 72 / 85 % | 30 / 53 % | 65 / 81 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 27 / 49 % | 92 / 99 % | 99 / 100 % | 46 / 68 % | 12 / 29 % | 31 / 49 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 45 % | 83 / 96 % | 94 / 98 % | 55 / 75 % | 14 / 32 % | 40 / 56 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 86 / 100 % | 94 / 97 % | 68 / 84 % | 30 / 54 % | 64 / 79 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 27 / 48 % | 79 / 99 % | 87 / 94 % | 48 / 73 % | 19 / 45 % | 37 / 62 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 23 / 46 % | 35 / 83 % | 78 / 88 % | 25 / 50 % | 10 / 26 % | 27 / 49 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 6 / 43 % | 72 / 86 % | 30 / 48 % | 5 / 13 % | 18 / 28 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 72 / 96 % | 11 / 24 % | 8 / 21 % | 2 / 11 % | 7 / 15 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 62 / 99 % | 27 / 69 % | 16 / 42 % | 5 / 16 % | 13 / 29 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 23 / 44 % | 61 / 98 % | 20 / 45 % | 19 / 41 % | 6 / 19 % | 24 / 44 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 4 / 60 % | 60 / 80 % | 22 / 46 % | 4 / 13 % | 9 / 19 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 29 / 51 % | 47 / 94 % | 52 / 71 % | 29 / 57 % | 16 / 33 % | 29 / 51 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 3 / 34 % | 50 / 64 % | 9 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 21 / 68 % | 47 / 61 % | 21 / 45 % | 4 / 17 % | 7 / 14 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 1 / 24 % | 42 / 72 % | 8 / 26 % | 2 / 13 % | 6 / 13 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 38 / 58 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 23 / 60 % | 36 / 61 % | 12 / 33 % | 8 / 23 % | 13 / 28 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 35 / 84 % | 34 / 58 % | 8 / 25 % | 0 / 0 % | 8 / 16 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 27 / 71 % | 0 / 0 % | 28 / 54 % | 8 / 24 % | 12 / 25 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 24 / 44 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 17 / 48 % | 22 / 47 % | 10 / 24 % | 2 / 7 % | 5 / 12 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 21 / 43 % | 10 / 31 % | 1 / 6 % | 9 / 20 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 4 / 14 % | 16 / 32 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 9 / 49 % | 3 / 14 % | 10 / 28 % | 4 / 12 % | 15 / 29 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 13 / 43 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 9 / 19 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 3 / 8 % | 9 / 19 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 2 / 10 % | 6 / 14 % | 2 / 9 % | 7 / 14 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 5 / 59 % | 4 / 18 % | 7 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 7 / 31 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 64 % | 0 / 0 % | 7 / 19 % | 2 / 11 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 7 % | 6 / 15 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 2 / 6 % | 4 / 7 % | – | – |
