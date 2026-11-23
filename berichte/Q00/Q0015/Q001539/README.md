[English](README.md) · [Deutsch](README.de.md)

# Advancing Gemini's security safeguards

Report Q001539 · Source deepmind.google · Date 2025-05-20 · [Open original](https://deepmind.google/blog/advancing-geminis-security-safeguards/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind berichtet, dass automatisierte, auch adaptive Angriffstests und ein gezieltes Training von Gemini 2.5 die Abwehr indirekter Prompt-Injections verbessert hätten. Das Unternehmen betont, dass kein Modell vollständig geschützt sei und empfiehlt mehrere Schutzschichten sowie fortlaufende Tests; konkrete Messwerte fehlen im Beitrag.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 48 % | 45 / 91 % | 99 / 100 % | 48 / 71 % | 13 / 33 % | 33 / 60 % | 18 / 45 % | 26 / 46 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 51 % | 80 / 98 % | 96 / 99 % | 49 / 73 % | 42 / 63 % | 56 / 72 % | 49 / 76 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 35 / 57 % | 38 / 80 % | 92 / 98 % | 22 / 40 % | 16 / 36 % | 34 / 58 % | 30 / 58 % | 32 / 57 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 48 % | 82 / 99 % | 83 / 91 % | 40 / 67 % | 19 / 40 % | 29 / 54 % | 8 / 23 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 50 / 90 % | 68 / 89 % | 34 / 60 % | 7 / 19 % | 13 / 25 % | 7 / 22 % | 11 / 28 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 48 / 91 % | 68 / 84 % | 19 / 37 % | 6 / 13 % | 13 / 23 % | 1 / 5 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 16 / 41 % | 58 / 93 % | 56 / 85 % | 41 / 65 % | 7 / 22 % | 22 / 45 % | 13 / 46 % | 13 / 39 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 57 / 77 % | 17 / 38 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 23 / 76 % | 45 / 62 % | 36 / 64 % | 15 / 34 % | 30 / 52 % | 3 / 11 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 34 / 82 % | 0 / 0 % | 6 / 12 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 13 / 33 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 33 / 46 % | 7 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 8 / 23 % | 14 / 36 % | 2 / 13 % | 6 / 17 % | 1 / 6 % | 31 / 52 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 28 / 51 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 3 / 27 % | 27 / 52 % | 6 / 13 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 23 / 50 % | 8 / 35 % | 11 / 29 % | 1 / 5 % | 6 / 13 % | 0 / 0 % | 19 / 40 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 40 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 19 / 46 % | 4 / 24 % | 6 / 14 % | 1 / 4 % | 4 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 18 / 56 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 30 % | 17 / 51 % | 1 / 14 % | 10 / 25 % | 2 / 8 % | 0 / 0 % | 1 / 6 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 26 % | 17 / 71 % | 0 / 0 % | 8 / 23 % | 4 / 13 % | 9 / 22 % | 1 / 5 % | 5 / 18 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 16 / 71 % | 8 / 18 % | 10 / 32 % | 3 / 8 % | 11 / 22 % | 2 / 8 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 16 / 49 % | 9 / 26 % | 8 / 19 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 11 / 89 % | 3 / 31 % | 12 / 31 % | 2 / 9 % | 8 / 16 % | 0 / 3 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 33 % | 1 / 6 % | 4 / 8 % | 1 / 4 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 33 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 3 / 19 % | 5 / 10 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | 10 / 27 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 7 / 67 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 6 / 24 % | 6 / 15 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 31 % | 0 / 0 % | 5 / 10 % | 0 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
