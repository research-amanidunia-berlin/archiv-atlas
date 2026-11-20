[English](README.md) · [Deutsch](README.de.md)

# Introducing Anthropic's Responsible Scaling Policy

Report Q003153 · Source anthropic.com · Date 2023-09-19 · [Open original](https://www.anthropic.com/news/anthropics-responsible-scaling-policy)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic stellt ein Regelwerk vor, das Schutzmaßnahmen für KI-Systeme an abgestuften Risiken ausrichten soll. Die höheren Sicherheitsstufen sind teils noch nicht ausgearbeitet; das Unternehmen hält die Richtlinie für vorläufig und erwartet Anpassungen, während eine Trainingspause nötig werden könnte, falls Sicherheitsmaßnahmen nicht mit der Skalierung Schritt halten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 43 / 63 % | 99 / 100 % | – | 100 / 100 % | 79 / 89 % | 65 / 84 % | 74 / 86 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 51 / 72 % | 98 / 100 % | – | 92 / 98 % | 78 / 88 % | 69 / 85 % | 84 / 91 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 48 / 66 % | 80 / 93 % | – | 97 / 99 % | 70 / 85 % | 43 / 66 % | 68 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 58 % | 97 / 99 % | – | 96 / 99 % | 53 / 78 % | 49 / 75 % | 67 / 82 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 19 / 46 % | 40 / 76 % | – | 97 / 99 % | 34 / 62 % | 9 / 31 % | 14 / 41 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 20 / 44 % | 80 / 96 % | – | 96 / 99 % | 36 / 62 % | 19 / 44 % | 24 / 58 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 24 / 47 % | 91 / 96 % | – | 84 / 94 % | 55 / 75 % | 20 / 39 % | 48 / 63 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 46 % | 86 / 95 % | – | 85 / 94 % | 34 / 57 % | 14 / 38 % | 32 / 55 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 23 / 49 % | 85 / 98 % | – | 81 / 92 % | 44 / 66 % | 17 / 46 % | 54 / 73 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 28 / 59 % | 58 / 86 % | – | 83 / 96 % | 16 / 38 % | 23 / 50 % | 41 / 66 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 30 % | 77 / 96 % | – | 49 / 79 % | 15 / 37 % | 5 / 20 % | 8 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 46 / 84 % | – | 73 / 88 % | 8 / 21 % | 1 / 8 % | 5 / 9 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 28 / 53 % | 67 / 93 % | – | 46 / 66 % | 23 / 51 % | 12 / 33 % | 29 / 52 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 31 / 57 % | 65 / 88 % | – | 66 / 81 % | 51 / 72 % | 31 / 56 % | 51 / 69 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 18 / 42 % | 66 / 97 % | – | 38 / 60 % | 21 / 44 % | 7 / 25 % | 9 / 25 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 45 / 92 % | – | 64 / 87 % | 30 / 58 % | 11 / 30 % | 8 / 20 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 10 / 31 % | 58 / 89 % | – | 11 / 29 % | 10 / 27 % | 5 / 19 % | 8 / 22 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 25 / 49 % | 22 / 68 % | – | 28 / 51 % | 43 / 68 % | 21 / 48 % | 48 / 70 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 23 / 50 % | 25 / 85 % | – | 48 / 81 % | 22 / 51 % | 8 / 35 % | 8 / 46 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 48 / 77 % | – | 41 / 76 % | 12 / 27 % | 6 / 22 % | 7 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 16 / 48 % | 47 / 80 % | – | 22 / 64 % | 21 / 48 % | 9 / 30 % | 8 / 19 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 40 % | 41 / 88 % | – | 32 / 72 % | 29 / 52 % | 8 / 27 % | 16 / 37 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 28 % | 37 / 91 % | – | 18 / 38 % | 9 / 26 % | 4 / 16 % | 6 / 16 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 36 / 79 % | – | 13 / 42 % | 9 / 21 % | 1 / 5 % | 3 / 10 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 34 / 65 % | – | 2 / 22 % | 7 / 22 % | 1 / 6 % | 6 / 17 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 19 / 33 % | 0 / 0 % | – | 0 / 0 % | 32 / 57 % | 4 / 12 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 32 / 84 % | – | 2 / 17 % | 6 / 12 % | 1 / 4 % | 5 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 6 / 26 % | 23 / 78 % | – | 3 / 19 % | 7 / 20 % | 2 / 12 % | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 12 / 37 % | 21 / 76 % | – | 20 / 52 % | 12 / 31 % | 5 / 16 % | 7 / 20 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 68 % | – | 1 / 12 % | 10 / 23 % | 1 / 7 % | 4 / 8 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 35 % | 14 / 40 % | – | 2 / 13 % | 11 / 35 % | 7 / 22 % | 12 / 27 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 12 / 86 % | – | 4 / 28 % | 9 / 22 % | 3 / 10 % | 4 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 11 / 34 % | 0 / 0 % | – | 4 / 19 % | 9 / 23 % | 3 / 10 % | 7 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 26 % | 6 / 17 % | 4 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 7 / 26 % | 9 / 24 % | 1 / 5 % | 5 / 17 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 4 / 25 % | 8 / 19 % | 1 / 7 % | 6 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 32 % | – | 0 / 0 % | 7 / 19 % | 2 / 6 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 3 / 43 % | – | 2 / 20 % | 7 / 17 % | 1 / 7 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 3 / 10 % | 6 / 19 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 1 / 3 % | 5 / 9 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 1 / 4 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 28 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
