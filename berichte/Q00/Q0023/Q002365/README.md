[English](README.md) · [Deutsch](README.de.md)

# Demystifying evals for AI agents

Report Q002365 · Source anthropic.com · Date 2026-01-09 · [Open original](https://www.anthropic.com/research/demystifying-evals-for-ai-agents)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic empfiehlt, KI-Agenten früh und fortlaufend mit realistischen Aufgaben zu prüfen, klare Erfolgskriterien festzulegen und geeignete Code-, Modell- und menschliche Bewertungen zu kombinieren. Weil einzelne Evals Fehler übersehen oder gültige Lösungen unfair bewerten können, sollten Teams Versuchsprotokolle kontrollieren und automatisierte Tests durch Produktionsdaten, Nutzerfeedback und menschliche Prüfung ergänzen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 56 % | 99 / 100 % | 87 / 97 % | 53 / 78 % | 54 / 76 % | 62 / 78 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 45 / 79 % | 79 / 95 % | 30 / 59 % | 11 / 32 % | 19 / 33 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 25 / 55 % | 75 / 99 % | 75 / 94 % | 52 / 75 % | 11 / 38 % | 36 / 60 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 54 % | 46 / 83 % | 67 / 85 % | 46 / 74 % | 20 / 45 % | 38 / 62 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 62 / 98 % | 40 / 83 % | 16 / 43 % | 8 / 24 % | 15 / 31 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 25 / 90 % | 58 / 66 % | 18 / 45 % | 4 / 19 % | 8 / 21 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 26 / 49 % | 27 / 66 % | 0 / 0 % | 51 / 77 % | 39 / 64 % | 56 / 74 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 22 / 49 % | 52 / 92 % | 30 / 74 % | 10 / 26 % | 12 / 36 % | 24 / 48 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 36 % | 44 / 95 % | 0 / 0 % | 10 / 36 % | 2 / 13 % | 7 / 14 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 22 / 46 % | 43 / 94 % | 21 / 55 % | 31 / 63 % | 17 / 39 % | 28 / 53 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 38 / 76 % | 0 / 0 % | 9 / 22 % | 1 / 5 % | 7 / 17 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 35 / 91 % | 0 / 0 % | 7 / 22 % | 4 / 12 % | 8 / 17 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 28 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 51 % | 7 / 20 % | 9 / 20 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 89 % | 8 / 22 % | 16 / 44 % | 8 / 22 % | 17 / 29 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 17 / 55 % | 0 / 0 % | 9 / 28 % | 3 / 9 % | 7 / 15 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 34 % | 11 / 78 % | 0 / 0 % | 15 / 41 % | 7 / 26 % | 14 / 33 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 25 % | 5 / 13 % | 11 / 21 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 33 % | 1 / 3 % | 11 / 21 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 32 % | 3 / 10 % | 6 / 13 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 9 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 9 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 4 / 9 % | 8 / 16 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 8 / 13 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 8 / 36 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 1 / 6 % | 5 / 9 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 3 % | 4 / 9 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 5 / 39 % | 0 / 0 % | 6 / 17 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 5 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 2 / 5 % | 4 / 7 % | – | – |
