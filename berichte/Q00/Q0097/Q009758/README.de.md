[English](README.md) · [Deutsch](README.de.md)

# iOS: SimCam is Cool? Let’s Reverse Engineer it!

Bericht Q009758 · Quelle medium.com · Datum 2026-06-06 · [Original öffnen](https://medium.com/macoclock/ios-simcam-is-cool-lets-reverse-engineer-it-18a1273b163a)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht rekonstruiert anhand von LLDB-Einträgen und Hinweisen in SimCams Bibliotheken, wie die Software vermutlich virtuelle Kameras in Simulator-Apps einbindet und Bilddaten über eine lokale Socket-Verbindung einspeist. Der Autor kritisiert, dass die Einbindung nach dem Beenden der App offenbar bestehen bleibt; die technische Erklärung ist teilweise eine aus Binärdatei-Hinweisen abgeleitete Vermutung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
