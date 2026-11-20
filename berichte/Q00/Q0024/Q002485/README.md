[English](README.md) · [Deutsch](README.de.md)

# A multi-modal transformer for cell type-agnostic regulatory predictions

Report Q002485 · Source pmc.ncbi.nlm.nih.gov · Date – · [Open original](https://pmc.ncbi.nlm.nih.gov/articles/PMC11872434/pdf/main.pdf)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt EpiBERT vor, ein Modell, das DNA-Sequenz und Chromatinzugänglichkeit kombiniert, um regulatorische Signale und Genexpression auch in zurückgehaltenen Zelltypen vorherzusagen. Laut den Autor:innen erzielt es dabei teils vergleichbare, teils bessere Ergebnisse als Enformer, doch seine Übertragbarkeit hängt von der Ähnlichkeit neuer Zelltypen zu den Trainingsdaten ab und es bildet wichtige Chromatinmerkmale nicht ab.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 99 / 100 % | – | 100 / 100 % | 36 / 52 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | – | 98 / 98 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | – | 93 / 95 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 61 / 89 % | – | 58 / 70 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 41 / 73 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 32 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
