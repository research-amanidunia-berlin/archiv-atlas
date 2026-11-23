[English](README.md) · [Deutsch](README.de.md)

# Theories of Change for AI Auditing

Report Q001466 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/blog/theories-of-change-for-ai-auditing)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Apollo Research beschreibt fünf Arten von KI-Prüfungen, die Risiken erkennen, sichere Entwicklung fördern und Aufsicht unterstützen könnten. Der Nutzen ist laut Bericht jedoch unsicher: Tests können falsche Sicherheit schaffen und garantieren nicht, dass ein System ungefährlich ist; wirksame Prüfungen erfordern bessere Methoden, unabhängige Prüfer und durchsetzbare Regeln.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 64 % | 97 / 99 % | – | 65 / 86 % | 78 / 92 % | 81 / 92 % | 84 / 97 % | 42 / 67 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 57 / 73 % | 73 / 93 % | – | 78 / 89 % | 84 / 91 % | 88 / 92 % | 93 / 98 % | 22 / 50 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 17 / 45 % | 86 / 96 % | – | 45 / 77 % | 28 / 58 % | 45 / 82 % | 26 / 69 % | 19 / 47 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 32 / 56 % | 54 / 95 % | – | 61 / 84 % | 33 / 68 % | 86 / 94 % | 56 / 90 % | 20 / 46 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 26 / 57 % | 83 / 99 % | – | 52 / 78 % | 43 / 76 % | 48 / 74 % | 45 / 88 % | 21 / 46 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 31 / 56 % | 51 / 91 % | – | 69 / 87 % | 75 / 90 % | 76 / 90 % | 48 / 82 % | 12 / 34 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 24 / 46 % | 46 / 88 % | – | 56 / 79 % | 46 / 69 % | 75 / 85 % | 73 / 82 % | 7 / 32 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 28 / 54 % | 73 / 90 % | – | 55 / 79 % | 35 / 69 % | 63 / 84 % | 74 / 92 % | 27 / 57 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 39 % | 69 / 89 % | – | 22 / 55 % | 8 / 32 % | 19 / 58 % | 6 / 35 % | 23 / 52 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 49 % | 59 / 92 % | – | 52 / 76 % | 41 / 66 % | 66 / 83 % | 51 / 78 % | 21 / 46 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 22 / 55 % | 60 / 90 % | – | 35 / 73 % | 42 / 77 % | 65 / 89 % | 50 / 90 % | 21 / 51 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 25 / 50 % | 51 / 86 % | – | 34 / 67 % | 27 / 57 % | 64 / 78 % | 42 / 55 % | 15 / 36 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 27 / 53 % | 63 / 96 % | – | 53 / 80 % | 46 / 76 % | 37 / 76 % | 18 / 60 % | 13 / 35 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 37 / 59 % | 63 / 95 % | – | 54 / 81 % | 39 / 74 % | 62 / 85 % | 45 / 89 % | 32 / 57 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 17 / 43 % | 35 / 74 % | – | 48 / 71 % | 15 / 31 % | 59 / 70 % | 3 / 4 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 47 % | 28 / 85 % | – | 26 / 61 % | 15 / 43 % | 56 / 78 % | 31 / 65 % | 11 / 30 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 41 % | 56 / 93 % | – | 15 / 45 % | 5 / 26 % | 24 / 58 % | 3 / 20 % | 13 / 34 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 17 / 45 % | 50 / 82 % | – | 41 / 70 % | 31 / 60 % | 56 / 80 % | 23 / 52 % | 21 / 47 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 17 / 41 % | 51 / 90 % | – | 19 / 48 % | 8 / 24 % | 23 / 49 % | 7 / 25 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 15 / 47 % | 51 / 97 % | – | 23 / 54 % | 13 / 46 % | 28 / 65 % | 25 / 74 % | 23 / 55 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 19 / 40 % | 50 / 81 % | – | 35 / 59 % | 7 / 24 % | 36 / 56 % | 13 / 28 % | 23 / 50 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 24 / 53 % | 38 / 87 % | – | 44 / 74 % | 18 / 53 % | 23 / 61 % | 16 / 55 % | 12 / 35 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 19 / 48 % | 34 / 90 % | – | 42 / 75 % | 21 / 54 % | 33 / 79 % | 20 / 69 % | 10 / 35 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 10 / 32 % | 39 / 95 % | – | 15 / 44 % | 6 / 26 % | 15 / 47 % | 3 / 13 % | 8 / 26 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 14 / 42 % | 35 / 86 % | – | 21 / 51 % | 12 / 40 % | 20 / 59 % | 6 / 40 % | 12 / 40 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 30 % | 34 / 84 % | – | 15 / 43 % | 6 / 25 % | 10 / 29 % | 1 / 10 % | 12 / 37 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 9 / 46 % | 32 / 78 % | – | 13 / 38 % | 6 / 19 % | 12 / 31 % | 2 / 11 % | 8 / 29 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 19 / 41 % | 26 / 68 % | – | 23 / 58 % | 8 / 22 % | 24 / 65 % | 6 / 18 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 22 / 97 % | – | 11 / 33 % | 5 / 17 % | 8 / 29 % | 1 / 9 % | 6 / 29 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 14 / 62 % | – | 11 / 37 % | 2 / 11 % | 20 / 41 % | 2 / 10 % | 13 / 33 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 11 / 86 % | – | 16 / 45 % | 3 / 15 % | 19 / 33 % | 1 / 3 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 11 / 36 % | 18 / 58 % | – | 14 / 39 % | 6 / 18 % | 14 / 27 % | 1 / 7 % | 10 / 32 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 17 / 87 % | – | 6 / 20 % | 2 / 7 % | 9 / 22 % | 0 / 2 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 17 / 53 % | – | 10 / 28 % | 0 / 0 % | 10 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 31 % | – | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 2 % | 14 / 40 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 9 / 25 % | 0 / 0 % | – | 13 / 43 % | 7 / 35 % | 14 / 47 % | 3 / 14 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 4 / 78 % | – | 8 / 29 % | 4 / 14 % | 12 / 31 % | 1 / 7 % | 1 / 12 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | 2 / 8 % | 12 / 32 % | 1 / 5 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 91 % | – | 8 / 24 % | 3 / 14 % | 12 / 23 % | 1 / 6 % | 2 / 16 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 8 / 22 % | 0 / 0 % | 11 / 25 % | 1 / 5 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 11 / 44 % | – | 0 / 0 % | 5 / 15 % | 9 / 19 % | 0 / 2 % | 7 / 21 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 11 / 43 % | – | 7 / 22 % | 2 / 5 % | 10 / 26 % | 0 / 3 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | 3 / 10 % | 10 / 19 % | 0 / 2 % | 6 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 8 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
