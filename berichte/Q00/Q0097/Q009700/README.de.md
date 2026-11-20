[English](README.md) · [Deutsch](README.de.md)

# How Apple Container + builder-shim build our Docker Image

Bericht Q009700 · Quelle medium.com · Datum 2026-07-26 · [Original öffnen](https://medium.com/@itsuki.enjoy/how-apple-container-builder-shim-build-our-docker-image-d67db50f908e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht erläutert anhand der Code-Nachverfolgung des Autors, wie Apples Container-Befehl über `container-builder-shim` mit BuildKit kommuniziert und lokale Dateien, Images sowie Build-Ausgaben vermittelt. Für OCI-Layout-Build-Kontexte schlägt der Autor vor, das Image direkt anzufordern, in einem OCI-Store abzulegen und als benannte Eingabe weiterzugeben; er sagt, diese Unterstützung in seinem Fork ergänzt zu haben, betont aber, dass der beschriebene Hauptzweig sie noch nicht enthält und er keine Garantie für seine Implementierung gibt. Der Bericht ist vollständig.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 36 / 65 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
