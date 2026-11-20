[English](README.md) · [Deutsch](README.de.md)

# Stop Building AI Agents Like Monoliths: 5 Architecture Tips Every Developer Should Know

Report Q011227 · Source medium.com · Date 2026-08-09 · [Open original](https://medium.com/coding-nexus/stop-building-ai-agents-like-monoliths-5-architecture-tips-every-developer-should-know-6a2515517232)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht empfiehlt spezialisierte Agenten, eine vom Modellanbieter unabhängige Schnittstelle, multimodale Fähigkeiten und offene Protokolle wie MCP. Außerdem solle ein Sprachmodell Aktionen vorschlagen, während geprüfter Code sie nach Validierung und Berechtigungsprüfung ausführt; die Vorteile werden anhand einfacher Beispiele erläutert, aber nicht durch Messungen belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 27 / 49 % | 94 / 99 % | 42 / 73 % | 99 / 100 % | 37 / 65 % | 20 / 45 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 48 % | 80 / 98 % | 11 / 32 % | 98 / 99 % | 34 / 63 % | 24 / 49 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 36 / 93 % | 0 / 0 % | 65 / 84 % | 5 / 11 % | 4 / 12 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 43 / 72 % | 0 / 0 % | 61 / 75 % | 5 / 11 % | 3 / 9 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 14 / 36 % | 0 / 0 % | 59 / 77 % | 5 / 11 % | 5 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 15 / 40 % | 32 / 80 % | 1 / 6 % | 11 / 41 % | 12 / 34 % | 13 / 36 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 28 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 28 % | 22 / 92 % | 0 / 5 % | 26 / 52 % | 8 / 28 % | 4 / 15 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 21 / 75 % | 0 / 0 % | 6 / 31 % | 5 / 13 % | 3 / 9 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 16 / 35 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 11 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 6 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 9 / 57 % | 0 / 0 % | 0 / 0 % | 4 / 8 % | 2 / 4 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 8 / 32 % | 6 / 33 % | 0 / 1 % | 0 / 4 % | 5 / 11 % | 5 / 9 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 1 / 36 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 5 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 6 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 6 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 4 / 8 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 6 / 35 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 5 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 7 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 5 / 35 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 13 % |
