[English](README.md) · [Deutsch](README.de.md)

# BYOL-Explore: Exploration with Bootstrapped Prediction

Report Q002316 · Source deepmind.google · Date 2022-06-20 · [Open original](https://deepmind.google/blog/byol-explore-exploration-with-bootstrapped-prediction/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

BYOL-Explore nutzt den Fehler bei der Vorhersage künftiger Weltrepräsentationen als internes Belohnungssignal, um Exploration zu trainieren. Der Beitrag berichtet bessere Ergebnisse als RND, ICM und reines RL auf DM-HARD-8 sowie übermenschliche Leistung in zehn schwierigen Atari-Spielen; detaillierte Versuchsangaben und Unsicherheitsmaße fehlen in der vorliegenden Darstellung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 45 / 84 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 13 / 45 % | 0 / 0 % | 37 / 58 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 35 / 57 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % |
