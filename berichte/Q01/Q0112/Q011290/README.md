[English](README.md) · [Deutsch](README.de.md)

# The Best Local LLM Setup on a Single RTX 3090

Report Q011290 · Source medium.com · Date 2026-03-07 · [Open original](https://medium.com/coding-nexus/the-best-local-llm-setup-on-a-single-rtx-3090-aa8aa07f73e4)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor empfiehlt für eine einzelne RTX 3090 Qwen 3.5 27B Dense in Q4_K_M mit Flash Attention und berichtet dabei von etwa 35 Tokens/s bis zu sehr langen Kontexten. Für ein 3090/3060-System schreibt er den gemessenen Leistungsabfall teilweise fehlender Flash Attention zu, weist aber auf die Bandbreitenbegrenzung der schwächeren Karte hin. Die Ergebnisse beruhen auf begrenzten eigenen Tests und einem Bekannten-Setup; AMD wurde noch nicht benchmarked.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 51 / 77 % | 96 / 97 % | 7 / 20 % | 0 / 0 % | 3 / 7 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 19 / 30 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 3 / 5 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
