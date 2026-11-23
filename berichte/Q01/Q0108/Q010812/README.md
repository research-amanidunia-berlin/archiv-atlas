[English](README.md) · [Deutsch](README.de.md)

# Create and Invoke SageMaker Endpoint from Pre-trained Tensorflow Model

Report Q010812 · Source medium.com · Date 2023-11-08 · [Open original](https://medium.com/aws-tip/create-and-invoke-sagemaker-endpoint-from-pre-trained-tensorflow-model-1f78bde26c50)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht beschreibt die Bereitstellung eines vortrainierten TensorFlow-Modells als SageMaker-Endpunkt, einschließlich IAM-Rolle, Modellarchiv, S3 und Erstellung über SDK oder Konsole. Für Bildvorhersagen empfiehlt der Autor einen `TensorFlowPredictor`; sein OpenCV-Beispiel bereitet ein Gesicht für DeepFaces Emotionserkennung auf und gibt „happy“ als höchste Beispielklasse aus. Die Erfahrungen und der Ablauf sind beispielbezogen und keine allgemeine Bewertung von Kosten oder Sicherheit.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 90 / 97 % | 60 / 73 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 25 / 81 % | 36 / 55 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
