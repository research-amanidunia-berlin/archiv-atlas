[English](README.md) · [Deutsch](README.de.md)

# Introducing Triton: Open-source GPU programming for neural networks

Bericht Q007825 · Quelle openai.com · Datum 2021-07-28 · [Original öffnen](https://openai.com/index/triton/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI stellt Triton 1.0 als Python-ähnliche Sprache vor, die GPU-Kernel vereinfachen und viele Optimierungen innerhalb eines SM automatisieren soll; Arbeitsteilung zwischen SMs bleibt teilweise manuell. Der Bericht nennt schnelle Softmax- und Matrixmultiplikationskernel als Beispiele, doch die Leistungswerte sind OpenAIs Angaben und werden im Text nicht durch vollständige Messdaten belegt; unterstützt werden nur neuere NVIDIA-GPUs.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 10 / 61 % | – | 48 / 61 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 18 / 61 % | – | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
