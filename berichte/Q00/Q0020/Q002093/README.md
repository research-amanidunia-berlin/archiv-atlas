[English](README.md) · [Deutsch](README.de.md)

# Common Elements of Frontier AI Safety Policies (December 2025 Update)

Report Q002093 · Source metr.org · Date 2025-12-09 · [Open original](https://metr.org/blog/2025-12-09-common-elements-of-frontier-ai-safety-policies/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Text ist ein Auszug aus METRs Bericht von Dezember 2025, keine vollständige Einzelanalyse der zwölf veröffentlichten Richtlinien. METR zufolge umfassen gemeinsame Ansätze Fähigkeitsschwellen und regelmäßige Modellprüfungen, Schutz der Modellgewichte, Einsatzsicherungen, mögliche Stopps bei unzureichenden Schutzmaßnahmen sowie Aufsicht und spätere Überarbeitungen; die Wirksamkeit wird im Auszug nicht belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 64 % | 87 / 97 % | 91 / 97 % | 59 / 80 % | 55 / 78 % | 60 / 81 % | 40 / 80 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 32 / 62 % | 88 / 98 % | 77 / 94 % | 78 / 88 % | 77 / 87 % | 86 / 92 % | 77 / 91 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 58 / 81 % | 81 / 93 % | 85 / 96 % | 85 / 93 % | 73 / 87 % | 87 / 93 % | 88 / 95 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 51 % | 72 / 88 % | 86 / 95 % | 36 / 61 % | 32 / 57 % | 45 / 68 % | 13 / 49 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 56 % | 82 / 97 % | 80 / 96 % | 55 / 80 % | 66 / 84 % | 70 / 86 % | 62 / 86 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 21 / 52 % | 16 / 44 % | 82 / 93 % | 34 / 61 % | 16 / 43 % | 24 / 54 % | 14 / 54 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 17 / 46 % | 81 / 93 % | 41 / 61 % | 56 / 77 % | 30 / 50 % | 51 / 67 % | 29 / 54 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 55 % | 61 / 96 % | 74 / 88 % | 33 / 60 % | 24 / 47 % | 34 / 60 % | 15 / 48 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 44 % | 74 / 94 % | 60 / 77 % | 49 / 71 % | 36 / 60 % | 59 / 69 % | 14 / 27 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 23 / 49 % | 49 / 85 % | 69 / 81 % | 49 / 70 % | 34 / 57 % | 49 / 65 % | 28 / 54 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 21 / 53 % | 46 / 84 % | 48 / 83 % | 20 / 43 % | 40 / 68 % | 54 / 78 % | 31 / 71 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 49 / 79 % | 35 / 72 % | 18 / 42 % | 7 / 22 % | 11 / 27 % | 2 / 12 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 47 / 78 % | 20 / 53 % | 12 / 34 % | 3 / 13 % | 6 / 20 % | 1 / 6 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 9 / 31 % | 47 / 77 % | 6 / 18 % | 13 / 34 % | 6 / 22 % | 13 / 35 % | 4 / 21 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 16 / 47 % | 44 / 87 % | 38 / 56 % | 17 / 42 % | 8 / 28 % | 10 / 30 % | 4 / 19 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 20 / 46 % | 39 / 88 % | 15 / 35 % | 27 / 56 % | 20 / 42 % | 16 / 45 % | 10 / 35 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 29 % | 36 / 66 % | 38 / 67 % | 13 / 32 % | 5 / 20 % | 8 / 31 % | 2 / 14 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 36 / 77 % | 12 / 58 % | 37 / 65 % | 19 / 44 % | 10 / 36 % | 10 / 42 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 34 / 78 % | 5 / 34 % | 12 / 31 % | 4 / 16 % | 5 / 18 % | 1 / 9 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 33 / 81 % | 1 / 21 % | 11 / 31 % | 4 / 15 % | 6 / 17 % | 1 / 8 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 17 / 50 % | 22 / 51 % | 23 / 57 % | 31 / 58 % | 20 / 48 % | 16 / 39 % | 11 / 39 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 12 / 40 % | 23 / 50 % | 0 / 0 % | 25 / 56 % | 10 / 36 % | 27 / 58 % | 2 / 12 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 16 / 43 % | 24 / 51 % | 27 / 59 % | 19 / 43 % | 6 / 22 % | 11 / 28 % | 3 / 18 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 28 % | 27 / 81 % | 0 / 0 % | 8 / 24 % | 3 / 14 % | 5 / 16 % | 0 / 3 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 27 / 51 % | 5 / 13 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 15 / 33 % | 21 / 56 % | 21 / 49 % | 16 / 44 % | 5 / 15 % | 10 / 31 % | 1 / 6 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 19 / 81 % | 5 / 18 % | 7 / 23 % | 4 / 15 % | 5 / 17 % | 1 / 6 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 17 / 52 % | 16 / 42 % | 16 / 45 % | 5 / 21 % | 6 / 26 % | 1 / 7 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 16 / 44 % | 1 / 17 % | 7 / 18 % | 2 / 8 % | 5 / 17 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 11 / 40 % | 14 / 50 % | 12 / 36 % | 13 / 35 % | 6 / 17 % | 9 / 26 % | 1 / 5 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 36 % | 11 / 29 % | 8 / 25 % | 3 / 14 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 27 % | 3 / 24 % | 0 / 0 % | 10 / 34 % | 6 / 20 % | 9 / 28 % | 1 / 8 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 5 / 16 % | 8 / 20 % | 1 / 5 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 2 / 7 % | 6 / 13 % | 0 / 2 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 6 % | 5 / 13 % | 0 / 1 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 1 / 12 % | 7 / 21 % | 2 / 10 % | 0 / 0 % | 0 / 3 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 6 / 20 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 2 / 7 % | 5 / 13 % | 0 / 3 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | 0 / 0 % | – |
