[English](README.md) · [Deutsch](README.de.md)

# AWS: Invalidate CloudFront Cache on S3 Upload

Report Q010784 · Source medium.com · Date 2024-02-01 · [Open original](https://medium.com/aws-tip/aws-invalidate-cloudfront-cache-on-s3-upload-4f2c0c8a2143)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt eine CDK-gestützte Lambda-Funktion, die bei neuen S3-Objekten eine CloudFront-Invalidierung anfordert, damit aktualisierte Inhalte nicht bis zum Ablauf des Caches warten müssen. Laut Autor dauert die Invalidierung mehrere Minuten; vorausgesetzt werden ein bestehender Bucket und eine CloudFront-Distribution.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
