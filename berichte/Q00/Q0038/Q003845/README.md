[English](README.md) · [Deutsch](README.de.md)

# 6840c6a

Report Q003845 · Source partnershiponai.org · Date 2021-07-30 · [Open original](https://partnershiponai.org/paper_page/6840c6a/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht erklärt, dass Modelle trotz korrekter Daten und ohne direkte Verwendung geschützter Merkmale verzerrt sein können, etwa durch ausgelassene Faktoren oder Stellvertretervariablen. Er vergleicht Ansätze wie gleiche Falsch-Positiv-Raten, gruppenübergreifende Kalibrierung und kausale Modellierung, betont aber Zielkonflikte und Werturteile; eine abschließende Lösung oder eigene vergleichende Prüfung liefert die Passage nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 96 / 99 % | – | 99 / 100 % | 31 / 54 % | 23 / 41 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 14 / 69 % | – | 86 / 95 % | 11 / 29 % | 6 / 13 % | 2 / 8 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 52 / 81 % | – | 70 / 87 % | 8 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 66 / 93 % | – | 68 / 81 % | 21 / 44 % | 7 / 18 % | 3 / 11 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 58 / 80 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 49 / 98 % | – | 41 / 86 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 17 / 51 % | – | 47 / 70 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 38 / 79 % | – | 13 / 59 % | 18 / 39 % | 7 / 13 % | 3 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 31 / 96 % | – | 0 / 0 % | 8 / 18 % | 7 / 14 % | 2 / 8 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 16 / 93 % | – | 24 / 60 % | 8 / 19 % | 0 / 0 % | 1 / 5 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 18 / 51 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 15 / 87 % | – | 0 / 0 % | 7 / 16 % | 4 / 9 % | 1 / 5 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 14 / 50 % | – | 0 / 0 % | 7 / 14 % | 6 / 16 % | 1 / 5 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 11 / 53 % | – | 0 / 0 % | 10 / 32 % | 7 / 19 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 5 / 10 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 1 / 43 % | – | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 62 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % |
