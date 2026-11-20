[English](README.md) · [Deutsch](README.de.md)

# AWS: Invalidate CloudFront Cache on S3 Upload

Bericht Q010784 · Quelle medium.com · Datum 2024-02-01 · [Original öffnen](https://medium.com/aws-tip/aws-invalidate-cloudfront-cache-on-s3-upload-4f2c0c8a2143)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt eine CDK-gestützte Lambda-Funktion, die bei neuen S3-Objekten eine CloudFront-Invalidierung anfordert, damit aktualisierte Inhalte nicht bis zum Ablauf des Caches warten müssen. Laut Autor dauert die Invalidierung mehrere Minuten; vorausgesetzt werden ein bestehender Bucket und eine CloudFront-Distribution.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
