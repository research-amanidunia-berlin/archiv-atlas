[English](README.md) · [Deutsch](README.de.md)

# Bedrock AgentCore with Strands Agent Built-in Tools

Report Q010218 · Source medium.com · Date 2025-08-08 · [Open original](https://medium.com/gitconnected/bedrock-agentcore-with-strands-agent-built-in-tools-946d7403ee42)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht zeigt die Einrichtung der Strands-Tools für AgentCore Browser, Code Interpreter und Memory und gibt Empfehlungen, wann direkter AgentCore-Zugriff nötig sein könne. Strands eigne sich laut Autor besonders für flexible agentengesteuerte Aufgaben; Direktzugriff sei hilfreich bei fehlenden Aktionen, Parametern oder strukturierten Rohdaten. Der Beitrag enthält Codebeispiele und API-Verweise, aber keine systematischen Vergleichstests.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 27 / 49 % | 86 / 97 % | 3 / 17 % | 72 / 88 % | 28 / 50 % | 10 / 24 % | 1 / 9 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 33 / 49 % | 10 / 25 % | 6 / 16 % | 1 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 25 % | 6 / 16 % | 1 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 6 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 4 / 8 % | 0 / 0 % |
