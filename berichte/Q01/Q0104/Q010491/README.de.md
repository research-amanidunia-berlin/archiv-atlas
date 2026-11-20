[English](README.md) · [Deutsch](README.de.md)

# AWS CDK: Custom Resource

Bericht Q010491 · Quelle medium.com · Datum 2025-01-24 · [Original öffnen](https://medium.com/gitconnected/aws-cdk-custom-resource-cdb07f755333)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag beschreibt zwei Wege, CloudFormation-Custom-Resources mit AWS CDK umzusetzen: über `Provider` und `CustomResource` mit eigener Lambda oder über `AwsCustomResource` für AWS-SDK-Aktionen. Er erklärt Anfrage- und Antwortverarbeitung, die Bedeutung der stabilen `PhysicalResourceId` sowie Hinweise zu Fehlern, sensiblen Daten, Berechtigungen und erzwungenen Updates.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
