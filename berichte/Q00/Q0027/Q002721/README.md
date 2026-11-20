[English](README.md) · [Deutsch](README.de.md)

# Introducing Claude 3.5 Sonnet

Report Q002721 · Source anthropic.com · Date 2024-06-21 · [Open original](https://www.anthropic.com/news/claude-3-5-sonnet)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic kündigt Claude 3.5 Sonnet mit laut eigenen Benchmarks verbesserten Fähigkeiten, doppelter Geschwindigkeit gegenüber Claude 3 Opus, Bildverarbeitung und einem internen Programmierergebnis von 64 Prozent gelöster Aufgaben an. Der Bericht beschreibt außerdem neue Artifacts auf Claude.ai, nennt Sicherheitsprüfungen und Datenschutzgrundsätze und skizziert weitere Funktionen als Zukunftspläne; unabhängige Vergleichsdaten und konkrete Ergebnisse der externen Sicherheitsprüfung werden nicht ausgeführt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 51 % | 77 / 96 % | – | 97 / 99 % | 51 / 76 % | 70 / 84 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 51 % | 66 / 92 % | – | 97 / 99 % | 51 / 74 % | 46 / 68 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 28 / 46 % | 94 / 99 % | – | 93 / 96 % | 40 / 61 % | 46 / 61 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 55 / 91 % | – | 92 / 96 % | 35 / 64 % | 41 / 65 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 48 / 64 % | 92 / 96 % | – | 91 / 93 % | 71 / 83 % | 60 / 71 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 32 / 52 % | 0 / 0 % | – | 87 / 91 % | 51 / 72 % | 59 / 72 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 28 / 93 % | – | 79 / 91 % | 22 / 55 % | 13 / 44 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 20 / 34 % | 37 / 67 % | – | 76 / 86 % | 17 / 38 % | 18 / 41 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 24 / 42 % | 49 / 81 % | – | 75 / 89 % | 43 / 67 % | 39 / 60 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 70 / 96 % | – | 72 / 84 % | 12 / 36 % | 16 / 30 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 26 / 50 % | 72 / 95 % | – | 72 / 89 % | 30 / 54 % | 49 / 68 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 32 / 64 % | – | 72 / 80 % | 20 / 42 % | 11 / 23 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 16 / 49 % | – | 71 / 87 % | 8 / 22 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 61 / 81 % | – | 70 / 83 % | 35 / 58 % | 15 / 29 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 49 % | – | 64 / 79 % | 37 / 62 % | 13 / 29 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 34 / 78 % | – | 64 / 72 % | 21 / 44 % | 14 / 26 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 21 / 45 % | 62 / 90 % | – | 29 / 56 % | 37 / 63 % | 21 / 45 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 38 / 91 % | – | 60 / 74 % | 9 / 24 % | 6 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 34 % | 53 / 87 % | – | 16 / 33 % | 17 / 42 % | 10 / 23 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 27 / 72 % | – | 49 / 70 % | 21 / 50 % | 18 / 39 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 46 / 66 % | 11 / 29 % | 9 / 20 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 41 / 62 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 10 / 50 % | – | 36 / 54 % | 12 / 29 % | 10 / 17 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 31 / 67 % | – | 5 / 17 % | 11 / 26 % | 8 / 17 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 25 / 32 % | 8 / 19 % | 10 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 36 % | 19 / 56 % | – | 1 / 15 % | 9 / 24 % | 9 / 21 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 19 / 62 % | – | 0 / 0 % | 6 / 13 % | 5 / 10 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 28 % | 13 / 29 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 33 % | 11 / 28 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 24 % | 5 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 23 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 9 / 19 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 6 / 17 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 6 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 5 / 23 % | 7 / 15 % | 5 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 6 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 6 / 13 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 3 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 23 % | – | 1 / 6 % | 5 / 13 % | 0 / 0 % |
