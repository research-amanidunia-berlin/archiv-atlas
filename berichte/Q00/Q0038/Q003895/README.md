[English](README.md) · [Deutsch](README.de.md)

# Google DeepMind strengthens the Frontier Safety Framework

Report Q003895 · Source deepmind.google · Date 2025-09-22 · [Open original](https://deepmind.google/blog/strengthening-our-frontier-safety-framework/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind beschreibt eine überarbeitete Fassung seines Sicherheitsrahmens für fortgeschrittene KI. Sie ergänzt Warnstufen für schädliche Manipulation, erweitert Prüfungen auf mögliche Fehlanpassung und interne Großeinsätze und führt Beobachtungsstufen für weniger extreme Risiken ein. Der Bericht gibt DeepMinds eigene Darstellung wieder; unabhängige Wirksamkeitsnachweise nennt er nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 56 % | 84 / 96 % | 43 / 79 % | 98 / 100 % | 57 / 78 % | 28 / 56 % | 42 / 74 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 35 / 56 % | 95 / 99 % | 64 / 77 % | 95 / 99 % | 56 / 76 % | 46 / 69 % | 68 / 81 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 32 / 60 % | 93 / 99 % | 48 / 74 % | 77 / 96 % | 63 / 80 % | 46 / 68 % | 66 / 82 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 55 % | 92 / 100 % | 43 / 76 % | 93 / 99 % | 42 / 72 % | 32 / 64 % | 51 / 76 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 36 / 56 % | 77 / 94 % | 32 / 64 % | 89 / 97 % | 56 / 78 % | 27 / 55 % | 48 / 71 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 18 / 44 % | 69 / 92 % | 17 / 27 % | 40 / 61 % | 33 / 57 % | 18 / 36 % | 32 / 53 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 14 / 40 % | 58 / 89 % | 5 / 22 % | 69 / 87 % | 17 / 42 % | 8 / 23 % | 13 / 34 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 38 % | 0 / 0 % | 6 / 31 % | 68 / 89 % | 19 / 47 % | 6 / 26 % | 10 / 32 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 60 / 92 % | 1 / 11 % | 31 / 67 % | 13 / 31 % | 4 / 19 % | 6 / 21 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 11 / 44 % | 59 / 84 % | 4 / 19 % | 7 / 26 % | 17 / 42 % | 8 / 23 % | 14 / 37 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 23 / 53 % | 53 / 90 % | 11 / 51 % | 54 / 87 % | 13 / 32 % | 19 / 51 % | 27 / 64 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 29 / 54 % | 0 / 0 % | 52 / 77 % | 7 / 22 % | 1 / 6 % | 5 / 10 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 16 / 39 % | 48 / 89 % | 7 / 27 % | 47 / 78 % | 20 / 42 % | 7 / 23 % | 13 / 34 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 10 / 36 % | 41 / 82 % | 5 / 19 % | 23 / 44 % | 19 / 44 % | 7 / 27 % | 7 / 21 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 45 % | 28 / 87 % | 4 / 21 % | 37 / 64 % | 17 / 43 % | 7 / 27 % | 10 / 37 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 34 / 67 % | 1 / 8 % | 20 / 60 % | 13 / 32 % | 5 / 14 % | 7 / 14 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 29 / 64 % | 8 / 28 % | 23 / 57 % | 31 / 59 % | 11 / 35 % | 7 / 19 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 22 / 50 % | 5 / 37 % | 5 / 21 % | 0 / 0 % | 31 / 61 % | 10 / 36 % | 26 / 53 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 16 / 42 % | 18 / 89 % | 3 / 17 % | 27 / 67 % | 23 / 53 % | 6 / 29 % | 10 / 44 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 32 % | 26 / 72 % | 1 / 8 % | 10 / 31 % | 10 / 28 % | 3 / 16 % | 6 / 17 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 25 / 61 % | 1 / 11 % | 1 / 7 % | 8 / 19 % | 3 / 14 % | 6 / 15 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 24 / 61 % | 1 / 5 % | 8 / 31 % | 10 / 22 % | 2 / 9 % | 16 / 32 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 20 / 80 % | 3 / 16 % | 9 / 28 % | 10 / 27 % | 3 / 13 % | 8 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 13 / 30 % | 20 / 53 % | 0 / 4 % | 8 / 26 % | 10 / 26 % | 1 / 7 % | 5 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 44 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 15 / 47 % | 0 / 0 % | 5 / 21 % | 5 / 28 % | 16 / 41 % | 6 / 20 % | 6 / 19 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 12 / 45 % | 0 / 2 % | 0 / 2 % | 8 / 17 % | 0 / 0 % | 5 / 8 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 35 % | 1 / 19 % | 1 / 5 % | 0 / 0 % | 7 / 19 % | 2 / 12 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 10 / 35 % | 0 / 3 % | 0 / 0 % | 9 / 21 % | 1 / 5 % | 5 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 7 / 26 % | 10 / 32 % | 1 / 6 % | 5 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 0 / 0 % | 9 / 21 % | 2 / 8 % | 5 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 9 / 20 % | 1 / 9 % | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 1 / 33 % | 0 / 3 % | 6 / 30 % | 8 / 17 % | 1 / 9 % | 6 / 14 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 2 / 7 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 23 % | 0 / 3 % | 1 / 15 % | 8 / 19 % | 1 / 6 % | 5 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 23 % | 4 / 81 % | 0 / 2 % | 0 / 0 % | 7 / 21 % | 2 / 12 % | 4 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 6 / 16 % | 1 / 5 % | 6 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | 3 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 12 % | 0 / 0 % | 1 / 6 % | 5 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 4 / 9 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 4 / 11 % |
