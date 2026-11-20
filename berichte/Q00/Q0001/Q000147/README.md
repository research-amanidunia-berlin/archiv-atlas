[English](README.md) · [Deutsch](README.de.md)

# Key Practices for Incident Readiness and Response in Super Intelligence Training and Evaluation

Report Q000147 · Source go.dhs.gov · Date 2026-10-16 · [Open original](https://go.dhs.gov/5rZ)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Text beschreibt eine freiwillige Anleitung von NIST, NSA SISC und CISA zur Vorbereitung auf Kontrollvorfälle mit leistungsfähigen Super-Intelligence-Agenten. Sie behandelt unter anderem Zugriffsbeschränkung, Überwachung, Beweissicherung, Eindämmung und Meldung von Vorfällen. Der vorliegende Text ist nur eine kurze Vorstellung der Anleitung; die zehn Praktiken werden nicht einzeln erläutert.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 47 / 61 % | 94 / 99 % | 64 / 83 % | – | 66 / 83 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 49 / 65 % | 88 / 97 % | 85 / 94 % | – | 73 / 87 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 42 / 63 % | 71 / 93 % | 86 / 93 % | – | 73 / 86 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 37 / 58 % | 82 / 92 % | 86 / 91 % | – | 62 / 78 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 55 / 73 % | 72 / 91 % | 85 / 93 % | – | 77 / 88 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 42 / 61 % | 67 / 83 % | 64 / 75 % | – | 72 / 85 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 24 / 41 % | 35 / 53 % | 26 / 56 % | – | 55 / 76 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 49 % | 54 / 88 % | 24 / 58 % | – | 42 / 71 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 30 / 53 % | 52 / 89 % | 32 / 61 % | – | 35 / 61 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 30 % | 43 / 89 % | 7 / 22 % | – | 19 / 47 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 43 / 61 % | 39 / 74 % | 43 / 68 % | – | 43 / 66 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 17 / 44 % | 42 / 91 % | 20 / 48 % | – | 38 / 65 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 39 / 76 % | 9 / 23 % | – | 28 / 52 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 33 / 81 % | 2 / 10 % | – | 16 / 45 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 32 / 61 % | 1 / 5 % | – | 9 / 22 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 30 / 51 % | 26 / 91 % | 14 / 34 % | – | 31 / 55 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 30 / 52 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 12 / 35 % | 27 / 69 % | 7 / 23 % | – | 13 / 31 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 24 / 48 % | 0 / 0 % | – | 8 / 23 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 24 / 44 % | 0 / 0 % | 8 / 23 % | – | 20 / 47 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 23 / 58 % | 1 / 3 % | – | 6 / 15 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 22 / 55 % | 1 / 5 % | – | 8 / 19 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 19 / 78 % | 0 / 0 % | – | 6 / 14 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 12 / 43 % | 0 / 0 % | 7 / 20 % | – | 18 / 44 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 9 / 23 % | – | 16 / 40 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 1 / 5 % | – | 15 / 43 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 14 / 40 % | 1 / 5 % | – | 8 / 22 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 2 / 8 % | – | 14 / 35 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 29 % | 0 / 0 % | 0 / 3 % | – | 7 / 20 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 11 / 56 % | 0 / 2 % | – | 5 / 12 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 2 / 10 % | – | 9 / 26 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 9 / 62 % | 1 / 8 % | – | 9 / 28 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 1 / 3 % | – | 9 / 21 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 19 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 1 / 5 % | – | 8 / 17 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 18 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | – |
