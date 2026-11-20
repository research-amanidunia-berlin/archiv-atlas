[English](README.md) · [Deutsch](README.de.md)

# What affects chain-of-thought monitorability across the model lifecycle?

Report Q000288 · Source alignment.openai.com · Date 2026-11-10 · [Open original](https://alignment.openai.com/cot-monitorability-model-lifecycle/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt Zusammenhänge zwischen sinkender Basismodell-Perplexität, besseren Fähigkeiten ohne sichtbaren CoT und steigender CoT-Kontrollierbarkeit; auch RL und modellgenerierte Trainingsdaten können laut den Experimenten die Kontrollierbarkeit erhöhen. Die Autorinnen und Autoren folgern, dass CoT-Überwachung dadurch schwieriger werden könnte, betonen aber, dass die verwendeten Ersatzmaße unvollkommen sind und Kontrollierbarkeit in den berichteten Vergleichstests nicht zuverlässig mit tatsächlicher Monitor-Umgehung einherging.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 64 % | 97 / 99 % | 39 / 71 % | – | 55 / 77 % | – | 20 / 41 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 55 / 73 % | 43 / 88 % | 34 / 68 % | – | 68 / 84 % | – | 36 / 59 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 37 / 63 % | 66 / 99 % | 3 / 16 % | – | 37 / 66 % | – | 13 / 29 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 64 / 87 % | 0 / 0 % | – | 39 / 61 % | – | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 22 / 48 % | 60 / 99 % | 5 / 23 % | – | 28 / 59 % | – | 5 / 17 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 31 / 55 % | 43 / 91 % | 2 / 7 % | – | 25 / 50 % | – | 6 / 18 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 59 % | 41 / 92 % | 11 / 41 % | – | 35 / 64 % | – | 12 / 30 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 26 / 57 % | 24 / 60 % | 8 / 29 % | – | 35 / 62 % | – | 4 / 12 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 8 / 65 % | 1 / 5 % | – | 35 / 60 % | – | 3 / 11 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 12 / 42 % | 35 / 97 % | 4 / 25 % | – | 33 / 58 % | – | 3 / 11 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 27 / 60 % | 0 / 0 % | – | 12 / 27 % | – | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 24 / 50 % | 19 / 64 % | 1 / 5 % | – | 18 / 42 % | – | 3 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 2 / 9 % | – | 22 / 46 % | – | 3 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 20 / 49 % | 0 / 0 % | 0 / 3 % | – | 15 / 42 % | – | 4 / 11 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 20 / 77 % | 0 / 0 % | – | 5 / 13 % | – | 1 / 4 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 44 % | 0 / 0 % | 0 / 0 % | – | 9 / 34 % | – | 2 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 19 / 62 % | 1 / 4 % | – | 14 / 39 % | – | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 47 % | 0 / 0 % | 2 / 7 % | – | 18 / 43 % | – | 2 / 9 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 7 / 52 % | 1 / 5 % | – | 9 / 27 % | – | 1 / 6 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 24 % | – | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 1 / 6 % | – | 7 / 22 % | – | 2 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 18 % | – | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | – | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 22 % | – | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | – | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | – | 1 / 4 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | – | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | – | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | – | 1 / 5 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 15 % | – | 1 / 5 % |
