[English](README.md) · [Deutsch](README.de.md)

# Rust: Implement OAuth 2.0: Login with Google

Bericht Q010497 · Quelle medium.com · Datum 2025-01-19 · [Original öffnen](https://medium.com/gitconnected/rust-implement-oauth-2-0-login-with-google-240364271591)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag erklärt einen Google-OAuth-Login für Rust-CLIs: Ein lokaler Axum-Server verarbeitet den Callback, tauscht den Code gegen Tokens und gibt diese per Kanal an das Hauptprogramm weiter. Er zeigt außerdem Browserabbruch und Tokenaktualisierung; die Beispiele konzentrieren sich auf den Profilabruf, und manche Hinweise – etwa zur Chrome-Konfiguration – beruhen auf der Erfahrung des Autors.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
