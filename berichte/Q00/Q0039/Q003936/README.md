[English](README.md) · [Deutsch](README.de.md)

# Teaching AI to See the World More Like Humans Do

Report Q003936 · Source deepmind.google · Date 2025-11-11 · [Open original](https://deepmind.google/blog/teaching-ai-to-see-the-world-more-like-we-do/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt AligNet vor: Ein Lehrermodell erweitert wenige menschliche Ähnlichkeitsurteile aus dem THINGS-Datensatz zu Millionen Beispielen, mit denen weitere Vision-Modelle trainiert werden. Laut den Autoren stimmen diese danach häufiger mit Menschen überein und schneiden auch bei Aufgaben mit wenigen Beispielen sowie veränderten Bildverteilungen besser ab; weitere Ausrichtungsarbeit bleibt nötig.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 19 / 60 % | 85 / 94 % | 8 / 24 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 22 / 39 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 9 / 39 % | 82 / 87 % | 16 / 35 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 38 / 90 % | 73 / 88 % | 13 / 36 % | 3 / 15 % | 9 / 28 % | 1 / 8 % | 27 / 48 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 21 / 48 % | 62 / 76 % | 8 / 25 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 55 / 92 % | 40 / 55 % | 16 / 41 % | 0 / 0 % | 11 / 26 % | 4 / 13 % | 30 / 50 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 51 / 83 % | 25 / 41 % | 12 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 40 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 22 / 58 % | 0 / 0 % | 21 / 46 % | 0 / 0 % | 15 / 36 % | 2 / 12 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 4 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 68 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 2 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
