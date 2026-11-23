[English](README.md) · [Deutsch](README.de.md)

# AWS: Create Feature Flag with AppConfig (Console)

Report Q010782 · Source medium.com · Date 2024-02-03 · [Open original](https://medium.com/aws-tip/aws-create-feature-flag-with-appconfig-console-889614c3645c)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht führt durch das Anlegen einer AppConfig-Anwendung, einer Produktionsumgebung und eines Feature-Flags, das über ein Attribut bestimmte Anwendungsinstanzen freischaltet. Eine IAM-Rolle für CloudWatch-Alarme ist laut Autor nur für automatisches Zurückrollen nötig; der Abruf der bereitgestellten Konfiguration wird lediglich angerissen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 79 / 98 % | 6 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 62 / 96 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 37 / 72 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
