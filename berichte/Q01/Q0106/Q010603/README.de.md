[English](README.md) · [Deutsch](README.de.md)

# AWS: Service Error While Calling Rekognition Video Start Operation from Lambda

Bericht Q010603 · Quelle medium.com · Datum 2024-08-30 · [Original öffnen](https://medium.com/gitconnected/aws-service-error-while-calling-rekognition-video-start-operation-from-lambda-76e7e225779a)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Ein Autor berichtet, dass seine auf AWS bereitgestellte Lambda-Funktion bei einer Rekognition-Video-Startoperation trotz vorhandener Rekognition-Berechtigungen einen nicht näher erklärten „service error“ ausgab. In seinem Fall löste eine auf die Rekognition-Dienstrolle beschränkte `iam:PassRole`-Berechtigung das Problem; der Artikel belegt nicht, dass dies die Ursache ähnlicher Fehler allgemein ist.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
