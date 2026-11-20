[English](README.md) · [Deutsch](README.de.md)

# Expanding on how Voice Engine works and our safety research

Report Q001951 · Source openai.com · Date 2024-06-07 · [Open original](https://openai.com/index/expanding-on-how-voice-engine-works-and-our-safety-research/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI zufolge kann Voice Engine aus einer 15-sekündigen Sprachprobe und Text eine ähnlich klingende Stimme erzeugen; das Verfahren werde nicht für einzelne Personen nachtrainiert. Das Unternehmen beschreibt begrenzte Einsätze und Schutzvorgaben wie Zustimmung, Offenlegung und Wasserzeichen, räumt Risiken synthetischer Stimmen ein und kündigt für GPT‑4o zunächst nur vorgegebene Stimmen an. Die Wirksamkeit der Maßnahmen wird im Bericht nicht unabhängig belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 43 % | 72 / 93 % | – | 99 / 100 % | 54 / 75 % | 24 / 45 % | 47 / 67 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 39 % | 75 / 91 % | – | 97 / 99 % | 29 / 51 % | 12 / 26 % | 26 / 45 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 68 / 93 % | – | 95 / 98 % | 31 / 57 % | 18 / 33 % | 40 / 54 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 70 / 91 % | – | 95 / 97 % | 12 / 35 % | 5 / 15 % | 14 / 30 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 27 / 59 % | – | 92 / 97 % | 20 / 44 % | 6 / 17 % | 10 / 23 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 70 / 90 % | – | 92 / 97 % | 19 / 43 % | 11 / 27 % | 19 / 38 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 43 % | 85 / 99 % | – | 91 / 97 % | 28 / 56 % | 16 / 37 % | 31 / 57 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 45 / 59 % | 89 / 98 % | – | 91 / 96 % | 74 / 85 % | 66 / 78 % | 72 / 81 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 22 / 41 % | 63 / 84 % | – | 85 / 92 % | 27 / 52 % | 9 / 25 % | 11 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 40 / 74 % | – | 84 / 94 % | 10 / 27 % | 4 / 11 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 52 / 95 % | – | 84 / 93 % | 11 / 35 % | 2 / 13 % | 7 / 22 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 22 / 51 % | – | 83 / 93 % | 26 / 50 % | 9 / 24 % | 15 / 28 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 78 / 94 % | 9 / 27 % | 4 / 17 % | 8 / 22 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 31 % | 0 / 0 % | – | 77 / 84 % | 15 / 43 % | 4 / 15 % | 12 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 52 / 83 % | – | 73 / 89 % | 6 / 13 % | 1 / 4 % | 5 / 11 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 41 / 73 % | – | 72 / 84 % | 10 / 28 % | 2 / 8 % | 7 / 16 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 72 / 84 % | – | 4 / 19 % | 8 / 18 % | 2 / 10 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 54 / 89 % | – | 25 / 50 % | 6 / 13 % | 0 / 0 % | 6 / 13 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 51 / 93 % | – | 47 / 66 % | 6 / 18 % | 2 / 11 % | 5 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 45 / 81 % | – | 25 / 63 % | 10 / 25 % | 4 / 10 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 38 / 92 % | – | 29 / 73 % | 11 / 32 % | 3 / 15 % | 7 / 23 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 34 / 67 % | 15 / 35 % | 5 / 15 % | 8 / 19 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 21 / 52 % | – | 33 / 59 % | 12 / 34 % | 5 / 15 % | 7 / 17 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 32 / 77 % | – | 15 / 49 % | 12 / 30 % | 3 / 11 % | 8 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 31 / 54 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 87 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 19 / 43 % | 10 / 27 % | 2 / 7 % | 6 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 26 % | 11 / 23 % | 11 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 23 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 2 / 7 % | 7 / 17 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 1 / 7 % | 7 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 5 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 2 / 8 % | 0 / 0 % |
