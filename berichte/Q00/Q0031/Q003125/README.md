[English](README.md) · [Deutsch](README.de.md)

# Reflections on our Responsible Scaling Policy

Report Q003125 · Source anthropic.com · Date 2024-05-20 · [Open original](https://www.anthropic.com/news/reflections-on-our-responsible-scaling-policy)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, die Responsible Scaling Policy helfe, Sicherheitsprioritäten für fortgeschrittene KI-Modelle zu ordnen, sei aber an einigen Stellen unklar und müsse angesichts offener Forschungsfragen weiterentwickelt werden. Der Beitrag beschreibt Tests, Schutzmaßnahmen und Aufsicht für abgestufte Risikogrenzen, nennt zugleich methodische Grenzen und ungelöste Fragen; er bietet Anthropics eigene Einschätzung, keine unabhängige Bewertung der Wirksamkeit.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 67 / 84 % | 98 / 99 % | – | 100 / 100 % | 91 / 95 % | 77 / 89 % | 90 / 94 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 55 / 70 % | 99 / 100 % | – | 100 / 100 % | 85 / 92 % | 88 / 95 % | 95 / 97 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 46 / 63 % | 99 / 100 % | – | 100 / 100 % | 81 / 90 % | 65 / 86 % | 84 / 91 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 39 / 60 % | 100 / 100 % | – | 100 / 100 % | 81 / 89 % | 77 / 90 % | 85 / 91 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 28 / 48 % | 99 / 100 % | – | 84 / 97 % | 76 / 88 % | 41 / 61 % | 77 / 87 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 65 / 83 % | 87 / 98 % | – | 98 / 100 % | 20 / 44 % | 76 / 89 % | 86 / 92 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 62 / 77 % | 90 / 94 % | – | 97 / 98 % | 87 / 92 % | 89 / 94 % | 92 / 94 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 56 / 74 % | 96 / 98 % | – | 96 / 99 % | 86 / 92 % | 87 / 94 % | 94 / 96 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 38 / 60 % | 90 / 99 % | – | 92 / 97 % | 65 / 82 % | 69 / 86 % | 81 / 88 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 35 / 57 % | 76 / 91 % | – | 92 / 96 % | 59 / 77 % | 45 / 62 % | 76 / 85 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 15 / 42 % | 52 / 88 % | – | 87 / 96 % | 42 / 69 % | 14 / 37 % | 26 / 60 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 32 / 58 % | 56 / 94 % | – | 85 / 93 % | 53 / 75 % | 61 / 80 % | 85 / 91 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 22 / 44 % | 16 / 49 % | – | 39 / 59 % | 50 / 73 % | 38 / 65 % | 72 / 84 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 22 / 47 % | 69 / 95 % | – | 54 / 85 % | 34 / 58 % | 13 / 31 % | 35 / 57 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 56 / 81 % | – | 65 / 82 % | 28 / 52 % | 9 / 19 % | 21 / 38 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 11 / 26 % | 64 / 86 % | – | 46 / 75 % | 15 / 39 % | 7 / 23 % | 13 / 35 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 59 / 95 % | – | 20 / 57 % | 13 / 33 % | 7 / 24 % | 13 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 58 / 89 % | – | 50 / 82 % | 58 / 78 % | 22 / 47 % | 15 / 35 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 38 / 88 % | – | 58 / 83 % | 31 / 61 % | 12 / 43 % | 31 / 65 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 12 / 37 % | 46 / 95 % | – | 53 / 75 % | 26 / 53 % | 10 / 29 % | 16 / 38 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 53 / 75 % | 8 / 17 % | 0 / 0 % | 9 / 15 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 33 % | 13 / 60 % | – | 17 / 39 % | 35 / 61 % | 14 / 35 % | 48 / 67 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 26 / 53 % | 38 / 89 % | – | 42 / 74 % | 43 / 66 % | 46 / 69 % | 34 / 58 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 46 / 89 % | – | 11 / 28 % | 16 / 36 % | 6 / 19 % | 13 / 30 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 36 / 67 % | – | 43 / 70 % | 19 / 45 % | 5 / 13 % | 16 / 36 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 19 / 46 % | 40 / 80 % | – | 42 / 74 % | 33 / 59 % | 11 / 34 % | 38 / 62 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 33 / 86 % | – | 5 / 36 % | 12 / 29 % | 5 / 14 % | 7 / 25 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 8 / 25 % | 32 / 82 % | – | 28 / 50 % | 8 / 26 % | 4 / 15 % | 9 / 23 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 27 / 72 % | – | 0 / 0 % | 6 / 13 % | 2 / 6 % | 7 / 19 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 26 / 68 % | – | 21 / 51 % | 9 / 26 % | 3 / 13 % | 8 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 18 / 40 % | 6 / 16 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 15 / 65 % | – | 2 / 20 % | 9 / 22 % | 1 / 5 % | 13 / 30 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 15 / 94 % | – | 1 / 15 % | 7 / 20 % | 2 / 8 % | 10 / 21 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 35 % | 11 / 23 % | 10 / 29 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 6 / 35 % | – | 10 / 31 % | 7 / 21 % | 4 / 13 % | 11 / 22 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 7 / 26 % | 8 / 20 % | 2 / 9 % | 11 / 27 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 9 / 93 % | – | 3 / 29 % | 8 / 21 % | 3 / 11 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 2 / 8 % | 8 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 4 / 10 % | 6 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 1 / 6 % | 7 / 19 % | 1 / 6 % | 7 / 15 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 7 / 13 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 2 / 6 % | 6 / 14 % |
