[English](README.md) · [Deutsch](README.de.md)

# Challenges in Detoxifying Language Models

Report Q002602 · Source deepmind.google · Date 2021-09-15 · [Open original](https://deepmind.google/blog/challenges-in-detoxifying-language-models/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Eine Kombination aus Datenfilterung, Klassifikator und Generierungslenkung senkte die gemessene Toxizität deutlich; menschliche Bewertungen bestätigten insgesamt den Rückgang. Nach den Eingriffen wurden automatische Bewertungen aber weniger zuverlässig, und der erhöhte Modellverlust traf manche Dialekte und Gruppen stärker als andere.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 90 / 99 % | 99 / 100 % | 41 / 66 % | 8 / 23 % | 30 / 54 % | 9 / 33 % | 34 / 57 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 61 / 95 % | 98 / 99 % | 30 / 57 % | 10 / 25 % | 16 / 38 % | 6 / 22 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 27 / 63 % | 66 / 78 % | 37 / 64 % | 9 / 23 % | 25 / 47 % | 5 / 19 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 21 / 51 % | 65 / 79 % | 9 / 27 % | 4 / 14 % | 0 / 0 % | 5 / 19 % | 33 / 55 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 28 / 80 % | 65 / 84 % | 8 / 18 % | 1 / 7 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 62 / 95 % | 49 / 82 % | 11 / 30 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 34 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 6 / 45 % | 57 / 73 % | 21 / 50 % | 7 / 19 % | 13 / 28 % | 2 / 12 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 15 / 89 % | 20 / 41 % | 10 / 25 % | 0 / 0 % | 11 / 27 % | 2 / 7 % | 49 / 73 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 5 / 33 % | 45 / 66 % | 12 / 32 % | 1 / 7 % | 0 / 0 % | 0 / 0 % | 7 / 21 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 14 / 46 % | 40 / 64 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 14 / 46 % | 39 / 73 % | 7 / 18 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 9 / 59 % | 20 / 65 % | 7 / 17 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | 8 / 24 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 20 / 53 % | 5 / 13 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 18 / 59 % | 11 / 20 % | 9 / 26 % | 0 / 0 % | 9 / 21 % | 0 / 3 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 11 / 59 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 8 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 9 / 48 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 4 / 27 % | 8 / 25 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 11 % |
