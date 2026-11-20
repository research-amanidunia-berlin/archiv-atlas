[English](README.md) · [Deutsch](README.de.md)

# Common Elements of Frontier AI Safety Policies (December 2025 Update)

Report Q002093 · Source metr.org · Date 2025-12-09 · [Open original](https://metr.org/blog/2025-12-09-common-elements-of-frontier-ai-safety-policies/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Text ist ein Auszug aus METRs Bericht von Dezember 2025, keine vollständige Einzelanalyse der zwölf veröffentlichten Richtlinien. METR zufolge umfassen gemeinsame Ansätze Fähigkeitsschwellen und regelmäßige Modellprüfungen, Schutz der Modellgewichte, Einsatzsicherungen, mögliche Stopps bei unzureichenden Schutzmaßnahmen sowie Aufsicht und spätere Überarbeitungen; die Wirksamkeit wird im Auszug nicht belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 64 % | 87 / 97 % | 40 / 80 % | 91 / 97 % | 59 / 80 % | 60 / 81 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 32 / 62 % | 88 / 98 % | 77 / 91 % | 77 / 94 % | 78 / 88 % | 86 / 92 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 58 / 81 % | 81 / 93 % | 88 / 95 % | 85 / 96 % | 85 / 93 % | 87 / 93 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 51 % | 72 / 88 % | 13 / 49 % | 86 / 95 % | 36 / 61 % | 45 / 68 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 56 % | 82 / 97 % | 62 / 86 % | 80 / 96 % | 55 / 80 % | 70 / 86 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 21 / 52 % | 16 / 44 % | 14 / 54 % | 82 / 93 % | 34 / 61 % | 24 / 54 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 17 / 46 % | 81 / 93 % | 29 / 54 % | 41 / 61 % | 56 / 77 % | 51 / 67 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 55 % | 61 / 96 % | 15 / 48 % | 74 / 88 % | 33 / 60 % | 34 / 60 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 44 % | 74 / 94 % | 14 / 27 % | 60 / 77 % | 49 / 71 % | 59 / 69 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 23 / 49 % | 49 / 85 % | 28 / 54 % | 69 / 81 % | 49 / 70 % | 49 / 65 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 21 / 53 % | 46 / 84 % | 31 / 71 % | 48 / 83 % | 20 / 43 % | 54 / 78 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 49 / 79 % | 2 / 12 % | 35 / 72 % | 18 / 42 % | 11 / 27 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 47 / 78 % | 1 / 6 % | 20 / 53 % | 12 / 34 % | 6 / 20 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 9 / 31 % | 47 / 77 % | 4 / 21 % | 6 / 18 % | 13 / 34 % | 13 / 35 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 16 / 47 % | 44 / 87 % | 4 / 19 % | 38 / 56 % | 17 / 42 % | 10 / 30 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 20 / 46 % | 39 / 88 % | 10 / 35 % | 15 / 35 % | 27 / 56 % | 16 / 45 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 29 % | 36 / 66 % | 2 / 14 % | 38 / 67 % | 13 / 32 % | 8 / 31 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 36 / 77 % | 10 / 42 % | 12 / 58 % | 37 / 65 % | 10 / 36 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 34 / 78 % | 1 / 9 % | 5 / 34 % | 12 / 31 % | 5 / 18 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 33 / 81 % | 1 / 8 % | 1 / 21 % | 11 / 31 % | 6 / 17 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 17 / 50 % | 22 / 51 % | 11 / 39 % | 23 / 57 % | 31 / 58 % | 16 / 39 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 12 / 40 % | 23 / 50 % | 2 / 12 % | 0 / 0 % | 25 / 56 % | 27 / 58 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 16 / 43 % | 24 / 51 % | 3 / 18 % | 27 / 59 % | 19 / 43 % | 11 / 28 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 28 % | 27 / 81 % | 0 / 3 % | 0 / 0 % | 8 / 24 % | 5 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 51 % | 5 / 13 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 15 / 33 % | 21 / 56 % | 1 / 6 % | 21 / 49 % | 16 / 44 % | 10 / 31 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 19 / 81 % | 1 / 6 % | 5 / 18 % | 7 / 23 % | 5 / 17 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 17 / 52 % | 1 / 7 % | 16 / 42 % | 16 / 45 % | 6 / 26 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 39 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 16 / 44 % | 0 / 0 % | 1 / 17 % | 7 / 18 % | 5 / 17 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 11 / 40 % | 14 / 50 % | 1 / 5 % | 12 / 36 % | 13 / 35 % | 9 / 26 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 3 / 14 % | 0 / 0 % | 13 / 36 % | 8 / 25 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 27 % | 3 / 24 % | 1 / 8 % | 0 / 0 % | 10 / 34 % | 9 / 28 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 9 / 29 % | 8 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 8 / 19 % | 6 / 13 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 5 / 11 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 16 % | 5 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 1 / 12 % | 7 / 21 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 6 / 20 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 19 % | 5 / 13 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % |
