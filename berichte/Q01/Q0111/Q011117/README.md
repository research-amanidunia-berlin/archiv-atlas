[English](README.md) · [Deutsch](README.de.md)

# Kubeflow Pipelines With GPUs

Report Q011117 · Source medium.com · Date 2019-07-01 · [Open original](https://medium.com/better-programming/kubeflow-pipelines-with-gpus-1af6a74ec2a)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag erklärt Kubeflow Pipelines anhand eines GPU-gestützten ResNet-50-Beispiels: Container übernehmen Bildvorverarbeitung, Training und Bereitstellung; TensorFlow-TensorRT und der TensorRT Inference Server sollen die Inferenz beschleunigen und skalieren. Die versprochenen Vorteile für Modularität und Leistung werden beschrieben, aber nicht mit Benchmarks oder Messwerten belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 28 / 84 % | 0 / 0 % | 61 / 84 % | 8 / 20 % | 0 / 0 % | 3 / 9 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 49 / 86 % | 0 / 0 % | 57 / 78 % | 9 / 28 % | 0 / 0 % | 3 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 12 / 67 % | 0 / 0 % | 2 / 26 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 10 / 71 % | 0 / 0 % | 1 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 79 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 3 / 8 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 3 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 7 % |
