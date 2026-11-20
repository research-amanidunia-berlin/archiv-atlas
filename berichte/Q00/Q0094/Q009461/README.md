[English](README.md) · [Deutsch](README.de.md)

# gpt-oss-120b & gpt-oss-20b Model Card

Report Q009461 · Source arxiv.org · Date – · [Open original](https://arxiv.org/pdf/2508.10925)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt zwei offene Modelle, die bei mehreren Mathematik-, Programmier- und Werkzeugtests starke Ergebnisse erzielen, aber bei Faktenfragen ohne Webzugriff häufiger halluzinieren und Anweisungsrangfolgen weniger zuverlässig schützen als o4-mini. Laut den berichteten Tests erreichten weder die Standardmodelle noch adversarial angepasste Varianten die internen Schwellen für hohe Fähigkeiten in Biologie/Chemie, Cybersecurity oder KI-Selbstverbesserung; die Aussage ist auf die geprüften Bedingungen begrenzt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 27 / 53 % | 100 / 100 % | 30 / 55 % | – | 59 / 83 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 64 / 78 % | 97 / 98 % | 80 / 91 % | – | 86 / 93 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 62 / 77 % | 96 / 97 % | 73 / 84 % | – | 91 / 95 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 32 / 53 % | 96 / 99 % | 35 / 57 % | – | 71 / 85 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 48 / 65 % | 95 / 96 % | 84 / 91 % | – | 81 / 90 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 65 / 79 % | 93 / 97 % | 94 / 97 % | – | 87 / 94 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 30 / 52 % | 92 / 97 % | 11 / 22 % | – | 56 / 77 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 39 / 58 % | 89 / 97 % | 31 / 54 % | – | 77 / 88 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 44 / 62 % | 87 / 97 % | 65 / 83 % | – | 83 / 91 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 26 / 42 % | 86 / 99 % | 6 / 14 % | – | 27 / 53 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 46 / 65 % | 80 / 96 % | 30 / 50 % | – | 79 / 89 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 40 / 62 % | 76 / 92 % | 51 / 67 % | – | 79 / 89 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 34 / 54 % | 78 / 98 % | 33 / 56 % | – | 78 / 89 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 50 / 84 % | 26 / 44 % | – | 77 / 89 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 43 / 63 % | 44 / 79 % | 24 / 49 % | – | 76 / 88 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 38 / 55 % | 73 / 97 % | 35 / 48 % | – | 44 / 70 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 64 / 80 % | 1 / 5 % | – | 15 / 34 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 25 / 51 % | 62 / 93 % | 8 / 14 % | – | 46 / 70 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 58 / 89 % | 1 / 4 % | – | 14 / 36 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 56 / 81 % | 1 / 4 % | – | 10 / 27 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 21 / 51 % | 0 / 0 % | 11 / 20 % | – | 45 / 69 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 45 / 90 % | 0 / 0 % | – | 10 / 27 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 35 % | 42 / 87 % | 4 / 12 % | – | 21 / 44 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 41 / 92 % | 0 / 0 % | – | 10 / 30 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 29 / 86 % | 0 / 0 % | – | 11 / 27 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 25 / 59 % | 0 / 0 % | 1 / 4 % | – | 16 / 41 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 20 / 76 % | 0 / 2 % | – | 9 / 24 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 16 / 45 % | 0 / 0 % | – | 16 / 33 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 7 % | – | 16 / 39 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 14 / 31 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 10 / 23 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 23 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 20 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 16 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 18 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 5 / 50 % | 0 / 0 % | – | 7 / 15 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 18 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | – |
