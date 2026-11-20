[English](README.md) · [Deutsch](README.de.md)

# Developing Gemini 4 Argon responsibly and safely

Report Q000095 · Source blog.google · Date 2026-10-13 · [Open original](https://blog.google/innovation-and-ai/technology/safety-security/gemini-4-model-safety-security/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google stellt Gemini 4 Argon als leistungsfähigeres Modell für Cybersicherheit und andere komplexe Aufgaben vor und beschreibt Schutzmaßnahmen gegen Missbrauch, Fehlanpassung und Prompt Injection. Die genannten Testergebnisse und Beispiele stammen aus Googles eigener Darstellung; der Beitrag räumt ein, dass seltene Fehltritte bei sehr vielen Aufgaben weiterhin vorkommen können.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 60 % | 95 / 98 % | 64 / 83 % | 100 / 100 % | 74 / 87 % | 80 / 87 % | 72 / 84 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 51 / 67 % | 99 / 100 % | 90 / 94 % | 100 / 100 % | 85 / 91 % | 85 / 91 % | 75 / 86 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 58 / 71 % | 98 / 100 % | 85 / 93 % | 100 / 100 % | 88 / 93 % | 88 / 93 % | 81 / 91 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 66 / 80 % | 97 / 99 % | 91 / 96 % | 100 / 100 % | 89 / 94 % | 80 / 87 % | 80 / 90 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 46 / 62 % | 82 / 94 % | 61 / 79 % | 99 / 100 % | 41 / 58 % | 74 / 84 % | 41 / 61 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 50 / 66 % | 95 / 97 % | 75 / 86 % | 99 / 100 % | 89 / 93 % | 94 / 96 % | 78 / 88 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 34 / 53 % | 94 / 98 % | 73 / 82 % | 98 / 99 % | 81 / 90 % | 66 / 77 % | 29 / 48 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 30 / 51 % | 97 / 99 % | 25 / 44 % | 82 / 96 % | 66 / 82 % | 48 / 66 % | 23 / 44 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 41 % | 57 / 89 % | 7 / 18 % | 92 / 96 % | 36 / 60 % | 32 / 49 % | 10 / 18 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 38 / 71 % | 0 / 0 % | 87 / 93 % | 10 / 26 % | 9 / 14 % | 3 / 9 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 3 / 9 % | 84 / 93 % | 45 / 69 % | 9 / 17 % | 10 / 20 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 30 / 45 % | 50 / 80 % | 15 / 35 % | 82 / 93 % | 55 / 77 % | 26 / 41 % | 11 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 82 / 98 % | 2 / 7 % | 62 / 78 % | 17 / 38 % | 11 / 25 % | 6 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 39 / 58 % | 66 / 88 % | 74 / 82 % | 74 / 86 % | 79 / 88 % | 81 / 87 % | 64 / 79 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 54 / 89 % | 5 / 13 % | 71 / 89 % | 22 / 42 % | 16 / 26 % | 11 / 26 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 57 / 87 % | 1 / 5 % | 15 / 43 % | 19 / 43 % | 12 / 25 % | 2 / 7 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 40 % | 47 / 88 % | 1 / 7 % | 24 / 48 % | 15 / 38 % | 16 / 34 % | 6 / 21 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 24 % | 0 / 0 % | 0 / 4 % | 46 / 78 % | 12 / 33 % | 6 / 13 % | 4 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 18 / 30 % | 32 / 88 % | 1 / 4 % | 39 / 55 % | 23 / 47 % | 13 / 22 % | 5 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 15 / 50 % | 0 / 2 % | 37 / 58 % | 9 / 25 % | 11 / 19 % | 4 / 10 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 58 % | 0 / 0 % | 1 / 4 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 15 / 53 % | 9 / 20 % | 34 / 55 % | 12 / 33 % | 18 / 30 % | 4 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 24 % | 33 / 85 % | 1 / 7 % | 13 / 55 % | 16 / 36 % | 9 / 22 % | 4 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 30 / 51 % | 8 / 18 % | 11 / 20 % | 5 / 11 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 30 / 89 % | 0 / 2 % | 1 / 6 % | 6 / 15 % | 0 / 0 % | 3 / 8 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 28 / 40 % | 12 / 36 % | 17 / 36 % | 4 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 19 / 42 % | 17 / 44 % | 12 / 23 % | 3 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 2 / 8 % | 0 / 0 % | 19 / 42 % | 10 / 19 % | 5 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 42 % | 1 / 6 % | 16 / 40 % | 17 / 39 % | 12 / 24 % | 10 / 21 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 37 % | 0 / 0 % | 0 / 2 % | 2 / 9 % | 9 / 24 % | 14 / 26 % | 3 / 11 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 12 / 52 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 5 / 9 % | 0 / 2 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 11 / 63 % | 0 / 0 % | 8 / 16 % | 8 / 22 % | 0 / 0 % | 5 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 10 / 18 % | 6 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 9 / 47 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 6 / 13 % | 3 / 9 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 4 / 53 % | 0 / 0 % | 2 / 14 % | 7 / 19 % | 0 / 0 % | 2 / 5 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 3 / 6 % | 1 / 3 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 10 % | 0 / 0 % | 6 / 12 % | 4 / 7 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 4 / 8 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 4 / 8 % | 3 / 6 % |
