[English](README.md) · [Deutsch](README.de.md)

# Swift: When ExtensionContext.Open Does NOT Open My App! + Solution!

Bericht Q009829 · Quelle medium.com · Datum 2026-04-07 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-when-extensioncontext-open-does-not-open-my-app-solution-eaf59ab552c2)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt, dass `extensionContext?.open(url)` seine App aus einer iOS-Tastaturerweiterung nicht öffnet, obwohl das URL-Schema aus Safari funktioniert. Er berichtet von Erfolg mit `EnvironmentValues().openURL(url)`, belegt dies aber nur anhand seines Einzelfalls und nennt keine Versionen oder unabhängigen Tests.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
