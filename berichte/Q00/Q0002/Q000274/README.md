[English](README.md) · [Deutsch](README.de.md)

# How we detect frontier model misalignment

Report Q000274 · Source alignment.openai.com · Date 2026-10-29 · [Open original](https://alignment.openai.com/how-we-detect-frontier-model-misalignment)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt ein mehrstufiges Monitoringsystem, das Sicherheitsverstöße und mögliche Fehlanpassungen von KI-Agenten erkennen und rechtzeitige Eingriffe ermöglichen soll. Tests zeigen je nach Fall unterschiedliche Erkennungsraten; der Bericht nennt zugleich Grenzen bei Fehlalarmen, externer menschlicher Prüfung und API-Abdeckung sowie noch offene Verbesserungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 65 / 79 % | 100 / 100 % | 94 / 97 % | – | 88 / 93 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 46 / 66 % | 99 / 100 % | 89 / 94 % | – | 87 / 93 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 63 / 77 % | 98 / 99 % | 98 / 99 % | – | 92 / 95 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 28 / 46 % | 97 / 99 % | 69 / 81 % | – | 84 / 92 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 50 / 69 % | 94 / 100 % | 45 / 78 % | – | 78 / 89 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 57 / 72 % | 92 / 99 % | 87 / 95 % | – | 87 / 93 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 63 / 81 % | 92 / 97 % | 92 / 97 % | – | 90 / 94 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 52 / 69 % | 62 / 91 % | 67 / 86 % | – | 86 / 91 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 82 / 95 % | 21 / 45 % | – | 66 / 83 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 47 / 64 % | 21 / 80 % | 63 / 79 % | – | 76 / 87 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 31 / 49 % | 71 / 93 % | 13 / 32 % | – | 44 / 69 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 70 / 90 % | 43 / 72 % | – | 62 / 80 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 35 / 60 % | 61 / 96 % | 15 / 37 % | – | 28 / 52 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 33 / 50 % | 43 / 76 % | 37 / 64 % | – | 59 / 81 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 38 / 56 % | 58 / 95 % | 20 / 26 % | – | 52 / 74 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 44 / 83 % | 3 / 8 % | – | 7 / 20 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 48 % | 41 / 77 % | 1 / 9 % | – | 15 / 39 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 23 / 51 % | 0 / 0 % | 6 / 17 % | – | 40 / 67 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 13 / 52 % | 3 / 11 % | – | 38 / 63 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 32 / 54 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 83 % | 1 / 6 % | – | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 29 / 75 % | 0 / 1 % | – | 8 / 19 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 29 / 86 % | 1 / 8 % | – | 10 / 26 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 27 / 55 % | 12 / 42 % | 8 / 22 % | – | 29 / 53 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 27 / 60 % | 0 / 2 % | – | 8 / 21 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 24 / 66 % | 0 / 0 % | – | 9 / 23 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 18 / 43 % | 0 / 0 % | 1 / 6 % | – | 12 / 36 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 3 / 60 % | 3 / 13 % | – | 14 / 36 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 10 / 60 % | 1 / 4 % | – | 11 / 28 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 21 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 17 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 7 / 66 % | 0 / 0 % | – | 6 / 13 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 46 % | 0 / 0 % | – | 7 / 16 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 20 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 57 % | 0 / 0 % | – | 4 / 10 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 3 / 39 % | 0 / 0 % | – | 0 / 0 % | – |
