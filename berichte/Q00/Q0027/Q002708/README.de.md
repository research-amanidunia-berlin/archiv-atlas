[English](README.md) · [Deutsch](README.de.md)

# Decoupled DiLoCo: Resilient, Distributed AI Training at Scale

Bericht Q002708 · Quelle deepmind.google · Datum 2026-04-23 · [Original öffnen](https://deepmind.google/blog/decoupled-diloco/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google DeepMind und Google Research stellen Decoupled DiLoCo als Ansatz vor, der Modelltraining über getrennte Rechenzentren mit weniger Synchronisation und größerer Ausfalltoleranz ermöglichen soll. Der Beitrag berichtet von geringerem Bandbreitenbedarf, höherem Goodput in Ausfalltests und vergleichbarer Benchmark-Leistung; ein Teil der Vergleiche beruht auf Simulationen, und die Ergebnisse werden vom Team selbst dargestellt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 42 / 75 % | 82 / 87 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 39 / 89 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 30 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 23 / 66 % | 36 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 19 / 92 % | 32 / 56 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 23 / 72 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 5 / 10 % | 0 / 5 % | 7 / 21 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 17 / 62 % | 21 / 39 % | 8 / 21 % | 0 / 0 % | 5 / 14 % | 1 / 10 % | 22 / 42 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 15 / 70 % | 20 / 35 % | 11 / 35 % | 0 / 0 % | 0 / 0 % | 1 / 10 % | 11 / 27 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 27 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 9 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
