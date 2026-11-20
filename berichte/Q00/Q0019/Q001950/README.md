[English](README.md) · [Deutsch](README.de.md)

# Practical challenges of control monitoring in frontier AI deployments

Report Q001950 · Source aisi.gov.uk · Date 2025-12-15 · [Open original](https://www.aisi.gov.uk/research/practical-challenges-of-control-monitoring-in-frontier-ai-deployments)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Text ist nur der Abstract eines Berichts über Kontrollmonitore für leistungsfähige KI-Agenten. Er beschreibt Herausforderungen wie parallele Instanzen und verzögerte Aufsicht und kündigt einen Vergleich dreier Überwachungsformen sowie vier Fallstudien an, enthält aber weder deren Ergebnisse noch eine Empfehlung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 18 / 42 % | 53 / 89 % | – | 80 / 89 % | 36 / 61 % | 25 / 48 % | 10 / 32 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 56 % | 40 / 92 % | – | 63 / 90 % | 31 / 61 % | 26 / 58 % | 22 / 53 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 39 / 62 % | 32 / 87 % | – | 58 / 90 % | 50 / 72 % | 42 / 66 % | 20 / 51 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 37 / 60 % | 26 / 84 % | – | 41 / 84 % | 44 / 69 % | 48 / 70 % | 20 / 48 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 39 / 59 % | 33 / 96 % | – | 23 / 71 % | 29 / 57 % | 27 / 48 % | 9 / 26 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 32 / 54 % | 0 / 0 % | – | 0 / 0 % | 37 / 63 % | 33 / 51 % | 5 / 17 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 51 % | 12 / 95 % | – | 0 / 0 % | 19 / 47 % | 17 / 37 % | 12 / 31 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 20 / 43 % | 22 / 96 % | – | 21 / 80 % | 26 / 54 % | 20 / 37 % | 9 / 24 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 22 / 52 % | – | 0 / 0 % | 9 / 25 % | 6 / 16 % | 1 / 5 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 21 / 62 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 1 / 4 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 41 % | 20 / 58 % | – | 0 / 0 % | 10 / 27 % | 9 / 19 % | 2 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 20 / 57 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 18 / 39 % | 7 / 85 % | – | 0 / 0 % | 10 / 26 % | 9 / 17 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 18 / 49 % | – | 7 / 35 % | 6 / 12 % | 3 / 8 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 17 / 54 % | – | 0 / 0 % | 13 / 32 % | 11 / 22 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 14 / 50 % | 5 / 15 % | 0 / 0 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 32 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 27 % | 5 / 14 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 31 % | 7 / 21 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 27 % | 6 / 13 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 9 / 29 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 7 / 16 % | 3 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 8 / 40 % | 9 / 23 % | 4 / 9 % | 1 / 4 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 20 % | 7 / 17 % | 2 / 7 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 5 / 24 % | 8 / 17 % | 0 / 0 % | 1 / 4 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 0 / 0 % | 0 / 3 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 6 / 17 % | 0 / 2 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 3 / 6 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 5 / 8 % | 0 / 1 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 36 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
