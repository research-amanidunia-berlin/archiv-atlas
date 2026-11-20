[English](README.md) · [Deutsch](README.de.md)

# Reasoning models struggle to control their chains of thought, and that’s good

Report Q007450 · Source openai.com · Date 2026-03-05 · [Open original](https://openai.com/index/reasoning-models-chain-of-thought-controllability/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, dass 13 getestete Reasoning-Modelle Vorgaben zur Gestaltung ihrer Gedankenspuren nur selten befolgten; die gemessenen Werte lagen höchstens bei 15,4 Prozent. Das könne CoT-Monitoring derzeit stützen, beweist aber keine generelle Sicherheit: Die Tests sind nur ein Näherungsmaß und erfassen tatsächliche Verschleierung fehlgeleiteter Ziele nicht direkt. Der bereitgestellte Bericht enthält Abbildungsplatzhalter, nicht die Grafiken selbst.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 59 % | 68 / 94 % | – | 99 / 100 % | 48 / 74 % | 47 / 73 % | 18 / 45 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 63 % | 95 / 99 % | – | 96 / 98 % | 61 / 80 % | 55 / 73 % | 32 / 61 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 25 / 48 % | 51 / 81 % | – | 91 / 94 % | 38 / 60 % | 19 / 32 % | 9 / 24 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 46 / 66 % | 87 / 99 % | – | 71 / 87 % | 54 / 76 % | 51 / 67 % | 46 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 53 / 70 % | 66 / 91 % | – | 68 / 83 % | 77 / 88 % | 79 / 87 % | 55 / 74 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 50 % | 9 / 45 % | – | 65 / 79 % | 31 / 57 % | 17 / 32 % | 5 / 16 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 23 / 49 % | 63 / 96 % | – | 37 / 74 % | 27 / 55 % | 13 / 28 % | 6 / 24 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 29 / 58 % | 39 / 82 % | – | 56 / 78 % | 14 / 31 % | 13 / 28 % | 4 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 4 / 48 % | – | 50 / 65 % | 21 / 45 % | 0 / 0 % | 3 / 10 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 15 / 44 % | 46 / 97 % | – | 47 / 77 % | 27 / 54 % | 15 / 36 % | 2 / 13 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 47 / 67 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 2 / 34 % | – | 47 / 68 % | 6 / 14 % | 6 / 10 % | 1 / 4 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 37 / 58 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 35 / 47 % | 7 / 23 % | 17 / 31 % | 2 / 13 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 86 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 29 / 69 % | – | 26 / 54 % | 6 / 14 % | 0 / 0 % | 1 / 6 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 44 % | 27 / 88 % | – | 0 / 0 % | 7 / 18 % | 11 / 22 % | 2 / 13 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 14 / 45 % | – | 22 / 43 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 21 / 71 % | – | 0 / 0 % | 7 / 20 % | 12 / 21 % | 4 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 17 / 48 % | 0 / 0 % | – | 0 / 0 % | 17 / 39 % | 0 / 0 % | 5 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 39 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 13 / 24 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 14 / 37 % | 5 / 13 % | 0 / 0 % | 1 / 6 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 13 / 43 % | – | 0 / 0 % | 8 / 20 % | 10 / 21 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 12 / 47 % | – | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 33 % | 12 / 85 % | – | 0 / 0 % | 7 / 21 % | 7 / 18 % | 2 / 10 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % | 1 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 5 / 10 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 5 / 13 % | 1 / 5 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 5 % |
