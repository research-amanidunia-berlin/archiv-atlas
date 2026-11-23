[English](README.md) · [Deutsch](README.de.md)

# Introducing the Frontier Safety Framework

Report Q002877 · Source deepmind.google · Date 2024-05-17 · [Open original](https://deepmind.google/blog/introducing-the-frontier-safety-framework/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Googles Frontier Safety Framework soll kritische KI-Fähigkeiten anhand festgelegter Schwellen und regelmäßiger Frühwarnprüfungen erkennen und bei Bedarf Schutzmaßnahmen auslösen. Die erste Fassung betrachtet vier Risikobereiche und bleibt laut Bericht vorläufig; die Forschung sei noch jung, und stärkere Schutzmaßnahmen könnten Innovation und Zugang einschränken.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 41 / 66 % | 98 / 100 % | 86 / 98 % | 73 / 86 % | 62 / 81 % | 80 / 88 % | 77 / 93 % | 61 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 57 % | 81 / 95 % | 93 / 99 % | 49 / 77 % | 41 / 69 % | 66 / 83 % | 47 / 80 % | 17 / 37 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 58 % | 93 / 99 % | 72 / 91 % | 57 / 78 % | 39 / 66 % | 67 / 82 % | 50 / 80 % | 39 / 64 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 49 / 69 % | 87 / 98 % | 92 / 99 % | 77 / 89 % | 47 / 72 % | 78 / 87 % | 72 / 88 % | 32 / 59 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 37 / 65 % | 63 / 90 % | 91 / 99 % | 28 / 53 % | 47 / 74 % | 69 / 83 % | 71 / 92 % | 39 / 69 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 41 % | 22 / 54 % | 88 / 96 % | 23 / 51 % | 7 / 29 % | 11 / 35 % | 7 / 33 % | 20 / 47 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 42 % | 60 / 90 % | 87 / 96 % | 23 / 49 % | 10 / 26 % | 22 / 43 % | 6 / 22 % | 13 / 33 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 25 / 51 % | 85 / 96 % | 84 / 94 % | 55 / 77 % | 32 / 63 % | 67 / 79 % | 22 / 39 % | 26 / 54 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 23 / 50 % | 76 / 92 % | 73 / 92 % | 57 / 78 % | 16 / 44 % | 51 / 68 % | 45 / 70 % | 30 / 56 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 18 / 48 % | 67 / 97 % | 57 / 85 % | 34 / 60 % | 18 / 43 % | 44 / 66 % | 20 / 48 % | 17 / 46 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 10 / 25 % | 62 / 94 % | 56 / 85 % | 12 / 32 % | 5 / 23 % | 9 / 28 % | 1 / 13 % | 19 / 44 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 41 / 78 % | 62 / 83 % | 7 / 21 % | 1 / 6 % | 9 / 15 % | 0 / 0 % | 17 / 36 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 43 % | 43 / 88 % | 61 / 83 % | 23 / 51 % | 13 / 31 % | 18 / 46 % | 6 / 27 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 21 / 49 % | 52 / 90 % | 61 / 91 % | 44 / 68 % | 12 / 34 % | 32 / 57 % | 12 / 40 % | 26 / 55 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 12 / 37 % | 58 / 87 % | 49 / 68 % | 24 / 50 % | 7 / 28 % | 11 / 27 % | 5 / 19 % | 11 / 34 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 14 / 44 % | 55 / 91 % | 42 / 80 % | 23 / 50 % | 7 / 29 % | 11 / 22 % | 5 / 22 % | 18 / 43 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 32 % | 50 / 95 % | 43 / 63 % | 9 / 31 % | 4 / 18 % | 7 / 19 % | 1 / 6 % | 15 / 39 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 35 / 82 % | 47 / 84 % | 47 / 71 % | 15 / 41 % | 9 / 23 % | 14 / 43 % | 16 / 44 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 9 / 31 % | 45 / 92 % | 7 / 27 % | 9 / 25 % | 3 / 18 % | 9 / 22 % | 2 / 14 % | 25 / 51 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 9 / 26 % | 41 / 91 % | 23 / 72 % | 14 / 34 % | 5 / 19 % | 8 / 23 % | 2 / 13 % | 16 / 45 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 18 / 48 % | 6 / 55 % | 9 / 35 % | 25 / 56 % | 13 / 39 % | 29 / 66 % | 2 / 12 % | 5 / 18 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 35 % | 21 / 85 % | 18 / 48 % | 8 / 25 % | 4 / 18 % | 7 / 20 % | 2 / 10 % | 21 / 50 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 14 / 73 % | 21 / 51 % | 10 / 27 % | 1 / 5 % | 6 / 15 % | 0 / 4 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 42 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 19 / 44 % | 18 / 83 % | 13 / 56 % | 15 / 47 % | 4 / 21 % | 12 / 49 % | 1 / 10 % | 10 / 32 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 19 / 58 % | 0 / 0 % | 8 / 19 % | 0 / 2 % | 6 / 14 % | 0 / 0 % | 8 / 28 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 50 % | 7 / 56 % | 12 / 49 % | 18 / 44 % | 5 / 19 % | 8 / 21 % | 5 / 21 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 15 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 17 / 42 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 37 % | 4 / 64 % | 9 / 33 % | 15 / 42 % | 6 / 18 % | 13 / 31 % | 6 / 23 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 14 / 63 % | 1 / 14 % | 7 / 18 % | 1 / 7 % | 8 / 16 % | 0 / 2 % | 3 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 34 % | 5 / 35 % | 0 / 0 % | 8 / 21 % | 3 / 11 % | 8 / 21 % | 1 / 5 % | 5 / 20 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 11 / 41 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 10 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 8 / 31 % | 10 / 26 % | 0 / 3 % | 8 / 17 % | 0 / 4 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 7 / 44 % | 8 / 27 % | 8 / 24 % | 1 / 7 % | 9 / 17 % | 0 / 3 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 7 % | 6 / 19 % | 0 / 3 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 2 / 31 % | 3 / 27 % | 7 / 18 % | 1 / 8 % | 8 / 18 % | 0 / 3 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 2 / 6 % | 5 / 9 % | 0 / 0 % | 7 / 22 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 7 / 44 % | 2 / 14 % | 6 / 15 % | 1 / 5 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 41 % | 1 / 21 % | 7 / 18 % | 1 / 5 % | 5 / 12 % | 0 / 2 % | 5 / 21 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 2 / 41 % | 0 / 4 % | 6 / 15 % | 2 / 7 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 11 % | 0 / 0 % | 4 / 10 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
