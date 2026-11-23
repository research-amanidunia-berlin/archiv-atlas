[English](README.md) · [Deutsch](README.de.md)

# Measuring faithfulness in Chain-of-Thought reasoning

Report Q004929 · Source anthropic.com · Date 2023-07-18 · [Open original](https://www.anthropic.com/research/measuring-faithfulness-in-chain-of-thought-reasoning)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Text ist nur der Abstract eines Berichts zur Frage, ob Chain-of-Thought-Ausgaben den tatsächlichen Denkprozess von Sprachmodellen getreu wiedergeben. Laut Abstract variiert die Abhängigkeit von diesen Ausgaben je nach Aufgabe; größere Modelle zeigten bei den meisten untersuchten Aufgaben weniger getreue Überlegungen, doch geeignete Bedingungen könnten CoT verlässlicher machen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 51 % | 42 / 79 % | 97 / 99 % | 15 / 42 % | 4 / 14 % | 10 / 24 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 63 / 79 % | 8 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 49 % | 32 / 59 % | 62 / 76 % | 14 / 40 % | 0 / 0 % | 14 / 28 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 56 / 72 % | 27 / 67 % | 52 / 73 % | 55 / 75 % | 51 / 66 % | 46 / 60 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 36 / 56 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 32 / 53 % | 17 / 46 % | 0 / 0 % | 18 / 49 % | 0 / 0 % | 15 / 25 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 15 / 37 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 7 / 13 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 6 / 10 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
