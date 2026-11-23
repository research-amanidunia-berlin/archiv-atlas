[English](README.md) · [Deutsch](README.de.md)

# AlphaDev discovers faster sorting algorithms

Report Q002438 · Source deepmind.google · Date 2023-06-07 · [Open original](https://deepmind.google/blog/alphadev-discovers-faster-sorting-algorithms/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

DeepMind berichtet, dass AlphaDev durch bestärkendes Lernen schnellere Sortier- und Hashing-Algorithmen entdeckt habe, darunter Verfahren, die in LLVM libc++ und Abseil aufgenommen wurden. Die Autoren nennen deutliche Geschwindigkeitsgewinne, weisen aber darauf hin, dass die Optimierung auf Assemblerebene bei größeren Algorithmen an Grenzen stößt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 22 / 73 % | 91 / 94 % | 16 / 32 % | 2 / 7 % | 8 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 38 % | 83 / 91 % | 7 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 66 / 83 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 64 / 87 % | 29 / 56 % | 15 / 39 % | 0 / 0 % | 11 / 25 % | 7 / 25 % | 17 / 37 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 23 / 53 % | 46 / 61 % | 20 / 40 % | 2 / 8 % | 9 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 0 / 0 % | 41 / 59 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 38 / 48 % | 6 / 19 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 4 / 36 % | 0 / 0 % | 8 / 24 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 3 / 7 % | 0 / 0 % | 0 / 0 % |
