[English](README.md) · [Deutsch](README.de.md)

# Introducing Claude Sonnet 4.5

Report Q002806 · Source anthropic.com · Date 2025-09-29 · [Open original](https://www.anthropic.com/news/claude-sonnet-4-5)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic präsentiert Claude Sonnet 4.5 als leistungsstarkes Modell für Coding, Agenten und Computeraufgaben und nennt unter anderem 77,2 Prozent bei SWE-bench Verified sowie 61,4 Prozent bei OSWorld. Die Benchmarkergebnisse hängen von den beschriebenen Testaufbauten ab; positive Kundenberichte sind keine unabhängige Bestätigung. Anthropic berichtet zudem von verbesserten Sicherheitswerten, weist aber auf mögliche Fehlalarme der Schutzfilter hin, und kündigt begleitende Produktupdates bei gleichbleibendem API-Preis an.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 60 % | 94 / 99 % | 100 / 100 % | 75 / 87 % | 24 / 47 % | 66 / 81 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 24 / 43 % | 82 / 91 % | 99 / 99 % | 68 / 83 % | 13 / 23 % | 65 / 77 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 32 / 57 % | 72 / 91 % | 99 / 100 % | 50 / 75 % | 22 / 41 % | 62 / 78 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 41 / 63 % | 93 / 99 % | 98 / 99 % | 73 / 85 % | 47 / 65 % | 77 / 87 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 36 / 59 % | 88 / 98 % | 94 / 97 % | 52 / 76 % | 25 / 51 % | 25 / 58 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 38 / 63 % | 56 / 80 % | 87 / 94 % | 34 / 58 % | 12 / 28 % | 56 / 71 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 67 / 86 % | 87 / 92 % | 20 / 44 % | 7 / 14 % | 22 / 43 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 31 / 54 % | 57 / 86 % | 85 / 88 % | 62 / 79 % | 13 / 28 % | 58 / 69 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 29 / 53 % | 69 / 95 % | 82 / 93 % | 56 / 76 % | 12 / 29 % | 48 / 65 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 16 / 30 % | 55 / 81 % | 81 / 88 % | 11 / 30 % | 1 / 5 % | 8 / 19 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 25 / 52 % | 77 / 97 % | 32 / 55 % | 37 / 65 % | 8 / 19 % | 23 / 46 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 22 / 44 % | 75 / 85 % | 8 / 24 % | 1 / 5 % | 5 / 9 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 73 / 83 % | 36 / 63 % | 6 / 14 % | 9 / 18 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 44 / 81 % | 71 / 87 % | 8 / 24 % | 2 / 6 % | 7 / 13 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 44 / 78 % | 71 / 81 % | 7 / 20 % | 2 / 7 % | 4 / 11 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 40 % | 63 / 90 % | 29 / 51 % | 15 / 42 % | 3 / 11 % | 16 / 32 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 55 / 71 % | 10 / 30 % | 2 / 6 % | 5 / 11 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 46 / 73 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 31 / 50 % | 24 / 56 % | 26 / 48 % | 40 / 66 % | 8 / 19 % | 26 / 45 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 40 / 56 % | 7 / 18 % | 0 / 2 % | 2 / 6 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 18 / 43 % | 37 / 57 % | 12 / 28 % | 6 / 14 % | 12 / 23 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 15 / 62 % | 30 / 52 % | 14 / 35 % | 3 / 10 % | 8 / 19 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 30 / 43 % | 9 / 22 % | 2 / 5 % | 12 / 23 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 23 / 49 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 65 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 4 / 6 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 46 % | 0 / 0 % | 0 / 0 % | 16 / 40 % | 4 / 9 % | 7 / 15 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 15 / 45 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 5 / 12 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 13 / 40 % | 0 / 0 % | 0 / 0 % | 11 / 33 % | 2 / 8 % | 9 / 22 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 30 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 1 / 4 % | 10 / 20 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 12 % | 11 / 26 % | 3 / 8 % | 5 / 12 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 2 / 6 % | 8 / 17 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 2 % | 6 / 12 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 1 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 2 % | 4 / 9 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 3 / 13 % | 5 / 12 % | 1 / 4 % | 4 / 7 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 2 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 3 % | 4 / 7 % | – | – |
