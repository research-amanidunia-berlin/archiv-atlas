[English](README.md) · [Deutsch](README.de.md)

# How we detect frontier model misalignment

Report Q000274 · Source alignment.openai.com · Date 2026-10-29 · [Open original](https://alignment.openai.com/how-we-detect-frontier-model-misalignment)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt ein mehrstufiges Monitoringsystem, das Sicherheitsverstöße und mögliche Fehlanpassungen von KI-Agenten erkennen und rechtzeitige Eingriffe ermöglichen soll. Tests zeigen je nach Fall unterschiedliche Erkennungsraten; der Bericht nennt zugleich Grenzen bei Fehlalarmen, externer menschlicher Prüfung und API-Abdeckung sowie noch offene Verbesserungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 65 / 79 % | 100 / 100 % | – | 88 / 93 % | 88 / 94 % | 91 / 94 % | 94 / 97 % | 68 / 82 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 46 / 66 % | 99 / 100 % | – | 87 / 93 % | 66 / 82 % | 87 / 92 % | 89 / 94 % | 67 / 84 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 63 / 77 % | 98 / 99 % | – | 92 / 95 % | 90 / 95 % | 95 / 97 % | 98 / 99 % | 49 / 73 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 28 / 46 % | 97 / 99 % | – | 84 / 92 % | 44 / 66 % | 87 / 92 % | 69 / 81 % | 56 / 75 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 52 / 69 % | 62 / 91 % | – | 86 / 91 % | 85 / 93 % | 94 / 96 % | 67 / 86 % | 25 / 51 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 50 / 69 % | 94 / 100 % | – | 78 / 89 % | 65 / 79 % | 75 / 86 % | 45 / 78 % | 36 / 57 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 57 / 72 % | 92 / 99 % | – | 87 / 93 % | 80 / 91 % | 88 / 93 % | 87 / 95 % | 56 / 75 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 63 / 81 % | 92 / 97 % | – | 90 / 94 % | 70 / 85 % | 89 / 93 % | 92 / 97 % | 44 / 71 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 82 / 95 % | – | 66 / 83 % | 32 / 52 % | 38 / 56 % | 21 / 45 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 47 / 64 % | 21 / 80 % | – | 76 / 87 % | 15 / 34 % | 69 / 79 % | 63 / 79 % | 38 / 59 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 31 / 49 % | 71 / 93 % | – | 44 / 69 % | 22 / 42 % | 49 / 65 % | 13 / 32 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 70 / 90 % | – | 62 / 80 % | 24 / 44 % | 46 / 66 % | 43 / 72 % | 45 / 70 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 38 / 56 % | 58 / 95 % | – | 52 / 74 % | 49 / 63 % | 65 / 76 % | 20 / 26 % | 11 / 26 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 35 / 60 % | 61 / 96 % | – | 28 / 52 % | 19 / 41 % | 43 / 64 % | 15 / 37 % | 46 / 66 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 33 / 50 % | 43 / 76 % | – | 59 / 81 % | 41 / 62 % | 35 / 59 % | 37 / 64 % | 20 / 40 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 23 / 51 % | 0 / 0 % | – | 40 / 67 % | 21 / 40 % | 51 / 68 % | 6 / 17 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 3 / 39 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 49 / 68 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 44 / 83 % | – | 7 / 20 % | 3 / 8 % | 6 / 12 % | 3 / 8 % | 12 / 28 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 48 % | 41 / 77 % | – | 15 / 39 % | 9 / 27 % | 19 / 38 % | 1 / 9 % | 18 / 43 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 7 / 66 % | – | 6 / 13 % | 2 / 5 % | 12 / 19 % | 0 / 0 % | 40 / 62 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 13 / 52 % | – | 38 / 63 % | 10 / 23 % | 14 / 26 % | 3 / 11 % | 15 / 34 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 32 / 54 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 83 % | – | 0 / 0 % | 4 / 9 % | 0 / 0 % | 1 / 6 % | 18 / 37 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 29 / 75 % | – | 8 / 19 % | 3 / 7 % | 8 / 15 % | 0 / 1 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 29 / 86 % | – | 10 / 26 % | 6 / 21 % | 6 / 16 % | 1 / 8 % | 8 / 31 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 27 / 55 % | 12 / 42 % | – | 29 / 53 % | 14 / 30 % | 15 / 28 % | 8 / 22 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 27 / 60 % | – | 8 / 21 % | 6 / 14 % | 0 / 0 % | 0 / 2 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 24 / 66 % | – | 9 / 23 % | 5 / 12 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 18 / 43 % | 0 / 0 % | – | 12 / 36 % | 8 / 22 % | 20 / 33 % | 1 / 6 % | 14 / 34 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 10 / 60 % | – | 11 / 28 % | 5 / 12 % | 16 / 30 % | 1 / 4 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 3 / 60 % | – | 14 / 36 % | 9 / 19 % | 0 / 0 % | 3 / 13 % | 8 / 26 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | 0 / 0 % | 11 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 8 / 21 % | 4 / 9 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 13 % | 6 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 3 / 6 % | 8 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 8 / 17 % | 0 / 4 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 46 % | – | 7 / 16 % | 2 / 6 % | 7 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 7 / 20 % | 4 / 11 % | 0 / 0 % | 0 / 0 % | 3 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 3 / 6 % | 0 / 0 % | 0 / 0 % | 6 / 21 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 57 % | – | 4 / 10 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
