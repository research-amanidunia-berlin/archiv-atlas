[English](README.md) · [Deutsch](README.de.md)

# Bedrock AgentCore Part 6: Identity. More Than a Secure Key Storage!

Report Q010198 · Source medium.com · Date 2025-08-18 · [Open original](https://medium.com/@itsuki.enjoy/bedrock-agentcore-part-6-identity-more-than-a-secure-key-storage-88412e45d036)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht stellt AgentCore Identity für die Verwaltung von API-Schlüsseln, Workload-Identitäten und OAuth-Abläufen vor und zeigt beispielhaft die Nutzung über SDK-Decorators. Der Autor weist auf Regionsprobleme und eine seiner Ansicht nach fragwürdige automatische Nutzer-ID hin; seine Darstellung ist ein Praxisbericht, keine unabhängige Prüfung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 34 / 55 % | 97 / 100 % | 19 / 48 % | 70 / 87 % | 36 / 57 % | 28 / 48 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 11 / 34 % | 3 / 31 % | 0 / 0 % | 39 / 64 % | 8 / 22 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 22 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 30 % | 11 / 26 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 81 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
