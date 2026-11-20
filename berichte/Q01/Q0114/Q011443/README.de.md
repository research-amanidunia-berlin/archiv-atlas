[English](README.md) · [Deutsch](README.de.md)

# How to Run Local AI Models on iOS & macOS devices with Swift

Bericht Q011443 · Quelle medium.com · Datum 2025-06-07 · [Original öffnen](https://medium.com/@jc_builds/how-to-run-local-ai-models-on-ios-macos-devices-with-kuzco-42173ba376ce)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht stellt Kuzco als Swift-Wrapper für llama.cpp vor, mit dem Apps Sprachmodelle auf Apple-Geräten lokal ausführen können sollen. Er beschreibt Funktionen und zeigt Beispielcode zur Einbindung und Vorhersage, belegt die genannten Vorteile und Leistungsangaben jedoch nicht durch Benchmarks oder Gerätetests.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 24 / 78 % | 0 / 0 % | 71 / 85 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 34 / 61 % | 0 / 0 % | 69 / 85 % | 9 / 23 % | 5 / 15 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 39 / 65 % | 0 / 0 % | 69 / 84 % | 4 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 35 / 74 % | 0 / 0 % | 11 / 30 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 12 % | 5 / 10 % | 3 / 7 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 22 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
