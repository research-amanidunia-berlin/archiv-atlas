[English](README.md) · [Deutsch](README.de.md)

# Red Teaming Language Models with Language Models

Report Q003654 · Source deepmind.google · Date 2022-02-07 · [Open original](https://deepmind.google/blog/red-teaming-language-models-with-language-models/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt automatisiertes Red-Teaming: Ein Sprachmodell erzeugt Testeingaben, ein Zielmodell antwortet und ein Klassifikator sucht nach schädlichen Ausgaben. Die Autoren sehen darin eine Ergänzung zu manuellen Prüfungen und nennen mögliche Gegenmaßnahmen, betonen aber, dass das Verfahren nur ein Baustein für sichere Sprachmodelle ist.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 53 % | 85 / 99 % | 24 / 60 % | 96 / 99 % | 42 / 71 % | 7 / 24 % | 32 / 62 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 24 / 51 % | 49 / 97 % | 31 / 70 % | 87 / 97 % | 11 / 29 % | 7 / 24 % | 13 / 35 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 27 / 51 % | 78 / 99 % | 29 / 69 % | 87 / 97 % | 31 / 62 % | 17 / 45 % | 35 / 61 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 65 / 80 % | 8 / 15 % | 16 / 27 % | 27 / 55 % | 5 / 17 % | 16 / 35 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 57 / 98 % | 16 / 44 % | 61 / 84 % | 38 / 67 % | 10 / 30 % | 26 / 56 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 27 / 67 % | 12 / 37 % | 59 / 78 % | 42 / 69 % | 9 / 28 % | 42 / 66 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 41 / 77 % | 4 / 21 % | 16 / 64 % | 19 / 48 % | 3 / 13 % | 10 / 25 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 38 / 74 % | 0 / 0 % | 0 / 5 % | 0 / 0 % | 0 / 3 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 37 / 70 % | 0 / 2 % | 11 / 48 % | 5 / 16 % | 1 / 5 % | 3 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 32 / 90 % | 1 / 5 % | 6 / 19 % | 7 / 18 % | 2 / 9 % | 7 / 19 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 30 / 65 % | 0 / 5 % | 28 / 69 % | 9 / 25 % | 2 / 7 % | 5 / 13 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 30 / 65 % | 0 / 0 % | 29 / 55 % | 6 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 26 / 55 % | 0 / 3 % | 29 / 64 % | 6 / 17 % | 1 / 4 % | 5 / 12 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 26 / 58 % | 0 / 2 % | 24 / 47 % | 8 / 21 % | 0 / 0 % | 13 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 22 / 53 % | 11 / 33 % | 1 / 6 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 22 / 54 % | 0 / 4 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 4 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 68 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 18 / 86 % | 1 / 7 % | 7 / 50 % | 12 / 39 % | 2 / 10 % | 9 / 20 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 13 / 64 % | 1 / 7 % | 10 / 32 % | 6 / 19 % | 1 / 6 % | 8 / 16 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 13 / 46 % | 1 / 6 % | 0 / 0 % | 9 / 26 % | 1 / 8 % | 9 / 22 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 13 / 40 % | 11 / 36 % | 0 / 0 % | 6 / 17 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 13 / 43 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 26 % | 0 / 0 % | 5 / 14 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 9 / 54 % | 0 / 0 % | 4 / 21 % | 7 / 20 % | 0 / 0 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 0 / 4 % | 7 / 24 % | 1 / 7 % | 4 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 7 / 24 % | 0 / 3 % | 3 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 30 % | 4 / 13 % | 0 / 4 % | 2 / 8 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 21 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 12 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 1 / 4 % | 0 / 0 % |
