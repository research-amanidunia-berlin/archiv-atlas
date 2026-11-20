[English](README.md) · [Deutsch](README.de.md)

# Gemini 4 Carbon: our next frontier model

Report Q000108 · Source blog.google · Date 2026-10-28 · [Open original](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-carbon/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google beschreibt Gemini 4 Carbon als leistungsfähigeres Modell für langfristige Programmieraufgaben und Cybersicherheitsarbeit und nennt dafür hohe Benchmarkwerte sowie Verbesserungen bei internen Sicherheitstests. Diese Ergebnisse und Vergleiche sind Angaben des Unternehmens; der Bericht erläutert die Methodik der internen Tests nur begrenzt. Der Zugang soll zunächst ausgewählten Cyberabwehr-Fachleuten offenstehen und danach schrittweise erweitert werden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 63 / 75 % | 98 / 100 % | 91 / 95 % | 99 / 100 % | 76 / 86 % | 63 / 77 % | 82 / 88 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 37 / 56 % | 87 / 94 % | 41 / 63 % | 99 / 100 % | 76 / 87 % | 58 / 75 % | 79 / 88 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 41 / 59 % | 93 / 97 % | 58 / 71 % | 99 / 100 % | 69 / 84 % | 58 / 74 % | 60 / 76 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 55 % | 94 / 97 % | 45 / 65 % | 97 / 99 % | 56 / 77 % | 50 / 71 % | 68 / 81 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 56 % | 78 / 95 % | 46 / 70 % | 97 / 98 % | 69 / 84 % | 31 / 54 % | 68 / 82 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 76 / 89 % | 7 / 19 % | 88 / 92 % | 30 / 56 % | 8 / 17 % | 25 / 44 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 29 / 48 % | 46 / 77 % | 33 / 52 % | 80 / 93 % | 53 / 73 % | 15 / 32 % | 36 / 57 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 51 / 80 % | 2 / 8 % | 77 / 87 % | 11 / 31 % | 3 / 9 % | 8 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 21 / 43 % | 75 / 92 % | 8 / 14 % | 57 / 70 % | 46 / 68 % | 13 / 33 % | 43 / 60 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 20 / 54 % | 1 / 3 % | 75 / 83 % | 11 / 30 % | 1 / 5 % | 7 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 31 / 58 % | 0 / 0 % | 70 / 84 % | 8 / 22 % | 2 / 7 % | 6 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 41 % | 39 / 69 % | 12 / 25 % | 69 / 80 % | 51 / 72 % | 11 / 25 % | 32 / 50 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 21 / 43 % | 65 / 92 % | 3 / 11 % | 26 / 51 % | 28 / 57 % | 8 / 22 % | 15 / 39 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 7 / 17 % | 59 / 75 % | 44 / 67 % | 9 / 20 % | 11 / 24 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 56 / 66 % | 7 / 21 % | 3 / 10 % | 5 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 15 / 38 % | 3 / 11 % | 55 / 73 % | 18 / 42 % | 6 / 15 % | 12 / 23 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 35 / 88 % | 0 / 0 % | 50 / 72 % | 9 / 28 % | 2 / 9 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 21 / 48 % | 37 / 64 % | 20 / 31 % | 48 / 60 % | 38 / 61 % | 12 / 28 % | 16 / 29 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 37 / 66 % | 1 / 4 % | 0 / 0 % | 11 / 29 % | 4 / 10 % | 6 / 13 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 21 / 37 % | 36 / 69 % | 4 / 10 % | 10 / 17 % | 28 / 51 % | 9 / 19 % | 11 / 22 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 34 / 57 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 35 % | 26 / 68 % | 2 / 10 % | 14 / 29 % | 19 / 42 % | 8 / 21 % | 20 / 40 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 8 % | 26 / 41 % | 9 / 27 % | 4 / 11 % | 6 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 15 / 32 % | 19 / 67 % | 3 / 11 % | 7 / 27 % | 13 / 32 % | 4 / 11 % | 7 / 19 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 43 % | 18 / 46 % | 2 / 7 % | 0 / 0 % | 17 / 45 % | 3 / 11 % | 10 / 26 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 24 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 7 / 18 % | 3 / 9 % | 8 / 16 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 8 / 54 % | 2 / 8 % | 0 / 0 % | 9 / 27 % | 3 / 10 % | 12 / 25 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 11 / 55 % | 0 / 3 % | 0 / 0 % | 8 / 19 % | 2 / 6 % | 6 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 25 % | 1 / 4 % | 6 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 1 / 5 % | 8 / 23 % | 2 / 9 % | 6 / 15 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 7 / 22 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 2 % | 6 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 4 % | 5 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 6 / 14 % | 1 / 5 % | 6 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 5 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 3 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 5 / 8 % |
