[English](README.md) · [Deutsch](README.de.md)

# Introducing the Frontier Safety Framework

Report Q002877 · Source deepmind.google · Date 2024-05-17 · [Open original](https://deepmind.google/blog/introducing-the-frontier-safety-framework/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Googles Frontier Safety Framework soll kritische KI-Fähigkeiten anhand festgelegter Schwellen und regelmäßiger Frühwarnprüfungen erkennen und bei Bedarf Schutzmaßnahmen auslösen. Die erste Fassung betrachtet vier Risikobereiche und bleibt laut Bericht vorläufig; die Forschung sei noch jung, und stärkere Schutzmaßnahmen könnten Innovation und Zugang einschränken.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 41 / 66 % | 98 / 100 % | 77 / 93 % | 86 / 98 % | 73 / 86 % | 80 / 88 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 57 % | 81 / 95 % | 47 / 80 % | 93 / 99 % | 49 / 77 % | 66 / 83 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 58 % | 93 / 99 % | 50 / 80 % | 72 / 91 % | 57 / 78 % | 67 / 82 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 49 / 69 % | 87 / 98 % | 72 / 88 % | 92 / 99 % | 77 / 89 % | 78 / 87 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 37 / 65 % | 63 / 90 % | 71 / 92 % | 91 / 99 % | 28 / 53 % | 69 / 83 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 41 % | 22 / 54 % | 7 / 33 % | 88 / 96 % | 23 / 51 % | 11 / 35 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 42 % | 60 / 90 % | 6 / 22 % | 87 / 96 % | 23 / 49 % | 22 / 43 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 25 / 51 % | 85 / 96 % | 22 / 39 % | 84 / 94 % | 55 / 77 % | 67 / 79 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 23 / 50 % | 76 / 92 % | 45 / 70 % | 73 / 92 % | 57 / 78 % | 51 / 68 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 18 / 48 % | 67 / 97 % | 20 / 48 % | 57 / 85 % | 34 / 60 % | 44 / 66 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 10 / 25 % | 62 / 94 % | 1 / 13 % | 56 / 85 % | 12 / 32 % | 9 / 28 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 41 / 78 % | 0 / 0 % | 62 / 83 % | 7 / 21 % | 9 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 43 % | 43 / 88 % | 6 / 27 % | 61 / 83 % | 23 / 51 % | 18 / 46 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 21 / 49 % | 52 / 90 % | 12 / 40 % | 61 / 91 % | 44 / 68 % | 32 / 57 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 12 / 37 % | 58 / 87 % | 5 / 19 % | 49 / 68 % | 24 / 50 % | 11 / 27 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 14 / 44 % | 55 / 91 % | 5 / 22 % | 42 / 80 % | 23 / 50 % | 11 / 22 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 32 % | 50 / 95 % | 1 / 6 % | 43 / 63 % | 9 / 31 % | 7 / 19 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 35 / 82 % | 14 / 43 % | 47 / 84 % | 47 / 71 % | 9 / 23 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 9 / 31 % | 45 / 92 % | 2 / 14 % | 7 / 27 % | 9 / 25 % | 9 / 22 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 9 / 26 % | 41 / 91 % | 2 / 13 % | 23 / 72 % | 14 / 34 % | 8 / 23 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 18 / 48 % | 6 / 55 % | 2 / 12 % | 9 / 35 % | 25 / 56 % | 29 / 66 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 35 % | 21 / 85 % | 2 / 10 % | 18 / 48 % | 8 / 25 % | 7 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 14 / 73 % | 0 / 4 % | 21 / 51 % | 10 / 27 % | 6 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 42 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 19 / 44 % | 18 / 83 % | 1 / 10 % | 13 / 56 % | 15 / 47 % | 12 / 49 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 19 / 58 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 6 / 14 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 50 % | 7 / 56 % | 5 / 21 % | 12 / 49 % | 18 / 44 % | 8 / 21 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 37 % | 4 / 64 % | 6 / 23 % | 9 / 33 % | 15 / 42 % | 13 / 31 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 14 / 63 % | 0 / 2 % | 1 / 14 % | 7 / 18 % | 8 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 34 % | 5 / 35 % | 1 / 5 % | 0 / 0 % | 8 / 21 % | 8 / 21 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 11 / 41 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 6 / 14 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 8 / 31 % | 10 / 26 % | 8 / 17 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 7 / 44 % | 0 / 3 % | 8 / 27 % | 8 / 24 % | 9 / 17 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 9 / 24 % | 6 / 19 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 2 / 31 % | 0 / 3 % | 3 / 27 % | 7 / 18 % | 8 / 18 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 5 / 9 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 7 / 44 % | 0 / 0 % | 2 / 14 % | 6 / 15 % | 7 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 41 % | 0 / 2 % | 1 / 21 % | 7 / 18 % | 5 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 2 / 41 % | 0 / 0 % | 0 / 4 % | 6 / 15 % | 7 / 14 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 6 / 14 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 11 % | 0 / 0 % | 5 / 12 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
