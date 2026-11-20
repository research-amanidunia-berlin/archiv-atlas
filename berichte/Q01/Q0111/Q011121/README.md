[English](README.md) · [Deutsch](README.de.md)

# Accelerating the Entire Deep Learning Pipeline

Report Q011121 · Source medium.com · Date 2019-05-03 · [Open original](https://medium.com/@NvidiaAI/accelerating-the-entire-deep-learning-pipeline-bff0e4e05fc)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag beschreibt NVIDIAs Werkzeuge zur Beschleunigung der Deep-Learning-Pipeline: DALI für die Datenvorbereitung, AMP für gemischte FP16/FP32-Berechnungen, TensorRT zur Inferenzoptimierung und den TensorRT Inference Server für den Produktionsbetrieb. Die Leistungsangaben, darunter bis zu vierfach schnellere Trainingslösung mit AMP, stammen von NVIDIA; unabhängige Belege oder Messbedingungen werden nicht genannt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 24 / 83 % | 0 / 0 % | 68 / 84 % | 8 / 21 % | 3 / 11 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 22 / 79 % | 0 / 0 % | 3 / 21 % | 5 / 11 % | 2 / 6 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 14 / 49 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 13 / 58 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 8 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 9 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 9 / 49 % | 0 / 0 % | 3 / 20 % | 5 / 17 % | 3 / 11 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 9 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 4 / 10 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 6 / 42 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 2 / 29 % | 0 / 0 % | 1 / 10 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 65 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 7 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 10 % | 0 / 0 % |
