[English](README.md) · [Deutsch](README.de.md)

# Patterns and problems in multiagent systems

Report Q001678 · Source anthropic.com · Date 2026-08-13 · [Open original](https://www.anthropic.com/research/multiagent-systems)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropics frühe Experimente zeigen laut Bericht, dass koordinierte Agenten bei manchen Aufgaben ergänzende Ergebnisse erzielen, zugleich aber an Konflikten, Gleichförmigkeit, übermäßigem Vertrauen und mangelnder Weitergabe entscheidender Informationen scheitern können. Die Autoren folgern, dass stärkere Modelle nicht automatisch besser kooperieren und dass geeignete soziale und technische Regeln noch entwickelt werden müssen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 53 / 70 % | 100 / 100 % | 99 / 100 % | 82 / 90 % | 49 / 70 % | 79 / 89 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 91 / 96 % | 100 / 100 % | 100 / 100 % | 96 / 97 % | 94 / 96 % | 95 / 97 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 72 / 93 % | 98 / 99 % | 30 / 60 % | 8 / 29 % | 31 / 59 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 61 % | 88 / 98 % | 96 / 98 % | 63 / 83 % | 26 / 58 % | 48 / 76 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 28 / 55 % | 78 / 92 % | 95 / 97 % | 74 / 87 % | 26 / 51 % | 67 / 82 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 35 / 65 % | 93 / 98 % | 85 / 93 % | 57 / 77 % | 7 / 28 % | 30 / 56 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 52 / 81 % | 75 / 86 % | 16 / 41 % | 5 / 16 % | 13 / 31 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 64 / 92 % | 72 / 88 % | 14 / 41 % | 3 / 13 % | 8 / 28 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 19 / 84 % | 62 / 76 % | 18 / 42 % | 2 / 7 % | 6 / 13 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 44 % | 59 / 86 % | 42 / 72 % | 23 / 50 % | 4 / 19 % | 15 / 35 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 56 % | 39 / 88 % | 52 / 66 % | 31 / 61 % | 6 / 20 % | 20 / 40 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 48 / 97 % | 30 / 72 % | 18 / 50 % | 2 / 11 % | 8 / 22 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 19 / 47 % | 28 / 97 % | 48 / 84 % | 24 / 52 % | 3 / 11 % | 6 / 18 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 19 / 47 % | 48 / 98 % | 26 / 61 % | 30 / 57 % | 7 / 26 % | 24 / 49 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 41 / 85 % | 11 / 51 % | 18 / 45 % | 5 / 12 % | 6 / 15 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 38 / 80 % | 20 / 52 % | 10 / 29 % | 3 / 11 % | 5 / 14 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 36 / 77 % | 0 / 0 % | 6 / 15 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 34 / 87 % | 0 / 0 % | 6 / 16 % | 2 / 10 % | 4 / 9 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 30 / 84 % | 0 / 0 % | 9 / 28 % | 1 / 7 % | 4 / 9 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 30 / 93 % | 0 / 0 % | 10 / 27 % | 1 / 7 % | 5 / 18 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 15 / 68 % | 29 / 67 % | 8 / 30 % | 1 / 11 % | 4 / 14 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 24 / 56 % | 10 / 49 % | 13 / 38 % | 1 / 6 % | 5 / 13 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 22 / 55 % | 23 / 51 % | 19 / 46 % | 1 / 5 % | 8 / 17 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 18 / 67 % | 16 / 51 % | 6 / 14 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 16 / 69 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 3 / 7 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 39 % | 3 / 9 % | 7 / 14 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 15 / 64 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 6 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 13 / 80 % | 0 / 0 % | 9 / 22 % | 1 / 5 % | 6 / 10 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 33 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 12 / 90 % | 2 / 18 % | 8 / 25 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 2 / 9 % | 10 / 26 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 10 / 69 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 6 / 12 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 1 / 6 % | 3 / 9 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 8 / 15 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 7 % | 3 / 6 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 7 / 66 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 4 / 8 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 3 % | 5 / 14 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
