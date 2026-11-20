[English](README.md) · [Deutsch](README.de.md)

# RIP OpenClaw: Building a Secure AI Agent with Claude Opus 4.6 and n8n

Report Q011296 · Source medium.com · Date 2026-02-11 · [Open original](https://medium.com/coding-nexus/rip-openclaw-building-a-secure-ai-agent-with-claude-opus-4-6-and-n8n-8836d84e1a22)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht schlägt einen KI-Assistenten mit Claude, n8n und einem in Docker begrenzten Dateizugriff vor und beschreibt Integrationen, Speicher, Unteragenten, Automatisierung und Sicherheitsmaßnahmen. Die behaupteten Schutzgrenzen und Funktionen werden nicht durch unabhängige Tests belegt; außerdem passt die im Beispiel genannte Modellkennung nicht zur Bezeichnung Claude Opus 4.6.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 74 / 86 % | 99 / 100 % | 88 / 95 % | 100 / 100 % | 83 / 91 % | 74 / 87 % | 76 / 84 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 43 / 58 % | 59 / 92 % | 26 / 51 % | 99 / 100 % | 59 / 78 % | 39 / 62 % | 57 / 72 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 21 / 35 % | 76 / 92 % | 1 / 5 % | 99 / 100 % | 16 / 33 % | 5 / 10 % | 12 / 23 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 43 / 62 % | 76 / 95 % | 16 / 38 % | 81 / 89 % | 56 / 75 % | 51 / 74 % | 67 / 80 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 12 / 74 % | 0 / 0 % | 72 / 83 % | 5 / 10 % | 1 / 4 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 11 / 31 % | 20 / 88 % | 2 / 10 % | 61 / 76 % | 22 / 47 % | 11 / 29 % | 15 / 31 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 48 / 86 % | 1 / 6 % | 57 / 75 % | 12 / 35 % | 2 / 9 % | 11 / 25 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 45 % | 7 / 16 % | 1 / 3 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 25 / 74 % | 0 / 0 % | 21 / 46 % | 9 / 19 % | 4 / 9 % | 5 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 30 % | 22 / 51 % | 0 / 0 % | 6 / 15 % | 9 / 20 % | 1 / 3 % | 5 / 9 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 22 / 58 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 2 / 5 % | 12 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 7 / 19 % | 0 / 0 % | 0 / 0 % | 2 / 14 % | 9 / 20 % | 2 / 6 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 6 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 8 / 19 % | 1 / 4 % | 8 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 2 / 4 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 6 % | 6 / 12 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | 5 / 9 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 10 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 2 % | 0 / 0 % |
