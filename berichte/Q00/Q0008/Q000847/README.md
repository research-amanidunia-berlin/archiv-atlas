[English](README.md) · [Deutsch](README.de.md)

# Architectural Backdoors for Within-Batch Data Stealing and Model Inference Manipulation

Report Q000847 · Source deepmind.google · Date 2026-09-22 · [Open original](https://deepmind.google/research/publications/149959/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Bericht enthält nur das Abstract und bibliografische Angaben. Darin behaupten die Autoren, architektonische Hintertüren könnten gebündelte Inferenz nutzen, um Daten zwischen Nutzeranfragen abzugreifen und Antworten zu manipulieren; eine formale Informationsflusskontrolle soll dies verhindern. Bei einer Untersuchung hätten sie über 200 Hugging-Face-Modelle mit unbeabsichtigten Lecks durch dynamische Quantisierung gefunden, doch der Auszug liefert keine näheren Angaben zur Methodik oder zum Umfang der Prüfung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 56 / 72 % | 98 / 100 % | 100 / 100 % | 84 / 91 % | 41 / 58 % | 53 / 68 % | 68 / 79 % | 76 / 85 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 49 % | 72 / 92 % | 99 / 100 % | 30 / 53 % | 9 / 22 % | 16 / 33 % | 9 / 39 % | 29 / 48 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 19 / 45 % | 0 / 0 % | 65 / 82 % | 0 / 0 % | 6 / 15 % | 10 / 21 % | 3 / 16 % | 10 / 24 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 53 / 72 % | 22 / 57 % | 19 / 42 % | 0 / 0 % | 12 / 25 % | 2 / 9 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 38 / 57 % | 27 / 36 % | 28 / 52 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 38 / 68 % | 21 / 40 % | 0 / 0 % | 7 / 13 % | 3 / 12 % | 10 / 24 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 47 % | 0 / 0 % | 0 / 0 % | 11 / 31 % | 3 / 11 % | 10 / 21 % | 2 / 12 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 22 / 36 % | 10 / 27 % | 4 / 11 % | 0 / 0 % | 1 / 4 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 19 / 65 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 8 / 27 % | 16 / 37 % | 3 / 10 % | 7 / 15 % | 1 / 10 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 15 / 41 % | 0 / 0 % | 1 / 14 % | 9 / 21 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 6 / 20 % | 10 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 10 / 34 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 4 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
