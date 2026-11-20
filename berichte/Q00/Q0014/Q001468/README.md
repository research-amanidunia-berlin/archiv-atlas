[English](README.md) · [Deutsch](README.de.md)

# Quantifying the Salience of Geo-Cultural Values for Pluralistic Safety Alignment

Report Q001468 · Source deepmind.google · Date 2026-07-10 · [Open original](https://deepmind.google/research/publications/225819/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Bericht ist nur ein Abstract-Auszug. Laut Abstract zeigen Analysen von sechs Datensätzen, dass Kulturzonen Sicherheitsbewertungen zusätzlich zu demografischen Merkmalen beeinflussen können; etwa zehn Prozent der untersuchten Elemente seien kulturell sensibel. Sprachmodelle seien kein zuverlässiger Ersatz für menschliche Bewertende, könnten aber bei der Vorauswahl solcher Elemente helfen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 51 % | 55 / 93 % | 10 / 44 % | 82 / 92 % | 32 / 59 % | 9 / 26 % | 33 / 54 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 48 % | 48 / 81 % | 5 / 29 % | 80 / 91 % | 17 / 45 % | 9 / 26 % | 18 / 36 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 47 / 80 % | 10 / 41 % | 72 / 91 % | 32 / 59 % | 5 / 18 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 7 % | 72 / 89 % | 9 / 31 % | 1 / 7 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 22 / 68 % | 0 / 3 % | 70 / 82 % | 10 / 23 % | 5 / 12 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 39 / 82 % | 18 / 52 % | 60 / 78 % | 52 / 73 % | 26 / 47 % | 47 / 63 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 34 / 78 % | 2 / 11 % | 57 / 82 % | 8 / 19 % | 4 / 13 % | 7 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 30 / 52 % | 6 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 27 / 69 % | 2 / 13 % | 22 / 54 % | 16 / 46 % | 13 / 31 % | 21 / 38 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 23 / 65 % | 0 / 0 % | 18 / 55 % | 14 / 35 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 17 / 54 % | 0 / 0 % | 12 / 37 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 14 / 34 % | 13 / 34 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 13 / 42 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 26 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 4 / 27 % | 9 / 27 % | 0 / 0 % | 6 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 6 / 18 % | 0 / 0 % | 8 / 14 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 0 / 0 % | 0 / 0 % |
