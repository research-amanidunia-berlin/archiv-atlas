[English](README.md) · [Deutsch](README.de.md)

# Swift/FoundationModels: Give LanguageModels Some Long-Term Memories. On-Device.

Bericht Q009612 · Quelle medium.com · Datum 2026-10-22 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-foundationmodels-give-languagemodels-some-long-term-memories-on-device-4f8f47059178)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht beschreibt zwei experimentelle lokale Speicherverfahren für FoundationModels: semantische Suche mit NaturalLanguage-Einbettungen und Volltextsuche mit SQLite FTS5. Die eigenen Tests des Autors zeigen erhebliche Grenzen bei Ähnlichkeit und Werkzeugwahl; mehr Anweisungen halfen nicht, während ein Hinweis zur proaktiven Suche etwas nützlich erschien.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 45 / 76 % | 69 / 79 % | 9 / 21 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 68 / 96 % | 60 / 73 % | 11 / 25 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 3 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
