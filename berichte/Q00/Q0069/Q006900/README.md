[English](README.md) · [Deutsch](README.de.md)

# How GPT-5.6 Sol helps run quantum computing experiments

Report Q006900 · Source openai.com · Date 2026-09-08 · [Open original](https://openai.com/index/codex-quantum-computing-experiments/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Laut OpenAI-Bericht konnte GPT‑5.6 Sol über Codex Routine-Kalibrierungen an einem supraleitenden Qubit-Chip weitgehend selbstständig ausführen und so den Überwachungsaufwand für Forschende senken. Bei schwachen oder verrauschten Messsignalen hatte der Agent jedoch Schwierigkeiten und brauchte mitunter menschliche Anleitung; die Deutung uneindeutiger Ergebnisse bleibt eine Herausforderung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 22 / 43 % | 64 / 88 % | – | 97 / 99 % | 53 / 73 % | 28 / 49 % | 9 / 27 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 43 / 74 % | – | 93 / 96 % | 6 / 17 % | 4 / 11 % | 1 / 5 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 82 / 91 % | 6 / 16 % | 0 / 0 % | 0 / 2 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 19 / 39 % | 42 / 85 % | – | 54 / 74 % | 14 / 39 % | 17 / 34 % | 2 / 13 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 16 / 35 % | 44 / 77 % | – | 16 / 37 % | 5 / 14 % | 7 / 19 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 33 % | 38 / 73 % | – | 0 / 0 % | 15 / 39 % | 13 / 29 % | 4 / 15 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 36 / 78 % | – | 0 / 0 % | 13 / 38 % | 10 / 22 % | 1 / 7 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 24 / 72 % | – | 29 / 70 % | 0 / 0 % | 6 / 15 % | 0 / 3 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 34 % | 0 / 0 % | – | 14 / 27 % | 17 / 38 % | 16 / 32 % | 7 / 21 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 28 % | 9 / 19 % | 1 / 6 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 22 % | 0 / 0 % | – | 8 / 24 % | 7 / 23 % | 0 / 0 % | 1 / 8 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 4 / 8 % | 0 / 3 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 1 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 4 / 8 % | 4 / 11 % | 0 / 1 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 34 % | – | 0 / 0 % | 4 / 10 % | 0 / 0 % | 1 / 6 % |
