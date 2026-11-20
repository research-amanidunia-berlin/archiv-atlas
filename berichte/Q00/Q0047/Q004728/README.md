[English](README.md) · [Deutsch](README.de.md)

# Introducing Claude Opus 4.7

Report Q004728 · Source anthropic.com · Date 2026-04-16 · [Open original](https://www.anthropic.com/news/claude-opus-4-7)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge verbessert Claude Opus 4.7 gegenüber Opus 4.6 vor allem bei komplexem Programmieren, längeren Arbeitsabläufen, visuellen Aufgaben und der Befolgung von Anweisungen; interne Tests und frühe Kundenaussagen berichten von deutlichen Zugewinnen. Das Sicherheitsprofil sei insgesamt ähnlich, mit Stärken und einzelnen leichten Rückschritten; für riskante Cyberanfragen gibt es Schutzmaßnahmen. Das Modell ist zu den bisherigen Preisen verfügbar, doch Tokenverbrauch und ältere Prompts können sich anders verhalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 54 % | 97 / 99 % | – | 100 / 100 % | 69 / 85 % | 58 / 76 % | 20 / 40 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 51 % | 91 / 99 % | – | 99 / 100 % | 48 / 73 % | 56 / 77 % | 21 / 38 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 30 / 51 % | 75 / 91 % | – | 98 / 99 % | 66 / 83 % | 67 / 82 % | 25 / 46 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 40 % | 69 / 89 % | – | 96 / 98 % | 49 / 70 % | 37 / 55 % | 9 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 34 / 54 % | 56 / 87 % | – | 94 / 98 % | 10 / 27 % | 39 / 59 % | 9 / 22 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 80 / 94 % | – | 94 / 96 % | 25 / 52 % | 15 / 33 % | 5 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 27 / 49 % | 78 / 94 % | – | 93 / 96 % | 49 / 75 % | 37 / 70 % | 21 / 38 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 42 % | 0 / 0 % | – | 85 / 89 % | 22 / 48 % | 15 / 31 % | 1 / 4 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 53 / 77 % | – | 85 / 91 % | 9 / 27 % | 5 / 11 % | 1 / 4 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 27 / 75 % | – | 82 / 89 % | 8 / 26 % | 5 / 9 % | 1 / 3 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 25 / 57 % | – | 77 / 87 % | 37 / 63 % | 13 / 26 % | 4 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 50 / 91 % | – | 75 / 90 % | 8 / 28 % | 6 / 11 % | 1 / 6 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 18 / 53 % | – | 72 / 82 % | 28 / 54 % | 5 / 10 % | 3 / 9 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 13 / 63 % | – | 51 / 65 % | 7 / 21 % | 0 / 0 % | 1 / 4 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 50 / 90 % | – | 23 / 52 % | 27 / 55 % | 12 / 30 % | 4 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 43 / 71 % | – | 42 / 61 % | 8 / 23 % | 4 / 8 % | 0 / 2 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 43 / 85 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 1 / 3 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 40 % | 39 / 68 % | – | 34 / 53 % | 14 / 40 % | 13 / 28 % | 1 / 6 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 38 / 58 % | 6 / 18 % | 4 / 8 % | 1 / 5 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 37 / 75 % | – | 10 / 29 % | 13 / 31 % | 5 / 11 % | 2 / 7 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 36 % | 37 / 66 % | – | 13 / 27 % | 23 / 47 % | 28 / 45 % | 7 / 17 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 34 / 69 % | – | 12 / 38 % | 10 / 27 % | 5 / 10 % | 2 / 6 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 13 / 38 % | – | 27 / 43 % | 22 / 43 % | 16 / 27 % | 9 / 20 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 24 / 49 % | 0 / 0 % | 0 / 1 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 24 / 55 % | – | 0 / 0 % | 5 / 12 % | 4 / 6 % | 0 / 2 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 16 / 42 % | – | 0 / 0 % | 7 / 17 % | 5 / 9 % | 0 / 2 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 42 % | 0 / 0 % | – | 0 / 0 % | 16 / 40 % | 6 / 12 % | 1 / 4 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 24 % | 7 / 48 % | – | 14 / 27 % | 7 / 22 % | 6 / 13 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 25 % | 0 / 0 % | – | 0 / 0 % | 7 / 21 % | 8 / 16 % | 1 / 4 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 25 % | 10 / 19 % | 1 / 4 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 21 % | 4 / 9 % | 0 / 1 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 3 / 7 % | 0 / 1 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 44 % | – | 0 / 0 % | 7 / 18 % | 0 / 0 % | 1 / 5 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 1 / 3 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 2 / 5 % | 0 / 1 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 4 / 13 % | 5 / 12 % | 3 / 5 % | 1 / 5 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 2 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
