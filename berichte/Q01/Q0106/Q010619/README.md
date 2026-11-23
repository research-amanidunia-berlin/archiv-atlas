[English](README.md) · [Deutsch](README.de.md)

# AWS Bedrock Converse API with Rust: Tool Use + Streaming

Report Q010619 · Source medium.com · Date 2024-08-11 · [Open original](https://medium.com/gitconnected/aws-bedrock-converse-api-with-rust-tool-use-streaming-e20b7f42a5bd)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Artikel zeigt, wie Rust einen gestreamten Bedrock-Werkzeugaufruf anhand von Werkzeug-ID, Namen und stückweise eintreffender Eingabe verarbeitet, diese Eingabe in `Document` umwandelt und das Werkzeugergebnis für eine weitere Modellantwort zurücksendet. Das Beispiel führt das Werkzeug nicht tatsächlich aus, sondern verwendet ein fest codiertes Ergebnis und vereinfacht die Annahme, dass die Folgeantwort keinen weiteren Werkzeugaufruf enthält.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 47 / 79 % | 28 / 50 % | 9 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 19 / 37 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
