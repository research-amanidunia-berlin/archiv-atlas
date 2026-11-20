[English](README.md) · [Deutsch](README.de.md)

# Strengthening our safeguards with frontier automated red-teaming

Report Q000527 · Source safeguards.anthropic.com · Date 2026-11-12 · [Open original](https://safeguards.anthropic.com/2026/automated-red-teaming/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge findet das interne System Anvil Schwachstellen in Schutzmaßnahmen für biologische, Cyber- und Distillationsrisiken schneller und wirksamer als die verglichenen menschlichen Teams und unterstützt die Weiterentwicklung der Schutzmaßnahmen. Die Ergebnisse stammen aus internen Tests mit besonderen Modell- und Klassifikatorzugängen; weitere Verbesserungen liefen parallel, und die Autoren betonen verbleibende Lücken sowie mögliche künftige Angriffe durch leistungsfähigere offene Modelle.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 60 % | 89 / 95 % | – | 100 / 100 % | 67 / 83 % | 58 / 76 % | 77 / 87 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 59 / 90 % | – | 98 / 99 % | 62 / 78 % | 7 / 20 % | 28 / 48 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 37 / 53 % | 95 / 99 % | – | 97 / 98 % | 64 / 81 % | 18 / 38 % | 56 / 74 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 42 / 62 % | 83 / 95 % | – | 95 / 98 % | 59 / 75 % | 25 / 49 % | 55 / 73 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 59 / 87 % | – | 91 / 94 % | 21 / 45 % | 5 / 12 % | 20 / 40 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 33 / 53 % | 77 / 93 % | – | 47 / 75 % | 57 / 78 % | 6 / 17 % | 40 / 60 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 42 / 64 % | 55 / 84 % | – | 41 / 70 % | 68 / 83 % | 11 / 35 % | 70 / 82 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 26 / 49 % | 46 / 95 % | – | 65 / 75 % | 42 / 69 % | 15 / 35 % | 37 / 57 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 29 / 50 % | 26 / 93 % | – | 61 / 81 % | 60 / 79 % | 11 / 28 % | 34 / 57 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 9 / 52 % | – | 56 / 72 % | 47 / 69 % | 4 / 12 % | 12 / 23 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 50 / 97 % | – | 28 / 55 % | 30 / 61 % | 10 / 24 % | 21 / 41 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 8 / 68 % | – | 49 / 65 % | 22 / 49 % | 7 / 18 % | 16 / 35 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 21 / 48 % | – | 0 / 0 % | 43 / 68 % | 0 / 0 % | 47 / 66 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 36 / 55 % | 47 / 94 % | – | 0 / 0 % | 45 / 69 % | 0 / 0 % | 22 / 52 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 15 / 40 % | 25 / 91 % | – | 47 / 77 % | 24 / 45 % | 3 / 9 % | 16 / 35 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 41 / 88 % | – | 0 / 0 % | 7 / 16 % | 1 / 5 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 40 / 57 % | 23 / 51 % | 6 / 14 % | 9 / 19 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 38 / 53 % | 8 / 23 % | 1 / 5 % | 6 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 2 / 52 % | – | 11 / 23 % | 33 / 55 % | 2 / 10 % | 9 / 20 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 32 / 50 % | 7 / 15 % | 3 / 6 % | 8 / 12 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 31 / 56 % | – | 26 / 50 % | 8 / 21 % | 1 / 4 % | 6 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 28 / 54 % | 0 / 0 % | – | 0 / 0 % | 9 / 30 % | 4 / 10 % | 17 / 34 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 27 / 56 % | 7 / 21 % | 1 / 5 % | 5 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 26 / 93 % | – | 3 / 32 % | 15 / 36 % | 2 / 8 % | 6 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 10 / 75 % | – | 0 / 0 % | 18 / 39 % | 6 / 17 % | 23 / 42 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 19 / 43 % | 15 / 35 % | 0 / 0 % | 10 / 19 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 17 / 51 % | – | 0 / 0 % | 7 / 18 % | 2 / 7 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 33 % | 3 / 10 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 9 / 50 % | – | 13 / 28 % | 12 / 33 % | 2 / 8 % | 6 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 3 / 8 % | 12 / 20 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 24 % | 1 / 2 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 1 / 3 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 1 / 4 % | 6 / 12 % | 1 / 4 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 59 % | – | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 2 / 5 % | 4 / 8 % |
