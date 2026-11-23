[English](README.md) · [Deutsch](README.de.md)

# Developing Gemini 4 Argon responsibly and safely

Report Q000095 · Source blog.google · Date 2026-10-13 · [Open original](https://blog.google/innovation-and-ai/technology/safety-security/gemini-4-model-safety-security/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google stellt Gemini 4 Argon als leistungsfähigeres Modell für Cybersicherheit und andere komplexe Aufgaben vor und beschreibt Schutzmaßnahmen gegen Missbrauch, Fehlanpassung und Prompt Injection. Die genannten Testergebnisse und Beispiele stammen aus Googles eigener Darstellung; der Beitrag räumt ein, dass seltene Fehltritte bei sehr vielen Aufgaben weiterhin vorkommen können.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 60 % | 95 / 98 % | 100 / 100 % | 74 / 87 % | 72 / 84 % | 80 / 87 % | 64 / 83 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 51 / 67 % | 99 / 100 % | 100 / 100 % | 85 / 91 % | 75 / 86 % | 85 / 91 % | 90 / 94 % | 49 / 69 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 58 / 71 % | 98 / 100 % | 100 / 100 % | 88 / 93 % | 81 / 91 % | 88 / 93 % | 85 / 93 % | 57 / 74 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 66 / 80 % | 97 / 99 % | 100 / 100 % | 89 / 94 % | 80 / 90 % | 80 / 87 % | 91 / 96 % | 50 / 73 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 46 / 62 % | 82 / 94 % | 99 / 100 % | 41 / 58 % | 41 / 61 % | 74 / 84 % | 61 / 79 % | 63 / 82 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 50 / 66 % | 95 / 97 % | 99 / 100 % | 89 / 93 % | 78 / 88 % | 94 / 96 % | 75 / 86 % | 31 / 55 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 34 / 53 % | 94 / 98 % | 98 / 99 % | 81 / 90 % | 29 / 48 % | 66 / 77 % | 73 / 82 % | 45 / 66 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 30 / 51 % | 97 / 99 % | 82 / 96 % | 66 / 82 % | 23 / 44 % | 48 / 66 % | 25 / 44 % | 52 / 74 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 41 % | 57 / 89 % | 92 / 96 % | 36 / 60 % | 10 / 18 % | 32 / 49 % | 7 / 18 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 38 / 71 % | 87 / 93 % | 10 / 26 % | 3 / 9 % | 9 / 14 % | 0 / 0 % | 18 / 36 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 84 / 93 % | 45 / 69 % | 10 / 20 % | 9 / 17 % | 3 / 9 % | 18 / 40 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 30 / 45 % | 50 / 80 % | 82 / 93 % | 55 / 77 % | 11 / 25 % | 26 / 41 % | 15 / 35 % | 27 / 54 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 82 / 98 % | 62 / 78 % | 17 / 38 % | 6 / 13 % | 11 / 25 % | 2 / 7 % | 13 / 32 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 39 / 58 % | 66 / 88 % | 74 / 86 % | 79 / 88 % | 64 / 79 % | 81 / 87 % | 74 / 82 % | 32 / 56 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 54 / 89 % | 71 / 89 % | 22 / 42 % | 11 / 26 % | 16 / 26 % | 5 / 13 % | 35 / 60 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 57 / 87 % | 15 / 43 % | 19 / 43 % | 2 / 7 % | 12 / 25 % | 1 / 5 % | 27 / 49 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 40 % | 47 / 88 % | 24 / 48 % | 15 / 38 % | 6 / 21 % | 16 / 34 % | 1 / 7 % | 16 / 37 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 24 % | 0 / 0 % | 46 / 78 % | 12 / 33 % | 4 / 10 % | 6 / 13 % | 0 / 4 % | 5 / 17 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 18 / 30 % | 32 / 88 % | 39 / 55 % | 23 / 47 % | 5 / 12 % | 13 / 22 % | 1 / 4 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 15 / 50 % | 37 / 58 % | 9 / 25 % | 4 / 10 % | 11 / 19 % | 0 / 2 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 58 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 15 / 53 % | 34 / 55 % | 12 / 33 % | 4 / 9 % | 18 / 30 % | 9 / 20 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 24 % | 33 / 85 % | 13 / 55 % | 16 / 36 % | 4 / 11 % | 9 / 22 % | 1 / 7 % | 16 / 39 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 30 / 51 % | 8 / 18 % | 5 / 11 % | 11 / 20 % | 0 / 1 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 30 / 89 % | 1 / 6 % | 6 / 15 % | 3 / 8 % | 0 / 0 % | 0 / 2 % | 18 / 39 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 29 / 49 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 28 / 40 % | 12 / 36 % | 4 / 13 % | 17 / 36 % | 1 / 5 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 42 % | 16 / 40 % | 17 / 39 % | 10 / 21 % | 12 / 24 % | 1 / 6 % | 26 / 48 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 19 / 42 % | 17 / 44 % | 3 / 8 % | 12 / 23 % | 1 / 4 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 42 % | 5 / 13 % | 10 / 19 % | 2 / 8 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 1 / 10 % | 0 / 0 % | 4 / 7 % | 6 / 12 % | 0 / 0 % | 16 / 36 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 37 % | 0 / 0 % | 2 / 9 % | 9 / 24 % | 3 / 11 % | 14 / 26 % | 0 / 2 % | 15 / 37 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 9 / 47 % | 0 / 0 % | 7 / 18 % | 3 / 9 % | 6 / 13 % | 0 / 0 % | 15 / 33 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 12 / 52 % | 0 / 0 % | 6 / 12 % | 0 / 2 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 11 / 63 % | 8 / 16 % | 8 / 22 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 6 / 10 % | 10 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 4 / 53 % | 2 / 14 % | 7 / 19 % | 2 / 5 % | 0 / 0 % | 0 / 0 % | 3 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 3 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 4 / 8 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 3 / 6 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
