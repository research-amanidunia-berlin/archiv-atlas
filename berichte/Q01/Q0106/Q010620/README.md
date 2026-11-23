[English](README.md) · [Deutsch](README.de.md)

# AWS Bedrock Converse API with Rust: Tool Use

Report Q010620 · Source medium.com · Date 2024-08-11 · [Open original](https://medium.com/gitconnected/aws-bedrock-converse-api-with-rust-tool-use-8d1af829480a)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht zeigt den Rust-Ablauf für Werkzeugaufrufe mit der nicht gestreamten AWS-Bedrock-Converse-API: Schema definieren, Modellantwort auf Werkzeugaufrufe prüfen, Ergebnis zurücksenden. Das Beispiel `CREATE_FILE` legt jedoch keine Datei an, sondern gibt Eingaben aus und meldet Erfolg; zudem stimmen Modell-ID und Modellname im Prompt nicht überein.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 20 / 43 % | 69 / 93 % | 91 / 97 % | 19 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 19 / 38 % | 17 / 66 % | 56 / 75 % | 10 / 25 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 16 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 6 / 25 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 4 / 22 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 4 / 7 % | 0 / 0 % | – |
