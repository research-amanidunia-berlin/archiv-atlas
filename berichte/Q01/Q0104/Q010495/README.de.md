[English](README.md) · [Deutsch](README.de.md)

# AWS Cognito For API Gateway (Lambda Proxy) Access Control: Step By Step

Bericht Q010495 · Quelle medium.com · Datum 2025-01-23 · [Original öffnen](https://medium.com/gitconnected/aws-cognito-for-api-gateway-lambda-proxy-access-control-step-by-step-48b03475a78f)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erklärt, wie Cognito User Pools, Managed Login und ein Cognito-Authorizer für eine API-Gateway-Lambda-Proxy-API eingerichtet werden, sowohl über die AWS-Konsole als auch mit CDK. Laut Autor schützt die gezeigte Proxy-Konfiguration die API gemeinsam und erlaubt keine getrennte Zugriffskontrolle pro Methode; außerdem deaktiviert sein Rust-Beispiel zum Dekodieren von JWTs die Signaturprüfung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
