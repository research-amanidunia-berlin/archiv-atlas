[English](README.md) · [Deutsch](README.de.md)

# Wie wir Fehlausrichtung bei Frontier-Modellen erkennen

Report Q009534 · Source openai.com · Date – · [Open original](https://openai.com/index/how-we-detect-frontier-model-misalignment)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt ein mehrstufiges System, das Fehlverhalten leistungsfähiger KI-Agenten überwachen und bei schweren Sicherheitsfällen eine Reaktion auslösen soll. Der Bericht nennt früh erkannte Vorfälle und laufende Tests, räumt aber Grenzen wie Fehlalarme, Rechenaufwand, mögliche Umgehung und eingeschränkte externe Überwachung ein.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 45 / 63 % | 100 / 100 % | – | 99 / 100 % | 84 / 90 % | 75 / 88 % | 90 / 94 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 62 / 75 % | 100 / 100 % | – | 100 / 100 % | 82 / 90 % | 84 / 92 % | 93 / 95 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 58 / 71 % | 71 / 94 % | – | 100 / 100 % | 86 / 92 % | 71 / 86 % | 88 / 94 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 63 / 80 % | 97 / 99 % | – | 100 / 100 % | 86 / 92 % | 75 / 89 % | 88 / 92 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 69 / 81 % | 99 / 100 % | – | 100 / 100 % | 92 / 95 % | 89 / 95 % | 95 / 97 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 40 / 56 % | 37 / 79 % | – | 96 / 98 % | 74 / 86 % | 24 / 46 % | 73 / 82 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 49 / 67 % | 95 / 100 % | – | 92 / 97 % | 76 / 87 % | 50 / 72 % | 77 / 86 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 54 / 70 % | 68 / 93 % | – | 90 / 96 % | 83 / 90 % | 74 / 87 % | 93 / 95 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 92 / 98 % | – | 93 / 96 % | 69 / 84 % | 44 / 65 % | 56 / 70 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 54 / 88 % | – | 93 / 96 % | 44 / 69 % | 19 / 38 % | 43 / 60 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 70 / 96 % | – | 91 / 94 % | 69 / 83 % | 27 / 50 % | 61 / 74 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 88 / 98 % | – | 44 / 74 % | 48 / 71 % | 24 / 45 % | 51 / 71 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 37 / 54 % | 83 / 99 % | – | 44 / 60 % | 49 / 71 % | 44 / 61 % | 65 / 77 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 51 / 90 % | – | 83 / 93 % | 57 / 79 % | 32 / 54 % | 45 / 66 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 4 / 39 % | – | 58 / 77 % | 32 / 56 % | 9 / 22 % | 14 / 24 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 26 / 48 % | 53 / 87 % | – | 50 / 77 % | 26 / 49 % | 15 / 37 % | 46 / 62 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 53 / 87 % | – | 45 / 66 % | 9 / 23 % | 4 / 9 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 20 / 45 % | 0 / 0 % | – | 21 / 35 % | 38 / 64 % | 16 / 33 % | 49 / 71 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 48 / 84 % | – | 40 / 64 % | 8 / 19 % | 2 / 7 % | 6 / 12 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 27 / 52 % | 18 / 61 % | – | 45 / 61 % | 23 / 44 % | 12 / 28 % | 15 / 27 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 45 / 96 % | – | 1 / 6 % | 0 / 0 % | 4 / 9 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 8 / 60 % | – | 39 / 62 % | 10 / 27 % | 8 / 20 % | 22 / 39 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 46 % | 35 / 91 % | – | 24 / 48 % | 14 / 35 % | 8 / 22 % | 16 / 29 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 34 / 62 % | 6 / 17 % | 3 / 9 % | 5 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 24 / 78 % | – | 26 / 54 % | 6 / 13 % | 1 / 3 % | 12 / 20 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 25 / 79 % | – | 1 / 7 % | 7 / 17 % | 4 / 9 % | 8 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 25 / 96 % | – | 11 / 41 % | 10 / 25 % | 5 / 15 % | 6 / 11 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 23 / 41 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 16 / 38 % | 0 / 0 % | – | 0 / 0 % | 10 / 31 % | 6 / 17 % | 19 / 34 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 17 / 65 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 9 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 15 / 90 % | – | 3 / 25 % | 13 / 33 % | 11 / 25 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 13 / 80 % | – | 15 / 24 % | 7 / 17 % | 5 / 12 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 14 / 47 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 17 % | 4 / 11 % | 10 / 18 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 5 / 11 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 8 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 14 % | 1 / 4 % | 7 / 15 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 66 % | – | 0 / 0 % | 5 / 11 % | 1 / 6 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 12 % | 4 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 3 / 6 % | 0 / 0 % |
