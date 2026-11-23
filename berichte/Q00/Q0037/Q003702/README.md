[English](README.md) · [Deutsch](README.de.md)

# How Claude's text watermarking works

Report Q003702 · Source anthropic.com · Date 2026-08-14 · [Open original](https://www.anthropic.com/news/claude-text-watermark)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic erklärt, ein statistisches Muster in Claudes Wortwahl solle eine nachträgliche Einschätzung ermöglichen, ob Claude an einem Text mitgewirkt hat; das Unternehmen behauptet, Qualität, Lesbarkeit, Kosten und Geschwindigkeit würden dadurch praktisch nicht beeinflusst. Die Erkennung bleibt unsicher und funktioniert schlechter bei kurzen, stark vorgegebenen oder nur leicht bearbeiteten Texten sowie bei exaktem Code.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 73 / 81 % | 99 / 100 % | 100 / 100 % | 89 / 93 % | 90 / 93 % | 93 / 94 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 21 / 44 % | 96 / 97 % | 16 / 33 % | 7 / 13 % | 7 / 12 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 25 / 41 % | 62 / 93 % | 94 / 97 % | 21 / 39 % | 6 / 15 % | 13 / 23 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 40 % | 63 / 89 % | 90 / 94 % | 25 / 41 % | 8 / 17 % | 13 / 24 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 25 / 44 % | 0 / 0 % | 87 / 95 % | 35 / 56 % | 6 / 14 % | 12 / 27 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 32 / 57 % | 69 / 76 % | 32 / 51 % | 46 / 57 % | 0 / 0 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 46 / 64 % | 62 / 77 % | 14 / 32 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 21 / 40 % | 62 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 54 / 63 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 42 % | 0 / 0 % | 50 / 63 % | 11 / 30 % | 10 / 21 % | 8 / 18 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 18 / 31 % | 0 / 0 % | 49 / 71 % | 10 / 23 % | 5 / 14 % | 8 / 16 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 47 / 62 % | 14 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 47 / 60 % | 9 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 21 / 41 % | 40 / 92 % | 27 / 45 % | 25 / 43 % | 3 / 10 % | 8 / 15 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 29 / 64 % | 0 / 0 % | 11 / 23 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 40 % | 0 / 0 % | 0 / 0 % | 25 / 45 % | 10 / 19 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 20 / 64 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 0 / 0 % | 5 / 7 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 3 / 9 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 7 / 10 % | 7 / 11 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 8 % | 4 / 7 % | – | – |
