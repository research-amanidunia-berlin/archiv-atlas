[English](README.md) · [Deutsch](README.de.md)

# Addendum to GPT-5.2 System Card: GPT-5.2-Codex

Report Q000982 · Source deploymentsafety.openai.com · Date 2025-12-18 · [Open original](https://deploymentsafety.openai.com/gpt-5-2-codex)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet von deutlichen Fortschritten bei GPT-5.2-Codex, stuft seine Cyberfähigkeiten aber trotz starker Einzelergebnisse unterhalb der eigenen Hoch-Schwelle ein; im biologisch-chemischen Bereich gilt es als Hochrisiko. Die Ergebnisse fallen je nach Test unterschiedlich aus, und der Bericht schränkt ein, dass Benchmarks reale Einsatzbedingungen und durchschnittlichen Produktverkehr nur begrenzt abbilden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 71 / 82 % | 97 / 98 % | 98 / 100 % | 100 / 100 % | 85 / 92 % | 87 / 91 % | 78 / 88 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 59 / 75 % | 99 / 100 % | 80 / 89 % | 100 / 100 % | 91 / 95 % | 79 / 89 % | 25 / 43 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 50 / 66 % | 98 / 100 % | 77 / 90 % | 100 / 100 % | 88 / 93 % | 79 / 89 % | 54 / 74 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 62 / 77 % | 97 / 98 % | 98 / 99 % | 100 / 100 % | 92 / 95 % | 88 / 92 % | 78 / 89 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 54 / 96 % | 24 / 47 % | 98 / 99 % | 80 / 90 % | 26 / 43 % | 33 / 51 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 51 / 69 % | 97 / 100 % | 38 / 66 % | 78 / 91 % | 78 / 89 % | 68 / 81 % | 25 / 48 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 42 / 58 % | 58 / 92 % | 58 / 81 % | 97 / 98 % | 75 / 87 % | 86 / 92 % | 67 / 81 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 31 / 52 % | 91 / 97 % | 5 / 18 % | 95 / 97 % | 44 / 68 % | 33 / 49 % | 10 / 20 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 40 / 57 % | 91 / 99 % | 17 / 37 % | 93 / 96 % | 80 / 89 % | 70 / 83 % | 41 / 61 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 77 / 96 % | 8 / 14 % | 93 / 95 % | 14 / 33 % | 18 / 29 % | 4 / 9 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 27 / 46 % | 58 / 84 % | 11 / 31 % | 92 / 95 % | 76 / 87 % | 67 / 83 % | 22 / 40 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 46 / 64 % | 82 / 98 % | 82 / 91 % | 81 / 88 % | 85 / 92 % | 87 / 93 % | 56 / 74 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 46 / 65 % | 81 / 100 % | 40 / 52 % | 52 / 73 % | 70 / 84 % | 82 / 88 % | 64 / 80 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 43 / 62 % | 63 / 95 % | 20 / 49 % | 78 / 90 % | 73 / 87 % | 57 / 71 % | 17 / 35 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 5 / 63 % | 0 / 0 % | 68 / 80 % | 8 / 17 % | 0 / 0 % | 2 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 12 / 55 % | 0 / 1 % | 67 / 82 % | 11 / 31 % | 9 / 17 % | 5 / 14 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 63 / 81 % | 13 / 35 % | 6 / 13 % | 3 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 44 / 79 % | 2 / 7 % | 59 / 76 % | 13 / 30 % | 14 / 23 % | 5 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 7 / 15 % | 42 / 55 % | 26 / 51 % | 28 / 45 % | 10 / 20 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 41 / 76 % | 0 / 3 % | 0 / 0 % | 9 / 20 % | 7 / 13 % | 3 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 38 / 92 % | 2 / 9 % | 9 / 45 % | 19 / 41 % | 8 / 20 % | 8 / 18 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 15 / 42 % | 0 / 0 % | 4 / 12 % | 0 / 0 % | 32 / 58 % | 17 / 31 % | 5 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 24 / 53 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 19 / 45 % | 27 / 46 % | 6 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 6 / 64 % | 2 / 6 % | 27 / 48 % | 20 / 44 % | 12 / 23 % | 9 / 22 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 25 / 65 % | 0 / 0 % | 17 / 40 % | 10 / 25 % | 6 / 15 % | 3 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 23 / 67 % | 0 / 0 % | 8 / 30 % | 9 / 23 % | 8 / 14 % | 1 / 4 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 17 / 51 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 8 / 15 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 24 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 8 / 20 % | 11 / 21 % | 4 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 8 / 19 % | 11 / 20 % | 3 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 0 % | 2 / 7 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 14 % | 0 / 1 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 6 / 10 % | 3 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 44 % | 0 / 2 % | 0 / 0 % | 8 / 21 % | 6 / 12 % | 3 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 7 / 56 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 2 / 5 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 1 / 5 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 6 / 11 % | 3 / 9 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 1 / 5 % |
