[English](README.md) · [Deutsch](README.de.md)

# Infrastructure for deep learning

Report Q008113 · Source openai.com · Date 2016-08-29 · [Open original](https://openai.com/index/infrastructure-for-deep-learning/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag schildert OpenAIs damalige Deep-Learning-Infrastruktur für schnelle Prototypen und große, verteilte Trainingsläufe. Er beschreibt eine GAN-Methode, deren ImageNet-Ergebnisse trotz guter Resultate hinter den Erwartungen blieben, sowie Kubernetes und einen veröffentlichten Autoscaler für dynamische AWS-Ressourcen; ungelöste Ursachen, nichtlineare GPU-Beschleunigung und begrenzte Cloud-Kapazität nennt der Text als Grenzen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 28 / 84 % | 82 / 94 % | 9 / 25 % | 0 / 0 % | 7 / 18 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 14 / 78 % | 68 / 79 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 56 / 95 % | 12 / 41 % | 9 / 32 % | 0 / 0 % | 8 / 20 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 54 / 87 % | 51 / 68 % | 7 / 25 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 21 / 80 % | 34 / 54 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 25 / 63 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 6 / 13 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 17 / 83 % | 11 / 31 % | 6 / 17 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 10 / 20 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 11 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 11 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 6 / 50 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 7 / 16 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 6 / 68 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | – | – |
