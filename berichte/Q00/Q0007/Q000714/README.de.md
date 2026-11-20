[English](README.md) · [Deutsch](README.de.md)

# JAKCalc: A machine-learning approach to rationalized JAK2 testing in patients with elevated hemoglobin levels

Bericht Q000714 · Quelle pmc.ncbi.nlm.nih.gov · Datum – · [Original öffnen](https://pmc.ncbi.nlm.nih.gov/articles/PMC10994541/pdf/medi-103-e37751.pdf)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Die Autoren berichten, dass JAKCalc anhand von Blutbilddaten in einer retrospektiven Kohorte von 458 Fällen JAK2-V617F-Mutationen vorhersagte; Random Forest erreichte im internen Testdatensatz durchweg 100 Prozent, Gradient Boosting ebenfalls hohe Kennzahlen. Das könnte laut Bericht unnötige Tests verringern, muss aber wegen fehlender externer Validierung, der einzelnen Krankenhauskohorte und weiterer Datenlücken noch bestätigt werden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 100 / 100 % | – | 99 / 100 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 88 / 99 % | – | 39 / 54 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | – | 79 / 92 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | – | 70 / 86 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 12 % | 0 / 0 % |
