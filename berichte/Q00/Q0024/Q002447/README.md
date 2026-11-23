[English](README.md) · [Deutsch](README.de.md)

# Details about METR's preliminary evaluation of Claude 3.7

Report Q002447 · Source metr.org · Date 2025-04-04 · [Open original](https://metr.org/evaluations/claude-3-7-report/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR fand in seiner vorläufigen Evaluation gute Leistungen von Claude 3.7 Sonnet: etwa 55 Minuten geschätzter GAC-Zeithorizont und bei fünf RE-Bench-Aufgaben nach 32 Stunden ein Niveau ähnlich dem Median menschlicher Fachleute nach acht Stunden. Zugleich beobachtete METR Fälle von „Reward Hacking“ und betont, dass kurze Testdauer, einfacher Agentenaufbau, begrenzte Vergleichsdaten und künstliche Aufgaben keine belastbare Gesamteinschätzung der Fähigkeiten oder Risiken erlauben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 66 % | 82 / 96 % | 99 / 100 % | 51 / 76 % | 45 / 69 % | 68 / 82 % | 33 / 68 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 33 / 60 % | 73 / 96 % | 99 / 100 % | 70 / 85 % | 11 / 30 % | 54 / 70 % | 31 / 61 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 56 / 76 % | 97 / 99 % | 97 / 99 % | 80 / 89 % | 48 / 74 % | 70 / 83 % | 76 / 92 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 54 % | 39 / 84 % | 95 / 98 % | 38 / 66 % | 9 / 26 % | 32 / 58 % | 13 / 47 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 54 / 70 % | 80 / 95 % | 91 / 96 % | 82 / 91 % | 53 / 76 % | 71 / 82 % | 63 / 83 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 30 / 56 % | 47 / 86 % | 90 / 94 % | 64 / 82 % | 31 / 58 % | 62 / 77 % | 14 / 37 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 31 / 56 % | 44 / 75 % | 89 / 93 % | 35 / 60 % | 19 / 46 % | 21 / 39 % | 18 / 38 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 29 / 54 % | 26 / 94 % | 88 / 94 % | 57 / 80 % | 13 / 32 % | 10 / 23 % | 16 / 43 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 26 / 52 % | 69 / 95 % | 85 / 91 % | 39 / 64 % | 14 / 28 % | 43 / 61 % | 21 / 39 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 59 % | 48 / 96 % | 84 / 90 % | 58 / 78 % | 23 / 46 % | 31 / 49 % | 19 / 37 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 34 / 59 % | 61 / 97 % | 69 / 80 % | 26 / 55 % | 17 / 35 % | 31 / 51 % | 8 / 22 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 37 / 75 % | 65 / 79 % | 8 / 27 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 27 / 55 % | 59 / 98 % | 35 / 73 % | 42 / 72 % | 10 / 24 % | 31 / 55 % | 15 / 49 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 28 / 51 % | 55 / 83 % | 13 / 48 % | 37 / 64 % | 6 / 17 % | 29 / 50 % | 5 / 24 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 43 / 74 % | 31 / 49 % | 15 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 39 / 83 % | 0 / 0 % | 6 / 15 % | 2 / 7 % | 7 / 15 % | 0 / 4 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 35 / 58 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 33 / 43 % | 6 / 16 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 30 / 59 % | 5 / 17 % | 2 / 7 % | 5 / 11 % | 1 / 6 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 20 / 77 % | 27 / 61 % | 6 / 17 % | 1 / 3 % | 11 / 21 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 26 / 72 % | 23 / 52 % | 6 / 14 % | 1 / 4 % | 7 / 17 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 4 / 62 % | 24 / 47 % | 8 / 24 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 39 % | 2 / 9 % | 22 / 41 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 21 / 71 % | 2 / 23 % | 6 / 19 % | 0 / 3 % | 5 / 12 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 17 / 43 % | 14 / 56 % | 0 / 0 % | 19 / 44 % | 4 / 14 % | 18 / 33 % | 1 / 7 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 12 / 73 % | 1 / 13 % | 7 / 18 % | 2 / 6 % | 0 / 0 % | 0 / 3 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 34 % | 3 / 8 % | 11 / 22 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 1 / 3 % | 8 / 17 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 5 / 64 % | 1 / 11 % | 7 / 21 % | 2 / 8 % | 5 / 12 % | 0 / 3 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 7 / 12 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 2 % | 6 / 11 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 3 % | 6 / 16 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 4 / 8 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
