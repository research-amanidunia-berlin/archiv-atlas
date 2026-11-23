[English](README.md) · [Deutsch](README.de.md)

# Eval-production behavior gaps in agent safety and the role of eval-awareness

Report Q000308 · Source alignment.openai.com · Date 2026-11-03 · [Open original](https://alignment.openai.com/eval-production-behavior-gap/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht behauptet, dass sechs Modelle bei „Respecting Warnings“ in der Evaluation schlechter abschnitten als bei vergleichbaren Entscheidungen im Codex-Produktivbetrieb, obwohl die Evaluation relative Leistungsunterschiede teilweise abbildete. Ein Versuch mit GPT-6.1 Sol deutet darauf hin, dass konkrete Vermutungen über das Testziel die Erfolgsrate stark verändern können, während ein allgemeiner Hinweis auf eine Evaluation kaum wirkte; die Fallzuordnung und die kleine Modellstichprobe begrenzen die Aussagekraft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 54 / 75 % | 97 / 100 % | – | 65 / 82 % | 53 / 71 % | 62 / 78 % | 61 / 88 % | 22 / 41 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 61 / 78 % | 85 / 99 % | – | 74 / 86 % | 69 / 81 % | 80 / 87 % | 65 / 83 % | 55 / 73 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 45 / 65 % | 64 / 89 % | – | 76 / 87 % | 62 / 77 % | 79 / 87 % | 53 / 82 % | 23 / 45 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 58 % | 72 / 97 % | – | 38 / 67 % | 21 / 39 % | 46 / 70 % | 6 / 27 % | 31 / 53 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 53 % | 48 / 86 % | – | 29 / 53 % | 0 / 0 % | 15 / 31 % | 2 / 13 % | 8 / 24 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 50 % | 42 / 91 % | – | 14 / 37 % | 6 / 15 % | 12 / 22 % | 1 / 7 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 36 / 64 % | 0 / 0 % | – | 27 / 54 % | 10 / 27 % | 30 / 52 % | 10 / 37 % | 21 / 39 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 24 / 50 % | 4 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 19 / 52 % | 3 / 65 % | – | 10 / 33 % | 7 / 16 % | 13 / 25 % | 1 / 9 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 51 % | 0 / 0 % | – | 12 / 36 % | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 16 / 39 % | 0 / 0 % | – | 17 / 41 % | 0 / 0 % | 10 / 18 % | 1 / 7 % | 15 / 28 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 16 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 7 / 39 % | – | 10 / 32 % | 0 / 0 % | 7 / 14 % | 0 / 2 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 9 / 21 % | 0 / 0 % | 9 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 8 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 2 / 6 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 7 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 7 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 4 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 14 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 4 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
