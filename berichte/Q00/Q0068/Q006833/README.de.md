[English](README.md) · [Deutsch](README.de.md)

# DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition

Bericht Q006833 · Quelle arxiv.org · Datum – · [Original öffnen](https://arxiv.org/pdf/2504.21801)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

DeepSeek-Prover-V2 verbindet natürlichsprachliche Beweisskizzen von DeepSeek-V3 mit rekursiver Lösung formaler Lean-4-Teilziele und anschließendem Training mit überwachten Daten und bestärkendem Lernen. Die Autoren berichten starke Benchmarkwerte, weisen aber auch auf korrigierte Resultate, fehlerhafte Aufgaben und einen Lean-Benutzeroberflächenfehler hin; die Zahlen hängen von Testaufbau und Stichprobenbudget ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 98 / 100 % | – | 28 / 50 % | 0 / 0 % | 11 / 24 % | – | 17 / 34 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 92 / 98 % | – | 36 / 59 % | 0 / 0 % | 11 / 24 % | – | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 45 / 67 % | – | 22 / 44 % | 0 / 0 % | 8 / 19 % | – | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | – | 14 / 33 % | 0 / 0 % | 9 / 21 % | – | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 13 / 31 % | 0 / 0 % | 9 / 18 % | – | 12 / 27 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | – | 12 / 27 % | 0 / 0 % | 9 / 17 % | – | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 0 / 0 % | 10 / 18 % | – | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 10 / 34 % | – | 8 / 19 % | 0 / 0 % | 5 / 12 % | – | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | – | 9 / 23 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | – | 9 / 17 % | 0 / 0 % | 5 / 11 % | – | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 7 / 15 % | – | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % |
