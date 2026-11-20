[English](README.md) · [Deutsch](README.de.md)

# Decoupled Neural Interfaces Using Synthetic Gradients

Bericht Q001898 · Quelle deepmind.google · Datum 2016-08-29 · [Original öffnen](https://deepmind.google/blog/decoupled-neural-interfaces-using-synthetic-gradients/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt DNI als Methode, die neuronale Netzmodule mithilfe lokal geschätzter synthetischer Gradienten früher und unabhängig voneinander aktualisieren soll. Die angeführten Versuche berichten gleiche CIFAR-10-Genauigkeit wie mit Rückwärtspropagation und bei einer Sprachmodellaufgabe ähnliche Leistung mit weniger Trainingsschritten und etwa doppelter Geschwindigkeit. Echte Gradienten bleiben erforderlich; sie wirken laut Beitrag lediglich verzögert, und die dargestellten Ergebnisse belegen keine allgemeine Überlegenheit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 9 / 47 % | 0 / 0 % | 33 / 57 % | 0 / 0 % | 0 / 0 % | 4 / 12 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 22 / 73 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 3 / 9 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 11 / 75 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 0 % | 1 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 4 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
