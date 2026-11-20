[English](README.md) · [Deutsch](README.de.md)

# QuestBench: Can LLMs ask the right question to acquire information in reasoning tasks?

Report Q005372 · Source deepmind.google · Date 2025-03-28 · [Open original](https://deepmind.google/research/publications/121987/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Bericht ist nur ein Abstract zu QuestBench, einem Benchmark dafür, ob Sprachmodelle bei unvollständigen Denkaufgaben die richtige Rückfrage auswählen. Laut Verfassenden schneiden aktuelle Modelle bei Matheaufgaben gut, bei Logik und Planung mit 40 bis 50 Prozent Genauigkeit deutlich schwächer ab; das Abstract enthält keine ausführlichen Angaben zu Stichprobe oder Versuchsaufbau.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 10 / 60 % | 0 / 0 % | 78 / 89 % | 6 / 19 % | 0 / 0 % | 5 / 13 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 52 / 69 % | 6 / 19 % | 0 / 0 % | 6 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 26 / 45 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 27 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 0 / 0 % | 5 / 11 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 5 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
