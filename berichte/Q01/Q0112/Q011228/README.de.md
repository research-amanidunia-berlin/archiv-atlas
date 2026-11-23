[English](README.md) · [Deutsch](README.de.md)

# Everyone Is Buying Bigger AI Computers. Engineers Are Building Swarms of $8 Chips Instead.

Bericht Q011228 · Quelle medium.com · Datum 2026-08-08 · [Original öffnen](https://medium.com/coding-nexus/everyone-is-buying-bigger-ai-computers-engineers-are-building-swarms-of-8-chips-instead-ec3c4943478b)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht schlägt vor, lokale KI auf mehrere günstige Geräte mit jeweils einer Aufgabe zu verteilen, statt alles auf einem leistungsstarken Rechner auszuführen. Er enthält Beispiele für ESP32-S3, strukturierte JSON-Befehle, Needle und Home Assistant; die behaupteten Vorteile bei Kosten, Energieverbrauch und Skalierung werden allerdings nicht mit Vergleichstests belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 55 / 93 % | 95 / 98 % | 11 / 31 % | 2 / 13 % | 6 / 16 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 13 / 85 % | 89 / 95 % | 6 / 15 % | 1 / 9 % | 3 / 10 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 56 / 83 % | 67 / 83 % | 14 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 43 / 66 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 34 / 69 % | 41 / 64 % | 7 / 18 % | 1 / 6 % | 3 / 9 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 31 / 76 % | 21 / 37 % | 6 / 17 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 18 / 92 % | 14 / 39 % | 7 / 28 % | 3 / 15 % | 4 / 13 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 11 / 64 % | 0 / 0 % | 7 / 20 % | 2 / 11 % | 4 / 11 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 1 / 13 % | 0 / 0 % | 5 / 11 % | 0 / 3 % | 2 / 4 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
