[English](README.md) · [Deutsch](README.de.md)

# Understanding the source of what we see and hear online

Report Q007641 · Source openai.com · Date 2024-05-07 · [Open original](https://openai.com/index/understanding-the-source-of-what-we-see-and-hear-online/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt C2PA-Metadaten, Wasserzeichen und Klassifikatoren als Wege, die Herkunft digitaler Inhalte nachvollziehbarer zu machen, und berichtet über interne Tests eines DALL·E-3-Bildklassifikators. Der Bericht betont zugleich Grenzen: Metadaten können entfernt werden, Erkennung lässt sich durch Bearbeitungen beeinträchtigen, und Textwasserzeichen könnten leicht umgangen werden oder bestimmte Gruppen benachteiligen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 73 / 83 % | 99 / 100 % | – | 100 / 100 % | 90 / 93 % | 88 / 90 % | 91 / 94 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 31 / 49 % | 39 / 95 % | – | 99 / 100 % | 24 / 46 % | 6 / 13 % | 7 / 16 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 46 % | 78 / 93 % | – | 97 / 99 % | 28 / 56 % | 24 / 42 % | 16 / 34 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 50 / 90 % | – | 96 / 98 % | 16 / 34 % | 13 / 28 % | 10 / 22 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 94 / 96 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 57 / 79 % | – | 87 / 94 % | 28 / 50 % | 0 / 0 % | 55 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 24 / 63 % | – | 84 / 91 % | 13 / 33 % | 11 / 24 % | 5 / 16 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 37 / 54 % | 83 / 95 % | – | 73 / 93 % | 24 / 50 % | 0 / 0 % | 15 / 28 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 71 / 85 % | 9 / 20 % | 7 / 14 % | 2 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 39 / 76 % | – | 69 / 83 % | 19 / 41 % | 6 / 13 % | 8 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 23 / 85 % | – | 63 / 82 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | – | 56 / 70 % | 0 / 0 % | 3 / 6 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 22 / 89 % | – | 52 / 70 % | 8 / 21 % | 6 / 12 % | 2 / 11 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 39 / 86 % | – | 48 / 69 % | 29 / 51 % | 7 / 15 % | 4 / 12 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 43 / 70 % | 9 / 26 % | 0 / 0 % | 2 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 21 / 45 % | – | 33 / 56 % | 21 / 42 % | 15 / 26 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 33 / 59 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 31 / 68 % | – | 25 / 53 % | 10 / 28 % | 7 / 20 % | 4 / 16 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 25 / 92 % | – | 27 / 55 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 23 / 44 % | 12 / 31 % | 8 / 16 % | 3 / 8 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 18 / 52 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 8 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 5 / 40 % | – | 10 / 25 % | 7 / 16 % | 7 / 13 % | 4 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 25 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 0 / 0 % | 2 / 7 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 3 / 33 % | – | 0 / 0 % | 8 / 16 % | 0 / 0 % | 2 / 7 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
