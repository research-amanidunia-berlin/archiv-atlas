[English](README.md) · [Deutsch](README.de.md)

# AWS: Service Error While Calling Rekognition Video Start Operation from Lambda

Report Q010603 · Source medium.com · Date 2024-08-30 · [Open original](https://medium.com/gitconnected/aws-service-error-while-calling-rekognition-video-start-operation-from-lambda-76e7e225779a)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Ein Autor berichtet, dass seine auf AWS bereitgestellte Lambda-Funktion bei einer Rekognition-Video-Startoperation trotz vorhandener Rekognition-Berechtigungen einen nicht näher erklärten „service error“ ausgab. In seinem Fall löste eine auf die Rekognition-Dienstrolle beschränkte `iam:PassRole`-Berechtigung das Problem; der Artikel belegt nicht, dass dies die Ursache ähnlicher Fehler allgemein ist.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
