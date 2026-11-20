[English](README.md) · [Deutsch](README.de.md)

# Tailwind Style Not Show Up in NextJs Standalone (Regular Build & Docker)

Bericht Q010487 · Quelle medium.com · Datum 2025-01-25 · [Original öffnen](https://medium.com/gitconnected/tailwind-style-not-show-up-in-nextjs-standalone-regular-build-docker-f09630ca2b2c)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor führt fehlende Tailwind-Stile in seinem Next.js-Standalone-Build darauf zurück, dass `.next/static` nicht automatisch kopiert wird. Er empfiehlt, die Dateien nach `.next` zu kopieren – im Docker-Beispiel nach `./.next`, damit nicht versehentlich `.next/static/static` entsteht. Laut seinem Bericht behebt das den Fehler in seiner Anwendung; eine allgemeine Prüfung anderer Konfigurationen enthält der Text nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
