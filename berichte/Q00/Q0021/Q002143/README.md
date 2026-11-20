[English](README.md) · [Deutsch](README.de.md)

# Summary of our gpt-oss methodology review

Report Q002143 · Source metr.org · Date 2025-10-23 · [Open original](https://metr.org/blog/2025-10-23-gpt-oss-methodology-review/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR prüfte OpenAIs Methodik für adversariales Fine-Tuning von gpt-oss-120b in Biologie und Chemie sowie Cybersicherheit und gab 17 Empfehlungen ab. METR zufolge wurden fünf von sechs dringlichen Empfehlungen umgesetzt, eine nur teilweise; konkrete Kriterien für die Einstufung als hohe Fähigkeit bleiben unveröffentlicht. Die Prüfung war eng begrenzt und schloss sowohl eine Gesamtbewertung des Modells als auch Bedrohungsszenarien mit besser ausgestatteten Akteuren aus.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 49 / 67 % | 100 / 100 % | 83 / 94 % | 100 / 100 % | 69 / 84 % | 83 / 89 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 43 / 63 % | 99 / 100 % | 39 / 66 % | 99 / 100 % | 68 / 82 % | 62 / 74 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 31 / 56 % | 97 / 99 % | 33 / 58 % | 93 / 98 % | 64 / 82 % | 57 / 71 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 40 / 59 % | 82 / 99 % | 55 / 79 % | 97 / 99 % | 81 / 90 % | 56 / 71 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 58 / 73 % | 94 / 99 % | 64 / 78 % | 90 / 95 % | 69 / 83 % | 55 / 68 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 32 / 52 % | 91 / 98 % | 33 / 60 % | 76 / 92 % | 71 / 86 % | 53 / 68 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 44 / 64 % | 87 / 99 % | 73 / 91 % | 90 / 97 % | 60 / 75 % | 75 / 84 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 38 / 59 % | 0 / 0 % | 36 / 64 % | 89 / 93 % | 34 / 55 % | 31 / 50 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 50 / 82 % | 1 / 5 % | 88 / 92 % | 17 / 40 % | 10 / 19 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 62 / 97 % | 6 / 21 % | 82 / 94 % | 24 / 52 % | 31 / 52 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 40 / 60 % | 42 / 75 % | 12 / 42 % | 80 / 91 % | 60 / 81 % | 57 / 71 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 6 / 38 % | 0 / 0 % | 72 / 82 % | 9 / 21 % | 9 / 17 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 28 / 53 % | 53 / 97 % | 6 / 26 % | 66 / 86 % | 27 / 52 % | 26 / 43 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 41 / 86 % | 0 / 3 % | 58 / 76 % | 10 / 25 % | 7 / 17 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 10 / 47 % | 1 / 4 % | 55 / 72 % | 25 / 49 % | 18 / 34 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 44 / 61 % | 23 / 47 % | 27 / 42 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 40 / 59 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 36 / 56 % | 14 / 38 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 29 / 43 % | 12 / 34 % | 14 / 29 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 29 / 81 % | 0 / 2 % | 0 / 0 % | 7 / 20 % | 10 / 18 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 47 % | 10 / 23 % | 8 / 15 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 23 / 49 % | 12 / 35 % | 7 / 17 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 15 / 42 % | 1 / 7 % | 0 / 0 % | 9 / 20 % | 8 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 9 / 21 % | 12 / 21 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 10 / 20 % | 9 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 5 / 50 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 8 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 7 / 15 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % |
