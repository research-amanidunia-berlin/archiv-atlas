[English](README.md) · [Deutsch](README.de.md)

# Decoupled Neural Interfaces Using Synthetic Gradients

Report Q001898 · Source deepmind.google · Date 2016-08-29 · [Open original](https://deepmind.google/blog/decoupled-neural-interfaces-using-synthetic-gradients/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt DNI als Methode, die neuronale Netzmodule mithilfe lokal geschätzter synthetischer Gradienten früher und unabhängig voneinander aktualisieren soll. Die angeführten Versuche berichten gleiche CIFAR-10-Genauigkeit wie mit Rückwärtspropagation und bei einer Sprachmodellaufgabe ähnliche Leistung mit weniger Trainingsschritten und etwa doppelter Geschwindigkeit. Echte Gradienten bleiben erforderlich; sie wirken laut Beitrag lediglich verzögert, und die dargestellten Ergebnisse belegen keine allgemeine Überlegenheit.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 9 / 47 % | 33 / 57 % | 0 / 0 % | 0 / 0 % | 4 / 12 % | 0 / 0 % | 26 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 22 / 73 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 11 / 75 % | 0 / 0 % | 5 / 16 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 6 / 19 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
