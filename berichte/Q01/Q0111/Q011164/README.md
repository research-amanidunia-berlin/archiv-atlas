[English](README.md) · [Deutsch](README.de.md)

# Strands Decider: A small, fast decision model for agentic AI.

Report Q011164 · Source medium.com · Date 2026-11-11 · [Open original](https://medium.com/coding-nexus/strands-decider-a-small-fast-decision-model-for-agentic-ai-e59db7ef4e1f)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht stellt Strands Decider als Modell für Auswahl-, Ja/Nein- und Bewertungsentscheidungen in KI-Agenten vor, einschließlich Kommandozeilen-, API- und begrenzter Bildnutzung. Der Autor berichtet unter anderem von hoher Trefferquote bei Konfidenzwerten ab 0,9, betont aber, dass Schwellenwerte am eigenen Einsatz kalibriert werden müssen; unabhängige Prüfungen werden nicht dargestellt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 80 / 98 % | 100 / 100 % | 15 / 37 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 82 / 98 % | 93 / 96 % | 10 / 26 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 17 / 33 % | 49 / 83 % | 88 / 94 % | 18 / 41 % | 2 / 10 % | 14 / 34 % | 2 / 10 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 47 / 80 % | 74 / 88 % | 15 / 35 % | 2 / 10 % | 10 / 26 % | 4 / 21 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 65 / 82 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 7 / 71 % | 50 / 68 % | 7 / 17 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 17 / 61 % | 44 / 60 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 41 / 57 % | 6 / 15 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 34 / 42 % | 8 / 22 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 24 / 56 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 19 / 77 % | 0 / 0 % | 8 / 23 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 8 / 24 % | 12 / 27 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 11 / 22 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 2 / 9 % | 5 / 15 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 2 / 9 % | 0 / 2 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 5 / 8 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 3 / 5 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
