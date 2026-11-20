[English](README.md) · [Deutsch](README.de.md)

# Unsupervised learning: The curious pupil

Report Q004345 · Source deepmind.google · Date 2019-06-25 · [Open original](https://deepmind.google/blog/unsupervised-learning-the-curious-pupil/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der DeepMind-Artikel stellt unüberwachtes Lernen als Möglichkeit dar, aus der Struktur von Daten ohne konkrete menschliche Zielvorgaben zu lernen, und erläutert dies anhand von Bildrepräsentationen, GANs und autoregressiven Modellen. Er sieht darin Potenzial für übertragbares Wissen und Planung, benennt aber auch Grenzen der Repräsentationen sowie Missbrauchsrisiken generativer Medien.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 48 / 85 % | 1 / 11 % | 91 / 98 % | 9 / 31 % | 0 / 0 % | 7 / 25 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 29 / 47 % | 67 / 88 % | 65 / 78 % | 52 / 76 % | 58 / 78 % | 37 / 52 % | 53 / 71 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 61 / 91 % | 1 / 8 % | 48 / 82 % | 6 / 31 % | 0 / 0 % | 7 / 17 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 53 / 97 % | 0 / 6 % | 9 / 52 % | 5 / 24 % | 0 / 0 % | 5 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 44 / 65 % | 0 / 0 % | 6 / 40 % | 7 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 39 / 78 % | 0 / 3 % | 24 / 61 % | 5 / 15 % | 0 / 0 % | 4 / 15 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 35 / 62 % | 2 / 7 % | 23 / 55 % | 15 / 35 % | 4 / 10 % | 9 / 21 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 16 / 76 % | 1 / 9 % | 30 / 67 % | 7 / 26 % | 0 / 0 % | 6 / 23 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 24 / 77 % | 0 / 5 % | 2 / 30 % | 0 / 0 % | 0 / 0 % | 2 / 9 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 54 % | 5 / 12 % | 0 / 2 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 17 / 58 % | 0 / 0 % | 2 / 20 % | 5 / 13 % | 1 / 5 % | 2 / 7 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 12 / 76 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 10 / 53 % | 0 / 0 % | 0 / 0 % | 5 / 17 % | 0 / 0 % | 6 / 17 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 9 / 55 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 3 / 9 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 8 / 41 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 1 / 5 % | 5 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 81 % | 0 / 0 % | 7 / 25 % | 4 / 10 % | 1 / 4 % | 3 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 6 / 90 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 0 % | 4 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 6 / 15 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 12 % | 0 / 0 % | 5 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 37 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 1 / 7 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 2 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 12 % | 0 / 0 % | 2 / 7 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 2 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
