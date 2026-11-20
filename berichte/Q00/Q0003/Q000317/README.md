[English](README.md) · [Deutsch](README.de.md)

# OpenAI study probes reasoning-trace oversight

Report Q000317 · Source casrai.org · Date 2026-11-14 · [Open original](https://casrai.org/news/openai-chain-of-thought-monitorability-training-study-2026)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht zufolge beeinflussen Vortraining, Architektur, bestärkendes Lernen und modellgenerierte Daten sowohl Schlussfolgern ohne sichtbare Reasoning-Spur als auch die Kontrollierbarkeit von Spuren. In den beschriebenen Ausweichtests schnitten kontrollierbarere Modelle nicht besser ab; die Befunde sind jedoch begrenzt und belegen weder Täuschungsabsicht noch eine grundsätzliche Grenze der Überwachung. Hochschulen sollten verschiedene Prüfziele sowie interne und öffentliche Modellkonfigurationen auseinanderhalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 54 % | 53 / 92 % | 7 / 41 % | 90 / 98 % | 28 / 63 % | 25 / 57 % | 10 / 36 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 22 / 73 % | 2 / 11 % | 89 / 96 % | 22 / 57 % | 0 / 0 % | 2 / 12 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 39 / 63 % | 47 / 93 % | 58 / 87 % | 87 / 96 % | 76 / 89 % | 81 / 90 % | 72 / 87 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 60 % | 73 / 98 % | 33 / 82 % | 80 / 95 % | 57 / 82 % | 50 / 75 % | 40 / 72 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 60 % | 35 / 96 % | 23 / 64 % | 76 / 91 % | 49 / 79 % | 59 / 79 % | 55 / 77 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 21 / 49 % | 20 / 54 % | 1 / 11 % | 57 / 76 % | 16 / 48 % | 16 / 37 % | 6 / 22 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 21 / 81 % | 1 / 9 % | 54 / 78 % | 15 / 41 % | 13 / 31 % | 7 / 22 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 43 % | 0 / 0 % | 52 / 75 % | 6 / 14 % | 0 / 0 % | 1 / 4 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 49 % | 18 / 62 % | 1 / 9 % | 51 / 78 % | 16 / 49 % | 8 / 19 % | 7 / 23 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 12 / 47 % | 0 / 0 % | 44 / 77 % | 7 / 19 % | 8 / 19 % | 1 / 4 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 13 / 46 % | 33 / 83 % | 2 / 17 % | 38 / 69 % | 24 / 54 % | 7 / 18 % | 4 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 12 / 45 % | 0 / 0 % | 36 / 64 % | 7 / 21 % | 0 / 0 % | 2 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 19 / 47 % | 35 / 76 % | 0 / 0 % | 0 / 0 % | 15 / 42 % | 11 / 30 % | 2 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 47 % | 15 / 82 % | 5 / 26 % | 32 / 69 % | 5 / 14 % | 11 / 28 % | 4 / 16 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 40 % | 29 / 85 % | 0 / 4 % | 18 / 49 % | 11 / 41 % | 9 / 25 % | 3 / 15 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 24 / 70 % | 1 / 10 % | 9 / 55 % | 11 / 38 % | 9 / 21 % | 1 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 20 / 66 % | 1 / 6 % | 22 / 59 % | 16 / 46 % | 0 / 0 % | 3 / 9 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 11 / 41 % | 19 / 89 % | 1 / 10 % | 20 / 82 % | 15 / 48 % | 10 / 23 % | 4 / 16 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 19 / 91 % | 1 / 7 % | 0 / 0 % | 8 / 32 % | 8 / 18 % | 5 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 43 % | 0 / 0 % | 0 / 2 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 12 / 52 % | 0 / 0 % | 14 / 54 % | 6 / 18 % | 0 / 0 % | 1 / 5 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 12 / 56 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 3 / 6 % | 1 / 4 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 11 / 73 % | 0 / 0 % | 0 / 0 % | 5 / 17 % | 0 / 0 % | 1 / 6 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 41 % | 5 / 15 % | 0 / 0 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 9 / 33 % | 9 / 21 % | 3 / 13 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 23 % | 8 / 18 % | 1 / 9 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 0 / 0 % | 8 / 25 % | 0 / 0 % | 2 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 1 / 5 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 0 / 2 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 3 / 8 % | 0 / 2 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 57 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | 1 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 23 % | 5 / 12 % | 0 / 0 % | 1 / 3 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 2 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 2 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 3 / 5 % | 0 / 2 % |
