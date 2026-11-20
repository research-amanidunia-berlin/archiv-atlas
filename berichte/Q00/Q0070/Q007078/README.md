[English](README.md) · [Deutsch](README.de.md)

# Unlocking the Codex harness: how we built the App Server

Report Q007078 · Source openai.com · Date 2026-02-04 · [Open original](https://openai.com/index/unlocking-the-codex-harness/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt den Codex App Server als rückwärtskompatible JSON-RPC-Schnittstelle, die unterschiedliche Codex-Clients mit demselben Agenten-Harness verbindet und Gesprächsverläufe, gestreamte Ereignisse sowie Freigaben unterstützt. OpenAI empfiehlt ihn für Integrationen mit vollem Funktionsumfang, nennt aber den Aufwand eigener Client-Anbindungen; unabhängige Vergleichsmessungen enthält der Beitrag nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 38 / 57 % | 96 / 100 % | – | 95 / 99 % | 59 / 77 % | 45 / 63 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 56 / 64 % | 11 / 23 % | 8 / 17 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 40 % | 29 / 92 % | – | 47 / 70 % | 24 / 48 % | 24 / 43 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 26 / 47 % | 46 / 94 % | – | 34 / 51 % | 46 / 68 % | 46 / 64 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 88 % | – | 36 / 53 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 34 % | 34 / 68 % | – | 0 / 0 % | 8 / 22 % | 8 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 25 % | 8 / 81 % | – | 27 / 51 % | 8 / 25 % | 5 / 14 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 20 / 36 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 9 / 18 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 20 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 9 / 22 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 5 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 15 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 5 / 11 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 3 / 42 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 2 / 36 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
