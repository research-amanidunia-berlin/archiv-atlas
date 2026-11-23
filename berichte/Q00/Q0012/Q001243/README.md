[English](README.md) · [Deutsch](README.de.md)

# 2023 Alignment Research Updates

Report Q001243 · Source far.ai · Date 2026-08-19 · [Open original](https://www.far.ai/blog/2023-alignment-research-updates)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

FAR.AI berichtet über frühe Forschungsarbeiten zu Robustheit, Werteausrichtung und Bewertung von KI-Modellen, darunter adversariale Schwächen bei Go-Systemen, Lernen aus Sprachfeedback und neue Interpretierbarkeitsmethoden. Viele Ergebnisse sind vorläufig oder betreffen einzelne Anwendungen; zentrale Ziele wie verlässliche Sicherheitsgarantien und allgemeine Vorhersagen zur Robustheit bleiben laut Bericht offen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 48 / 70 % | 58 / 88 % | 91 / 97 % | 64 / 82 % | 40 / 66 % | 71 / 86 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 33 / 59 % | 71 / 98 % | 83 / 95 % | 54 / 77 % | 22 / 47 % | 43 / 73 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 57 % | 47 / 86 % | 77 / 93 % | 26 / 59 % | 5 / 23 % | 20 / 59 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 23 / 57 % | 23 / 94 % | 71 / 92 % | 9 / 29 % | 7 / 34 % | 18 / 57 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 57 / 85 % | 28 / 52 % | 15 / 45 % | 8 / 25 % | 9 / 22 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 26 / 54 % | 55 / 93 % | 43 / 79 % | 20 / 55 % | 11 / 32 % | 29 / 62 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 25 / 87 % | 52 / 76 % | 9 / 30 % | 1 / 8 % | 7 / 17 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 43 / 85 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 4 / 12 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 42 / 87 % | 17 / 49 % | 8 / 24 % | 1 / 8 % | 7 / 24 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 19 / 66 % | 32 / 59 % | 16 / 46 % | 2 / 12 % | 6 / 16 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 31 / 94 % | 2 / 32 % | 13 / 45 % | 4 / 17 % | 9 / 29 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 42 % | 30 / 83 % | 2 / 16 % | 8 / 28 % | 1 / 6 % | 5 / 11 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 28 / 93 % | 2 / 37 % | 15 / 44 % | 2 / 12 % | 8 / 22 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 37 % | 20 / 61 % | 0 / 5 % | 7 / 24 % | 3 / 15 % | 6 / 21 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 19 / 57 % | 10 / 27 % | 6 / 17 % | 0 / 6 % | 6 / 20 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 17 / 87 % | 1 / 20 % | 9 / 27 % | 2 / 10 % | 7 / 20 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 16 / 72 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 15 / 53 % | 0 / 0 % | 6 / 15 % | 1 / 8 % | 3 / 11 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 4 % | 10 / 23 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 10 / 50 % | 1 / 20 % | 5 / 12 % | 1 / 5 % | 6 / 13 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 2 / 38 % | 0 / 0 % | 6 / 24 % | 1 / 5 % | 9 / 19 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 9 / 51 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 31 % | 1 / 9 % | 5 / 14 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 8 / 27 % | 0 / 0 % | 8 / 17 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 28 % | 1 / 44 % | 0 / 5 % | 8 / 27 % | 1 / 12 % | 4 / 13 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 0 / 0 % | 6 / 14 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 5 / 13 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 3 / 63 % | 0 / 0 % | 6 / 16 % | 0 / 3 % | 3 / 7 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 2 / 4 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 5 / 14 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 67 % | 0 / 0 % | 5 / 12 % | 1 / 6 % | 2 / 10 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 2 / 5 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 56 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 8 % | 5 / 16 % | 1 / 7 % | 3 / 11 % | – | – |
