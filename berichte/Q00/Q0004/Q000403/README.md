[English](README.md) · [Deutsch](README.de.md)

# Forget What Comes Next: LLM Unlearning via Statistical Independence

Report Q000403 · Source arxiv.org · Date – · [Open original](https://arxiv.org/abs/2611.03955)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Bericht ist nur der arXiv-Eintrag mit Abstract. Die Autoren beschreiben PINT als ein HSIC-basiertes Verfahren zum Verlernen von Modellinhalten und berichten von einem besonders guten Verhältnis zwischen Vergessen und Nutzbarkeit; konkrete Messwerte und Versuchsdetails fehlen im Auszug.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 32 / 79 % | 84 / 89 % | 37 / 61 % | 0 / 0 % | 19 / 42 % | 6 / 27 % | 35 / 55 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 22 / 52 % | 84 / 91 % | 9 / 26 % | 0 / 0 % | 7 / 21 % | 0 / 5 % | 15 / 30 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 30 / 50 % | 1 / 4 % | 8 / 23 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 28 / 51 % | 12 / 28 % | 5 / 10 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 8 / 23 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 32 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 25 % | 0 / 0 % | 7 / 16 % | 1 / 5 % | 15 / 32 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 14 / 47 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 11 / 36 % | 6 / 14 % | 1 / 4 % | 5 / 10 % | 0 / 0 % | 5 / 18 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 7 / 22 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 5 / 16 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 8 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
