[English](README.md) · [Deutsch](README.de.md)

# How Apple Container + builder-shim build our Docker Image

Report Q009700 · Source medium.com · Date 2026-07-26 · [Open original](https://medium.com/@itsuki.enjoy/how-apple-container-builder-shim-build-our-docker-image-d67db50f908e)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht erläutert anhand der Code-Nachverfolgung des Autors, wie Apples Container-Befehl über `container-builder-shim` mit BuildKit kommuniziert und lokale Dateien, Images sowie Build-Ausgaben vermittelt. Für OCI-Layout-Build-Kontexte schlägt der Autor vor, das Image direkt anzufordern, in einem OCI-Store abzulegen und als benannte Eingabe weiterzugeben; er sagt, diese Unterstützung in seinem Fork ergänzt zu haben, betont aber, dass der beschriebene Hauptzweig sie noch nicht enthält und er keine Garantie für seine Implementierung gibt. Der Bericht ist vollständig.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 36 / 65 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
