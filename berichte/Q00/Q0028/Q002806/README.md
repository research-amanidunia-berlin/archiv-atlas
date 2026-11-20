[English](README.md) · [Deutsch](README.de.md)

# Introducing Claude Sonnet 4.5

Report Q002806 · Source anthropic.com · Date 2025-09-29 · [Open original](https://www.anthropic.com/news/claude-sonnet-4-5)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic präsentiert Claude Sonnet 4.5 als leistungsstarkes Modell für Coding, Agenten und Computeraufgaben und nennt unter anderem 77,2 Prozent bei SWE-bench Verified sowie 61,4 Prozent bei OSWorld. Die Benchmarkergebnisse hängen von den beschriebenen Testaufbauten ab; positive Kundenberichte sind keine unabhängige Bestätigung. Anthropic berichtet zudem von verbesserten Sicherheitswerten, weist aber auf mögliche Fehlalarme der Schutzfilter hin, und kündigt begleitende Produktupdates bei gleichbleibendem API-Preis an.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 60 % | 94 / 99 % | – | 100 / 100 % | 75 / 87 % | 66 / 81 % | 24 / 47 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 24 / 43 % | 82 / 91 % | – | 99 / 99 % | 68 / 83 % | 65 / 77 % | 13 / 23 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 32 / 57 % | 72 / 91 % | – | 99 / 100 % | 50 / 75 % | 62 / 78 % | 22 / 41 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 41 / 63 % | 93 / 99 % | – | 98 / 99 % | 73 / 85 % | 77 / 87 % | 47 / 65 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 36 / 59 % | 88 / 98 % | – | 94 / 97 % | 52 / 76 % | 25 / 58 % | 25 / 51 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 38 / 63 % | 56 / 80 % | – | 87 / 94 % | 34 / 58 % | 56 / 71 % | 12 / 28 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 67 / 86 % | – | 87 / 92 % | 20 / 44 % | 22 / 43 % | 7 / 14 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 31 / 54 % | 57 / 86 % | – | 85 / 88 % | 62 / 79 % | 58 / 69 % | 13 / 28 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 29 / 53 % | 69 / 95 % | – | 82 / 93 % | 56 / 76 % | 48 / 65 % | 12 / 29 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 16 / 30 % | 55 / 81 % | – | 81 / 88 % | 11 / 30 % | 8 / 19 % | 1 / 5 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 25 / 52 % | 77 / 97 % | – | 32 / 55 % | 37 / 65 % | 23 / 46 % | 8 / 19 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 22 / 44 % | – | 75 / 85 % | 8 / 24 % | 5 / 9 % | 1 / 5 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 73 / 83 % | 36 / 63 % | 9 / 18 % | 6 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 44 / 81 % | – | 71 / 87 % | 8 / 24 % | 7 / 13 % | 2 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 44 / 78 % | – | 71 / 81 % | 7 / 20 % | 4 / 11 % | 2 / 7 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 40 % | 63 / 90 % | – | 29 / 51 % | 15 / 42 % | 16 / 32 % | 3 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 55 / 71 % | 10 / 30 % | 5 / 11 % | 2 / 6 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 46 / 73 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 1 / 4 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 31 / 50 % | 24 / 56 % | – | 26 / 48 % | 40 / 66 % | 26 / 45 % | 8 / 19 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 40 / 56 % | 7 / 18 % | 2 / 6 % | 0 / 2 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 18 / 43 % | – | 37 / 57 % | 12 / 28 % | 12 / 23 % | 6 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 15 / 62 % | – | 30 / 52 % | 14 / 35 % | 8 / 19 % | 3 / 10 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 30 / 43 % | 9 / 22 % | 12 / 23 % | 2 / 5 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 23 / 49 % | 0 / 0 % | 0 / 2 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 65 % | – | 0 / 0 % | 6 / 15 % | 4 / 6 % | 1 / 3 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 46 % | 0 / 0 % | – | 0 / 0 % | 16 / 40 % | 7 / 15 % | 4 / 9 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 15 / 45 % | – | 0 / 0 % | 5 / 11 % | 5 / 12 % | 1 / 3 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 13 / 40 % | 0 / 0 % | – | 0 / 0 % | 11 / 33 % | 9 / 22 % | 2 / 8 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 30 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 10 / 20 % | 1 / 4 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 1 / 12 % | 11 / 26 % | 5 / 12 % | 3 / 8 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 22 % | 8 / 17 % | 2 / 6 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 22 % | 6 / 12 % | 0 / 2 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 5 / 10 % | 0 / 1 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 4 / 9 % | 0 / 2 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 1 / 3 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 0 / 0 % | 1 / 6 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 3 / 13 % | 5 / 12 % | 4 / 7 % | 1 / 4 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 2 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 4 / 7 % | 1 / 3 % |
