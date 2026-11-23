[English](README.md) · [Deutsch](README.de.md)

# Piloting the world's first double-blind AI evaluations

Report Q001169 · Source deepmind.google · Date 2026-08-27 · [Open original](https://deepmind.google/blog/piloting-the-worlds-first-double-blind-ai-evaluations/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind beschreibt einen Pilotversuch, bei dem ein Gemini-Flash-Lite-Modell anhand vertraulicher Benchmarks doppelt verblindet geprüft werden soll. Kryptografische Kontrollen in Google Cloud sollen laut Beitrag sowohl die Testfragen als auch die Modellgewichte vor der jeweils anderen Seite schützen. Konkrete Ergebnisse und Details zur Umsetzung enthält der vorliegende Text nicht; er verweist dafür auf einen technischen Bericht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 50 / 68 % | 40 / 86 % | 99 / 100 % | 50 / 73 % | 77 / 86 % | 62 / 72 % | 62 / 79 % | 41 / 64 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 58 / 74 % | 95 / 99 % | 99 / 100 % | 71 / 85 % | 90 / 95 % | 86 / 91 % | 94 / 98 % | 46 / 67 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 49 / 68 % | 79 / 93 % | 99 / 100 % | 67 / 81 % | 65 / 78 % | 35 / 51 % | 68 / 85 % | 22 / 45 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 43 / 67 % | 67 / 89 % | 91 / 98 % | 17 / 31 % | 69 / 81 % | 79 / 87 % | 60 / 83 % | 38 / 64 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 43 % | 53 / 83 % | 76 / 90 % | 25 / 46 % | 14 / 28 % | 27 / 46 % | 6 / 22 % | 14 / 33 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 25 / 45 % | 35 / 79 % | 75 / 91 % | 18 / 45 % | 6 / 19 % | 17 / 40 % | 6 / 20 % | 25 / 46 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 20 / 42 % | 51 / 85 % | 75 / 86 % | 20 / 42 % | 5 / 14 % | 8 / 18 % | 1 / 4 % | 11 / 28 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 26 / 58 % | 73 / 85 % | 8 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 21 / 44 % | 69 / 85 % | 31 / 47 % | 36 / 57 % | 8 / 20 % | 21 / 36 % | 6 / 12 % | 41 / 63 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 21 / 45 % | 44 / 79 % | 62 / 88 % | 29 / 55 % | 10 / 25 % | 24 / 44 % | 6 / 25 % | 20 / 43 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 30 / 59 % | 49 / 87 % | 0 / 0 % | 10 / 28 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 20 / 43 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 30 / 53 % | 25 / 95 % | 47 / 76 % | 46 / 70 % | 27 / 43 % | 17 / 38 % | 16 / 43 % | 10 / 29 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 35 / 89 % | 47 / 66 % | 6 / 20 % | 2 / 8 % | 4 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 45 / 93 % | 0 / 0 % | 9 / 32 % | 0 / 0 % | 10 / 25 % | 1 / 6 % | 22 / 41 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 8 / 51 % | 0 / 0 % | 34 / 55 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 11 / 32 % | 0 / 0 % | 33 / 70 % | 7 / 22 % | 2 / 10 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 31 / 58 % | 21 / 47 % | 8 / 18 % | 2 / 10 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 17 / 56 % | 0 / 0 % | 20 / 48 % | 23 / 42 % | 27 / 46 % | 8 / 25 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 23 / 84 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 23 / 74 % | 0 / 0 % | 7 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 22 / 76 % | 1 / 14 % | 9 / 25 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 6 / 25 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 18 / 44 % | 20 / 47 % | 5 / 9 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 15 / 31 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 9 % | 9 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 11 / 52 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 18 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 5 / 9 % | 0 / 0 % | 3 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % |
