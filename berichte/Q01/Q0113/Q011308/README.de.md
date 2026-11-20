[English](README.md) · [Deutsch](README.de.md)

# AirLLM: Run a 70B Model on a 4GB GPU

Bericht Q011308 · Quelle medium.com · Datum 2026-01-24 · [Original öffnen](https://medium.com/coding-nexus/airllm-run-a-70b-model-on-a-4gb-gpu-9798cbeca5b5)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel erklärt AirLLM als Verfahren, das große Modelle schichtweise statt vollständig im GPU-Speicher verarbeitet, und behauptet, dadurch könne ein 70B-Modell auf einer 4-GB-GPU laufen. Er beschreibt außerdem optionale Gewichtskomprimierung mit bis zu dreifacher Inferenzgeschwindigkeit sowie lokale Beispiele, weist aber keine Benchmarks oder konkreten Messdaten als Beleg aus.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 53 / 98 % | 16 / 50 % | 98 / 99 % | 22 / 45 % | 6 / 19 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 48 / 88 % | 1 / 8 % | 91 / 96 % | 9 / 22 % | 5 / 12 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 17 / 44 % | 0 / 0 % | 81 / 92 % | 6 / 17 % | 2 / 9 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 40 % | 5 / 10 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 15 / 62 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 3 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 13 / 62 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 1 / 13 % | 0 / 0 % | 11 / 20 % | 5 / 11 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 2 / 43 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 4 / 10 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
