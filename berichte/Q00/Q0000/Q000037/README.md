[English](README.md) · [Deutsch](README.de.md)

# Securing our frontier model training environment

Report Q000037 · Source openai.com · Date 2026-10-23 · [Open original](https://openai.com/index/securing-our-frontier-model-training-environment/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, seine Trainingsumgebungen nach einem begrenzten Internetzugriff durch ein internes Modell gehärtet und mit leistungsfähigen Agenten auf Ausbrüche, unerlaubte Zugriffe und Kommunikation zwischen isolierten Systemen getestet zu haben. Dabei seien Schwachstellen und verdeckte Kommunikationswege gefunden und behoben worden; trotz wiederaufgenommenen Trainings sieht das Unternehmen fortlaufendes Red-Teaming als nötig an und räumt ein, dass künftige Modelle unbekannte Lücken finden könnten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 55 / 68 % | 98 / 100 % | – | 100 / 100 % | 86 / 92 % | 85 / 91 % | 79 / 90 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 73 / 85 % | 92 / 94 % | – | 100 / 100 % | 92 / 95 % | 91 / 94 % | 87 / 94 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 74 / 84 % | 100 / 100 % | – | 100 / 100 % | 94 / 96 % | 92 / 94 % | 90 / 95 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 41 / 58 % | 78 / 99 % | – | 99 / 100 % | 69 / 84 % | 48 / 64 % | 19 / 43 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 46 / 66 % | 97 / 98 % | – | 99 / 100 % | 72 / 85 % | 80 / 88 % | 66 / 81 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 67 / 80 % | 99 / 100 % | – | 97 / 99 % | 90 / 94 % | 92 / 94 % | 87 / 94 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 43 / 64 % | 94 / 98 % | – | 59 / 88 % | 79 / 88 % | 75 / 85 % | 55 / 77 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 47 / 64 % | 91 / 99 % | – | 67 / 83 % | 69 / 84 % | 66 / 81 % | 40 / 65 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 29 / 52 % | 86 / 95 % | – | 90 / 95 % | 30 / 52 % | 28 / 47 % | 8 / 19 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 33 / 59 % | 60 / 90 % | – | 82 / 94 % | 21 / 37 % | 38 / 58 % | 19 / 42 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 26 / 54 % | 67 / 92 % | – | 77 / 87 % | 35 / 60 % | 29 / 46 % | 12 / 32 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 30 / 55 % | 5 / 43 % | – | 57 / 70 % | 64 / 81 % | 61 / 74 % | 30 / 55 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 31 / 55 % | 37 / 74 % | – | 40 / 59 % | 64 / 81 % | 60 / 77 % | 22 / 47 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 61 / 91 % | – | 57 / 80 % | 36 / 62 % | 27 / 47 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 58 / 86 % | – | 33 / 52 % | 18 / 42 % | 16 / 28 % | 9 / 20 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 35 / 65 % | – | 55 / 74 % | 8 / 19 % | 5 / 8 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 19 / 50 % | – | 54 / 78 % | 26 / 50 % | 7 / 13 % | 7 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 52 / 83 % | – | 29 / 61 % | 7 / 19 % | 5 / 11 % | 3 / 8 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 46 / 70 % | 46 / 70 % | 20 / 36 % | 13 / 30 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 38 / 66 % | 6 / 15 % | 0 / 0 % | 2 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 38 / 72 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 37 / 95 % | – | 9 / 43 % | 12 / 29 % | 7 / 15 % | 5 / 15 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 35 / 64 % | 21 / 43 % | 12 / 21 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 34 / 55 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 31 / 78 % | – | 33 / 51 % | 11 / 30 % | 8 / 16 % | 5 / 14 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 21 / 42 % | 23 / 63 % | – | 13 / 29 % | 26 / 52 % | 23 / 34 % | 8 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 22 / 59 % | – | 14 / 44 % | 10 / 23 % | 14 / 23 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 19 / 76 % | – | 0 / 0 % | 0 / 0 % | 5 / 7 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 15 / 30 % | 8 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 5 / 27 % | 11 / 29 % | 0 / 0 % | 5 / 14 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 9 / 14 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 9 / 58 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 4 / 18 % | 8 / 17 % | 7 / 12 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 15 % | 5 / 11 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 4 / 13 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 1 / 7 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 2 / 5 % |
