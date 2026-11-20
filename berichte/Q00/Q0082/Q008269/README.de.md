[English](README.md) · [Deutsch](README.de.md)

# Efficient training of language models to fill in the middle

Bericht Q008269 · Quelle openai.com · Datum 2022-07-28 · [Original öffnen](https://openai.com/index/efficient-training-of-language-models-to-fill-in-the-middle/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug stellt FIM vor: Trainingsdaten werden so umgeordnet, dass ein Abschnitt aus der Dokumentmitte ans Ende gelangt und das Modell das Einfügen fehlenden Textes lernt. Die Autoren behaupten, dies beeinträchtige die gewöhnliche Textgenerierung nicht, doch der Auszug enthält keine Messwerte oder ausführlichen Versuchsergebnisse zur unabhängigen Prüfung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 29 / 66 % | – | 58 / 72 % | 5 / 14 % | 4 / 10 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 40 / 58 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | – | 38 / 49 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | – | 22 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 14 / 35 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
