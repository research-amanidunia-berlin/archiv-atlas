[English](README.md) · [Deutsch](README.de.md)

# Operator System Card

Report Q009104 · Source openai.com · Date 2025-01-23 · [Open original](https://openai.com/index/operator-system-card/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Die Systemkarte beschreibt OpenAIs Tests zu Operator und Schutzmaßnahmen wie Ablehnungen, Bestätigungsabfragen und Überwachung. OpenAI berichtet von niedrigen Erfolgswerten in den untersuchten Risikoaufgaben, zugleich aber auch von Modellfehlern und verbleibender Prompt-Injection-Anfälligkeit; die Testergebnisse garantierten keine entsprechende Sicherheit im realen Einsatz.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 42 / 62 % | 98 / 100 % | – | 100 / 100 % | 70 / 84 % | 66 / 82 % | 81 / 89 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 39 / 58 % | 100 / 100 % | – | 99 / 100 % | 77 / 87 % | 33 / 59 % | 69 / 83 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 60 / 74 % | 96 / 99 % | – | 100 / 100 % | 89 / 93 % | 62 / 81 % | 84 / 91 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 72 / 84 % | 96 / 97 % | – | 100 / 100 % | 92 / 95 % | 77 / 90 % | 89 / 93 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 49 / 67 % | 99 / 100 % | – | 95 / 98 % | 74 / 86 % | 20 / 42 % | 68 / 80 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 52 / 70 % | 90 / 98 % | – | 99 / 100 % | 71 / 86 % | 35 / 62 % | 59 / 73 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 41 / 58 % | 99 / 100 % | – | 97 / 99 % | 80 / 90 % | 11 / 26 % | 61 / 72 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 38 / 51 % | 95 / 98 % | – | 99 / 100 % | 49 / 72 % | 33 / 55 % | 51 / 70 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 97 / 100 % | – | 98 / 99 % | 45 / 70 % | 39 / 63 % | 39 / 54 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 54 / 70 % | 72 / 91 % | – | 98 / 99 % | 88 / 93 % | 63 / 81 % | 87 / 92 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 33 / 52 % | 97 / 98 % | – | 94 / 96 % | 36 / 62 % | 10 / 20 % | 30 / 47 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 29 / 50 % | 93 / 98 % | – | 96 / 97 % | 75 / 87 % | 25 / 48 % | 69 / 83 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 45 / 60 % | 78 / 93 % | – | 95 / 98 % | 65 / 82 % | 13 / 32 % | 48 / 61 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 48 / 83 % | – | 93 / 96 % | 48 / 71 % | 8 / 20 % | 8 / 16 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 30 / 53 % | 75 / 98 % | – | 59 / 77 % | 74 / 86 % | 18 / 36 % | 77 / 86 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 27 / 61 % | – | 77 / 87 % | 8 / 20 % | 3 / 8 % | 7 / 13 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 28 / 57 % | 0 / 0 % | – | 71 / 79 % | 24 / 52 % | 5 / 15 % | 28 / 49 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 31 / 83 % | – | 62 / 77 % | 15 / 31 % | 8 / 17 % | 20 / 31 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 11 / 62 % | – | 57 / 70 % | 23 / 48 % | 6 / 14 % | 29 / 46 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 57 / 76 % | – | 55 / 67 % | 19 / 40 % | 6 / 11 % | 15 / 25 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 55 / 79 % | – | 1 / 5 % | 7 / 16 % | 2 / 8 % | 6 / 13 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 48 / 73 % | 10 / 30 % | 4 / 11 % | 6 / 14 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 15 / 23 % | 47 / 76 % | – | 32 / 56 % | 12 / 32 % | 3 / 9 % | 9 / 22 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 40 / 67 % | – | 15 / 41 % | 15 / 35 % | 1 / 4 % | 10 / 25 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 40 / 86 % | – | 0 / 0 % | 6 / 16 % | 3 / 8 % | 8 / 16 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 33 / 67 % | – | 7 / 16 % | 9 / 24 % | 6 / 13 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 31 / 55 % | 21 / 46 % | 4 / 11 % | 12 / 28 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 29 / 79 % | – | 17 / 34 % | 17 / 38 % | 9 / 21 % | 12 / 22 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 27 / 55 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 26 / 68 % | – | 3 / 24 % | 9 / 21 % | 4 / 10 % | 6 / 13 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 26 / 68 % | – | 0 / 0 % | 6 / 13 % | 2 / 6 % | 6 / 11 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 21 / 46 % | 5 / 12 % | 8 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 26 % | 3 / 9 % | 9 / 18 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 10 / 29 % | 8 / 19 % | 4 / 11 % | 11 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 35 % | – | 0 / 0 % | 8 / 17 % | 1 / 6 % | 9 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 26 % | 1 / 5 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 2 / 5 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 17 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 8 % | 6 / 11 % |
