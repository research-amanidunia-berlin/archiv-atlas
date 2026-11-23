[English](README.md) · [Deutsch](README.de.md)

# AI to defend critical infrastructure

Report Q001075 · Source anthropic.com · Date 2026-01-08 · [Open original](https://www.anthropic.com/research/critical-infrastructure-defense)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge half Claude in einer PNNL-Simulation, Angriffe auf eine Wasseraufbereitungsanlage schneller nachzubilden: PNNL schätzte den Aufwand auf drei Stunden statt mehrerer Wochen. Der Versuch zeigt laut Bericht Potenzial für KI-gestützte Sicherheitsprüfungen, belegt aber weder die Abwehr realer Angriffe noch einen Einsatz in einer produktiven Anlage.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 20 / 42 % | 73 / 96 % | 91 / 96 % | 54 / 74 % | 5 / 19 % | 19 / 40 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 49 % | 61 / 87 % | 90 / 97 % | 35 / 60 % | 16 / 35 % | 38 / 60 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 21 / 47 % | 38 / 81 % | 64 / 89 % | 8 / 19 % | 21 / 46 % | 33 / 63 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 20 / 42 % | 57 / 84 % | 48 / 66 % | 32 / 56 % | 15 / 32 % | 29 / 49 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 55 / 87 % | 40 / 55 % | 16 / 43 % | 2 / 14 % | 5 / 12 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 21 / 43 % | 52 / 86 % | 54 / 76 % | 15 / 45 % | 12 / 30 % | 26 / 55 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 18 / 41 % | 50 / 90 % | 53 / 80 % | 20 / 49 % | 4 / 19 % | 16 / 37 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 35 % | 51 / 91 % | 52 / 73 % | 10 / 28 % | 4 / 12 % | 21 / 39 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 51 / 67 % | 5 / 13 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 10 / 33 % | 14 / 91 % | 42 / 66 % | 7 / 24 % | 4 / 16 % | 6 / 15 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 35 / 47 % | 14 / 38 % | 2 / 7 % | 10 / 18 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 26 / 48 % | 24 / 93 % | 12 / 63 % | 34 / 62 % | 27 / 48 % | 33 / 59 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 54 % | 29 / 51 % | 16 / 41 % | 3 / 11 % | 6 / 13 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 28 / 62 % | 7 / 20 % | 7 / 21 % | 3 / 13 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 14 / 28 % | 17 / 53 % | 20 / 45 % | 9 / 29 % | 2 / 7 % | 4 / 8 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 19 / 80 % | 2 / 29 % | 11 / 38 % | 1 / 8 % | 7 / 19 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 11 / 28 % | 0 / 0 % | 12 / 38 % | 18 / 44 % | 6 / 18 % | 13 / 26 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 7 / 48 % | 1 / 9 % | 11 / 30 % | 8 / 20 % | 15 / 26 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 15 / 32 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 4 / 11 % | 12 / 25 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 35 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 6 / 30 % | 14 / 44 % | 0 / 0 % | 9 / 24 % | 2 / 12 % | 8 / 21 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 11 / 27 % | 0 / 0 % | 13 / 44 % | 7 / 23 % | 4 / 15 % | 8 / 22 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 12 / 30 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 3 / 11 % | 8 / 16 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 8 / 22 % | 4 / 27 % | 10 / 25 % | 8 / 22 % | 1 / 5 % | 6 / 11 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 10 / 18 % | 0 / 0 % | 1 / 10 % | 8 / 28 % | 1 / 4 % | 6 / 13 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 7 / 30 % | 5 / 41 % | 1 / 15 % | 9 / 30 % | 1 / 6 % | 4 / 9 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 9 / 36 % | 8 / 24 % | 2 / 9 % | 5 / 13 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 5 % | 7 / 13 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 31 % | 6 / 33 % | 2 / 16 % | 7 / 23 % | 2 / 14 % | 7 / 20 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 8 % | 7 / 16 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 7 / 16 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 14 % | 6 / 19 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 5 / 11 % | 6 / 16 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 3 % | 5 / 9 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 5 / 8 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 6 % | 3 / 5 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 5 / 35 % | 5 / 9 % | 1 / 2 % | 5 / 8 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 11 % | 1 / 3 % | 5 / 8 % | – | – |
