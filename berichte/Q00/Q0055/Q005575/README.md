[English](README.md) · [Deutsch](README.de.md)

# How Well Do Large Language Models Perform Latent Multi-Hop Reasoning without Exploiting Shortcuts?

Report Q005575 · Source deepmind.google · Date 2024-11-26 · [Open original](https://deepmind.google/research/publications/133302/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Quelltext ist nur der Abstract einer Studie, die mit dem Datensatz SOCRATES Abkürzungen bei der Prüfung latenter Mehrschritt-Schlussfolgerungen von Sprachmodellen eindämmen soll. Laut Abstract liegen die Ergebnisse je nach Brückenentität weit auseinander: etwa fünf Prozent bei einem Jahr, über 80 Prozent bei einem Land; außerdem zeigt sich eine deutliche Lücke zum expliziten Chain-of-Thought-Schlussfolgern.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 24 / 46 % | 0 / 0 % | – | 8 / 19 % | 0 / 0 % | 5 / 12 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 28 % | 0 / 0 % | 7 / 17 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 19 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 4 / 7 % |
