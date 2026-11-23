[English](README.md) · [Deutsch](README.de.md)

# The Promise of White-Box Tools for Detecting and Mitigating AI Deception

Report Q001284 · Source far.ai · Date 2026-08-19 · [Open original](https://www.far.ai/blog/ai-deception-white-box)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

FAR.AI sieht in White-Box-Verfahren, die interne Modellzustände untersuchen, eine vielversprechende Ergänzung zu Black-Box-Monitoren, die Ausgaben prüfen und verborgene Absichten übersehen können. Ihre Zuverlässigkeit, Verallgemeinerung und Robustheit sind jedoch nicht geklärt; der Bericht fordert deshalb größere und vielfältigere Experimente sowie mehr Transparenz von KI-Laboren.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 69 / 81 % | 77 / 99 % | 98 / 100 % | 85 / 91 % | 81 / 90 % | 88 / 92 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 54 % | 60 / 96 % | 95 / 98 % | 43 / 71 % | 15 / 41 % | 37 / 68 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 57 % | 86 / 98 % | 70 / 94 % | 56 / 79 % | 38 / 62 % | 42 / 68 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 38 / 59 % | 77 / 100 % | 86 / 97 % | 64 / 84 % | 48 / 72 % | 68 / 84 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 46 % | 62 / 92 % | 82 / 89 % | 44 / 68 % | 19 / 38 % | 22 / 43 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 5 / 81 % | 42 / 60 % | 10 / 23 % | 5 / 16 % | 11 / 22 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 41 % | 40 / 95 % | 0 / 0 % | 9 / 29 % | 1 / 7 % | 8 / 21 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 15 / 43 % | 7 / 71 % | 39 / 73 % | 17 / 39 % | 6 / 17 % | 8 / 17 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 17 / 88 % | 38 / 68 % | 12 / 41 % | 7 / 18 % | 9 / 23 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 2 / 68 % | 36 / 56 % | 13 / 33 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 11 / 77 % | 31 / 55 % | 16 / 41 % | 3 / 11 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 28 / 75 % | 13 / 38 % | 12 / 35 % | 2 / 8 % | 6 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 7 / 57 % | 2 / 8 % | 26 / 49 % | 2 / 9 % | 5 / 13 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 17 / 74 % | 25 / 39 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 25 / 70 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 20 / 70 % | 1 / 7 % | 8 / 22 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 15 / 40 % | 16 / 63 % | 19 / 48 % | 6 / 19 % | 3 / 13 % | 9 / 26 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 13 / 71 % | 19 / 41 % | 12 / 35 % | 3 / 9 % | 10 / 22 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 29 % | 16 / 88 % | 1 / 9 % | 10 / 32 % | 2 / 11 % | 7 / 22 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 14 / 49 % | 8 / 31 % | 6 / 16 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 8 / 91 % | 13 / 61 % | 13 / 40 % | 4 / 16 % | 9 / 24 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 13 / 51 % | 4 / 42 % | 12 / 37 % | 2 / 10 % | 7 / 18 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 12 / 57 % | 8 / 20 % | 8 / 21 % | 0 / 0 % | 2 / 5 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 6 % | 9 / 21 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 3 / 9 % | 8 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 0 / 2 % | 4 / 9 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 8 / 40 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 3 % | 2 / 4 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 7 / 52 % | 3 / 27 % | 5 / 12 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 4 / 22 % | 6 / 18 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 3 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 26 % | 0 / 0 % | 5 / 11 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 75 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
