[English](README.md) · [Deutsch](README.de.md)

# nemotron-3.5-super-vl-120b-a12b Model by NVIDIA

Report Q004895 · Source build.nvidia.com · Date – · [Open original](https://build.nvidia.com/nvidia/nemotron-3.5-super-vl-120b-a12b/modelcard)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

NVIDIA beschreibt Nemotron 3.5 Super VL NVFP4 als quantisiertes multimodales Modell mit 120 Milliarden Parametern und einem Kontextfenster von bis zu einer Million Token. Die gemeldeten Benchmarkwerte fallen je nach Aufgabe ähnlich, höher oder niedriger als beim BF16-Modell aus; Trainingsangaben und einzelne Prüfverfahren weisen laut Karte offene beziehungsweise noch nicht öffentlich dokumentierte Details auf.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 71 / 84 % | 100 / 100 % | 90 / 95 % | 100 / 100 % | 93 / 96 % | 88 / 93 % | 64 / 76 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 41 / 63 % | 93 / 98 % | 12 / 22 % | 99 / 100 % | 68 / 83 % | 54 / 69 % | 13 / 24 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 60 % | 55 / 92 % | 13 / 29 % | 98 / 99 % | 54 / 78 % | 48 / 73 % | 15 / 31 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 33 / 53 % | 90 / 99 % | 8 / 22 % | 96 / 98 % | 60 / 81 % | 44 / 70 % | 8 / 22 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 23 / 48 % | 35 / 81 % | 2 / 10 % | 88 / 93 % | 35 / 65 % | 19 / 54 % | 5 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 76 / 94 % | 3 / 12 % | 87 / 93 % | 39 / 67 % | 21 / 45 % | 2 / 8 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 25 / 76 % | 2 / 8 % | 77 / 89 % | 28 / 55 % | 8 / 21 % | 2 / 7 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 45 % | 47 / 68 % | 1 / 6 % | 76 / 85 % | 29 / 55 % | 16 / 33 % | 3 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 22 / 48 % | 45 / 72 % | 13 / 29 % | 74 / 81 % | 41 / 66 % | 28 / 52 % | 1 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 31 / 50 % | 74 / 93 % | 22 / 35 % | 71 / 83 % | 42 / 64 % | 25 / 40 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 28 / 57 % | 0 / 0 % | 68 / 80 % | 9 / 26 % | 8 / 18 % | 1 / 4 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 64 / 88 % | 1 / 8 % | 37 / 72 % | 33 / 59 % | 18 / 40 % | 2 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 63 / 70 % | 41 / 64 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 59 / 66 % | 15 / 34 % | 14 / 27 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 45 / 73 % | 0 / 0 % | 58 / 81 % | 8 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 27 / 52 % | 50 / 80 % | 7 / 21 % | 55 / 78 % | 35 / 62 % | 24 / 50 % | 4 / 14 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 29 / 55 % | 51 / 82 % | 20 / 40 % | 26 / 53 % | 48 / 72 % | 32 / 54 % | 7 / 16 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 22 / 69 % | 1 / 7 % | 51 / 77 % | 20 / 56 % | 11 / 45 % | 2 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 51 / 84 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 43 / 71 % | 0 / 0 % | 50 / 62 % | 7 / 21 % | 6 / 16 % | 1 / 4 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 40 / 87 % | 0 / 2 % | 11 / 39 % | 14 / 42 % | 8 / 24 % | 1 / 4 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 33 % | 35 / 81 % | 0 / 3 % | 1 / 12 % | 12 / 33 % | 11 / 30 % | 1 / 8 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 30 / 60 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 7 / 15 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 25 / 56 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 1 / 4 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 22 / 57 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 8 / 15 % | 1 / 4 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 44 % | 13 / 23 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 16 / 39 % | 5 / 11 % | 2 / 6 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 35 % | 10 / 21 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 28 % | 10 / 23 % | 0 / 3 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 27 % | 8 / 14 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 5 / 12 % | 0 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 3 / 5 % | 0 / 2 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 14 % | 7 / 21 % | 4 / 13 % | 1 / 6 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 7 / 19 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 4 / 8 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 6 % | 0 / 2 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 5 / 10 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 5 / 12 % | 1 / 3 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
