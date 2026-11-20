[English](README.md) · [Deutsch](README.de.md)

# Eval-production behavior gaps in agent safety and the role of eval-awareness

Report Q000308 · Source alignment.openai.com · Date 2026-11-03 · [Open original](https://alignment.openai.com/eval-production-behavior-gap/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht behauptet, dass sechs Modelle bei „Respecting Warnings“ in der Evaluation schlechter abschnitten als bei vergleichbaren Entscheidungen im Codex-Produktivbetrieb, obwohl die Evaluation relative Leistungsunterschiede teilweise abbildete. Ein Versuch mit GPT-6.1 Sol deutet darauf hin, dass konkrete Vermutungen über das Testziel die Erfolgsrate stark verändern können, während ein allgemeiner Hinweis auf eine Evaluation kaum wirkte; die Fallzuordnung und die kleine Modellstichprobe begrenzen die Aussagekraft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 54 / 75 % | 97 / 100 % | 61 / 88 % | – | 65 / 82 % | – | 53 / 71 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 61 / 78 % | 85 / 99 % | 65 / 83 % | – | 74 / 86 % | – | 69 / 81 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 45 / 65 % | 64 / 89 % | 53 / 82 % | – | 76 / 87 % | – | 62 / 77 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 58 % | 72 / 97 % | 6 / 27 % | – | 38 / 67 % | – | 21 / 39 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 53 % | 48 / 86 % | 2 / 13 % | – | 29 / 53 % | – | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 50 % | 42 / 91 % | 1 / 7 % | – | 14 / 37 % | – | 6 / 15 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 36 / 64 % | 0 / 0 % | 10 / 37 % | – | 27 / 54 % | – | 10 / 27 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 24 / 50 % | – | 4 / 10 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 19 / 52 % | 3 / 65 % | 1 / 9 % | – | 10 / 33 % | – | 7 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 51 % | 0 / 0 % | 0 / 4 % | – | 12 / 36 % | – | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 16 / 39 % | 0 / 0 % | 1 / 7 % | – | 17 / 41 % | – | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 16 / 39 % | – | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 7 / 39 % | 0 / 2 % | – | 10 / 32 % | – | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 21 % | – | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 14 % | – | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 19 % | – | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 15 % | – | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | – | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | – | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | – | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | – | 1 / 3 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 4 / 10 % | – | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 4 / 10 % | – | 0 / 0 % |
