[English](README.md) · [Deutsch](README.de.md)

# I kept building LLM apps that worked in demos and broke in production.

Report Q011080 · Source medium.com · Date 2026-06-09 · [Open original](https://medium.com/ai-advances/i-kept-building-llm-apps-that-worked-in-demos-and-broke-in-production-9cff6f27e3df)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor argumentiert anhand eines fehlerhaften Support-Chatbots, dass die Qualität von LLM-Anwendungen stark davon abhängt, welche Informationen tatsächlich im Kontext landen. Er empfiehlt gepflegte Wissensquellen, gezielte Suche und Filterung, passende Gesprächszusammenfassungen sowie Protokolle und Tests mit bekannten Antworten. Die Empfehlungen beruhen überwiegend auf seiner Praxiserfahrung; die angeführte Studie wird im Beitrag nur knapp beschrieben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 54 / 92 % | 0 / 0 % | 96 / 98 % | 23 / 49 % | 2 / 12 % | 8 / 23 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 89 / 98 % | 0 / 0 % | 79 / 88 % | 8 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 49 / 69 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 66 % | 0 / 0 % | 47 / 67 % | 5 / 12 % | 0 / 0 % | 4 / 10 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 41 / 81 % | 0 / 0 % | 13 / 36 % | 9 / 23 % | 1 / 7 % | 4 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 38 / 76 % | 0 / 0 % | 27 / 55 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 36 / 77 % | 0 / 0 % | 37 / 75 % | 0 / 0 % | 0 / 0 % | 6 / 13 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 32 / 86 % | 0 / 0 % | 0 / 0 % | 7 / 25 % | 0 / 0 % | 6 / 15 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 24 / 45 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 8 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 2 / 5 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 0 / 0 % | 7 / 17 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 1 / 43 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 0 / 0 % | 4 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 64 % | 0 / 0 % | 2 / 9 % | 7 / 18 % | 2 / 8 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 3 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 3 / 9 % |
