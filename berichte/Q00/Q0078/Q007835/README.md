[English](README.md) · [Deutsch](README.de.md)

# DALL·E 2 pre-training mitigations

Report Q007835 · Source openai.com · Date 2022-06-28 · [Open original](https://openai.com/index/dall-e-2-pre-training-mitigations/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, dass Bildfilter DALL·E 2 weniger explizite und drastische Inhalte erzeugen ließen, aber demografische Verzerrungen verstärkten; eine nachträgliche Gewichtung habe diese Verschiebungen in einer begrenzten Schlüsselwortmessung reduziert. Außerdem habe Deduplizierung die Wiedergabe von Trainingsbildern in Tests verhindert, wobei fast ein Viertel der Daten entfiel und weitere Forschung zu Verzerrungen und Memorierung nötig bleibe.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 39 / 58 % | 99 / 100 % | – | 93 / 97 % | 49 / 70 % | 29 / 48 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 85 / 99 % | – | 99 / 100 % | 35 / 60 % | 34 / 55 % | 10 / 23 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 77 / 97 % | – | 92 / 96 % | 49 / 71 % | 33 / 54 % | 12 / 29 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 41 / 73 % | – | 85 / 90 % | 24 / 50 % | 19 / 37 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 54 / 88 % | – | 81 / 90 % | 11 / 28 % | 10 / 25 % | 2 / 9 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 15 / 44 % | – | 69 / 83 % | 8 / 22 % | 0 / 0 % | 1 / 5 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 65 / 94 % | – | 22 / 50 % | 10 / 25 % | 6 / 13 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 38 / 73 % | – | 49 / 71 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | – | 48 / 68 % | 16 / 42 % | 8 / 23 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 45 / 94 % | – | 32 / 63 % | 11 / 24 % | 10 / 18 % | 3 / 11 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 34 / 58 % | 8 / 21 % | 7 / 14 % | 2 / 10 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 33 / 66 % | 6 / 17 % | 6 / 16 % | 1 / 6 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 69 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 28 / 58 % | 5 / 11 % | 0 / 0 % | 1 / 5 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 16 / 80 % | – | 0 / 0 % | 7 / 19 % | 7 / 15 % | 2 / 8 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 14 / 61 % | – | 3 / 13 % | 9 / 23 % | 10 / 24 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 8 / 23 % | 11 / 27 % | 7 / 14 % | 2 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 26 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 6 / 41 % | – | 7 / 15 % | 10 / 28 % | 9 / 17 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 9 / 17 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 55 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 5 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 6 / 12 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 4 / 8 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 59 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 6 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 67 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
