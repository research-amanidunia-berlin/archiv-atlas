[English](README.md) · [Deutsch](README.de.md)

# How OpenAI delivers low-latency voice AI at scale

Report Q008406 · Source openai.com · Date 2026-05-04 · [Open original](https://openai.com/index/delivering-low-latency-voice-ai-at-scale/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt eine WebRTC-Architektur, in der ein schlanker Relay-Dienst Medienpakete an den zuständigen Transceiver weiterleitet, der die Sitzung und ihre Protokollzustände verwaltet. Das Unternehmen sagt, der Ansatz verkleinere die öffentliche UDP-Fläche und erleichtere den Kubernetes-Betrieb; konkrete Latenz- oder Vergleichsmesswerte nennt der Bericht nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 50 / 91 % | 42 / 61 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 40 / 82 % | 32 / 54 % | 7 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 26 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 26 / 57 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 23 / 79 % | 2 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
