[English](README.md) · [Deutsch](README.de.md)

# How Claude Actually Works — A Developer’s Guide to LLMs Without the Math

Report Q010909 · Source medium.com · Date 2026-06-20 · [Open original](https://medium.com/@aitrends24/how-claude-actually-works-a-developers-guide-to-llms-without-the-math-2d663c5b71e4)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Beitrag erklärt Claude als Modell, das Eingaben in Tokens und Zahlenrepräsentationen umwandelt, Zusammenhänge per Aufmerksamkeit gewichtet und Antworten schrittweise Token für Token erzeugt. Der Autor leitet daraus Empfehlungen für knappe, klare Prompts ab und betont zugleich, dass der Rechenaufwand langer Kontexte sowie der Übergang zu scheinbarem Schlussfolgern nur teilweise erklärt sind; eigene Tests berichtet der Beitrag nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 39 / 82 % | 1 / 15 % | 96 / 99 % | 12 / 38 % | 7 / 24 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 23 / 91 % | 0 / 7 % | 92 / 98 % | 7 / 26 % | 3 / 15 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 55 / 96 % | 0 / 4 % | 28 / 77 % | 5 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 8 / 58 % | 0 / 0 % | 0 / 0 % | 6 / 25 % | 5 / 16 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 1 / 32 % | 0 / 0 % | 0 / 10 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 3 / 58 % | 0 / 2 % | 0 / 0 % | 5 / 13 % | 4 / 7 % | 0 / 2 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 1 / 52 % | 0 / 0 % | 0 / 0 % | 5 / 19 % | 4 / 9 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 6 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 56 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
