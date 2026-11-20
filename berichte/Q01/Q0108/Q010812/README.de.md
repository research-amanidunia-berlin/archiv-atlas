[English](README.md) · [Deutsch](README.de.md)

# Create and Invoke SageMaker Endpoint from Pre-trained Tensorflow Model

Bericht Q010812 · Quelle medium.com · Datum 2023-11-08 · [Original öffnen](https://medium.com/aws-tip/create-and-invoke-sagemaker-endpoint-from-pre-trained-tensorflow-model-1f78bde26c50)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht beschreibt die Bereitstellung eines vortrainierten TensorFlow-Modells als SageMaker-Endpunkt, einschließlich IAM-Rolle, Modellarchiv, S3 und Erstellung über SDK oder Konsole. Für Bildvorhersagen empfiehlt der Autor einen `TensorFlowPredictor`; sein OpenCV-Beispiel bereitet ein Gesicht für DeepFaces Emotionserkennung auf und gibt „happy“ als höchste Beispielklasse aus. Die Erfahrungen und der Ablauf sind beispielbezogen und keine allgemeine Bewertung von Kosten oder Sicherheit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 90 / 97 % | 0 / 0 % | 60 / 73 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 25 / 81 % | 0 / 0 % | 36 / 55 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
