[English](README.md) · [Deutsch](README.de.md)

# Real-Time Object Detection on GPUs in 10 Minutes

Bericht Q011118 · Quelle medium.com · Datum 2019-06-19 · [Original öffnen](https://medium.com/better-programming/real-time-object-detection-on-gpus-in-10-minutes-6e8c9b857bb3)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag führt anhand einer Webcam vor, wie ein SSD-Modell mit TensorRT auf einer NVIDIA-GPU für Objekterkennung optimiert und ausgeführt wird. NVIDIA beschreibt FP16 und INT8 als mögliche Beschleunigungen; für INT8 sei eine Kalibrierung nötig, konkrete allgemeingültige Laufzeitmessungen liefert der Text jedoch nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 28 / 60 % | 0 / 0 % | 85 / 92 % | 6 / 14 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 72 / 93 % | 0 / 0 % | 76 / 85 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
