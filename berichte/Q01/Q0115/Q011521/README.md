[English](README.md) · [Deutsch](README.de.md)

# Build a Local AI Agent with Qwen 3.5 Small

Report Q011521 · Source medium.com · Date 2026-03-18 · [Open original](https://medium.com/@amosgyamfi/build-a-local-ai-agent-with-qwen-3-5-small-facde9de5c7b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt eine Python-Anleitung für einen sprachgesteuerten Videoanalyse-Agenten mit Qwen 3.5 Small, Ollama und Vision Agents. Zwar behauptet der Artikel, alles laufe lokal, doch sein Stack benötigt auch externe Sprachdienste und Stream; die vollständige lokale Verarbeitung und die Datenschutzversprechen werden nicht belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 45 / 88 % | 73 / 84 % | 6 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 25 / 54 % | 48 / 71 % | 11 / 31 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 42 / 70 % | 27 / 46 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 23 / 51 % | 39 / 64 % | 10 / 25 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 32 / 48 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 22 / 44 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 11 / 24 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 5 / 20 % | 8 / 22 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 3 / 7 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 3 / 5 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
