[English](README.md) · [Deutsch](README.de.md)

# Principles for Embedded Evaluations

Report Q000795 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/blog/principles-for-embedded-evaluations)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Apollo Research schlägt ein System externer, eingebetteter Prüfungen vor, das konkrete Sicherheitsbehauptungen zu fortgeschrittenen KI-Systemen untersucht und seine Urteile samt Belegen und Zugangsgrenzen veröffentlicht. Der Bericht versteht dies als Ausgangspunkt: Heutige Methoden erlauben oft keine hohe Gewissheit, und gezielte Manipulation oder unzureichender Zugang könnten die Prüfungen unterlaufen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 88 / 92 % | 99 / 100 % | 100 / 100 % | – | 89 / 93 % | – | 97 / 98 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 62 / 75 % | 100 / 100 % | 97 / 99 % | – | 90 / 94 % | – | 95 / 98 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 58 / 75 % | 100 / 100 % | 96 / 98 % | – | 84 / 91 % | – | 86 / 94 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 69 / 81 % | 89 / 96 % | 92 / 98 % | – | 48 / 63 % | – | 92 / 96 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 36 / 54 % | 90 / 98 % | 58 / 74 % | – | 68 / 83 % | – | 72 / 85 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 39 % | 89 / 99 % | 23 / 51 % | – | 46 / 73 % | – | 19 / 43 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 44 % | 81 / 98 % | 4 / 19 % | – | 34 / 66 % | – | 23 / 52 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 57 % | 81 / 98 % | 36 / 66 % | – | 67 / 84 % | – | 47 / 74 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 42 / 65 % | 73 / 97 % | 71 / 90 % | – | 79 / 90 % | – | 47 / 70 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 27 / 49 % | 77 / 99 % | 15 / 39 % | – | 61 / 81 % | – | 28 / 59 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 22 / 45 % | 76 / 98 % | 15 / 49 % | – | 39 / 68 % | – | 22 / 48 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 34 / 56 % | 45 / 96 % | 22 / 47 % | – | 76 / 88 % | – | 50 / 76 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 76 / 97 % | 21 / 47 % | – | 42 / 70 % | – | 22 / 47 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 36 / 55 % | 76 / 94 % | 63 / 79 % | – | 58 / 81 % | – | 48 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 20 / 44 % | 67 / 88 % | 14 / 30 % | – | 43 / 66 % | – | 13 / 33 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 19 / 38 % | 65 / 93 % | 10 / 46 % | – | 27 / 55 % | – | 14 / 32 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 57 / 91 % | 2 / 7 % | – | 17 / 42 % | – | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 16 / 36 % | 57 / 94 % | 3 / 10 % | – | 44 / 69 % | – | 7 / 22 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 23 / 69 % | 9 / 25 % | – | 50 / 74 % | – | 18 / 44 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 37 % | 44 / 90 % | 4 / 14 % | – | 19 / 44 % | – | 11 / 31 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 44 / 82 % | 5 / 19 % | – | 14 / 36 % | – | 9 / 25 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 17 / 42 % | 43 / 94 % | 27 / 63 % | – | 30 / 58 % | – | 27 / 56 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 16 / 38 % | 43 / 86 % | 4 / 16 % | – | 19 / 45 % | – | 12 / 32 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 41 / 90 % | 4 / 10 % | – | 31 / 57 % | – | 15 / 42 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 14 / 83 % | 28 / 50 % | – | 39 / 64 % | – | 28 / 49 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 36 / 73 % | 2 / 6 % | – | 18 / 40 % | – | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 15 / 36 % | 15 / 64 % | 12 / 42 % | – | 35 / 64 % | – | 17 / 39 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 33 / 78 % | 1 / 3 % | – | 9 / 21 % | – | 6 / 14 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 30 % | 15 / 70 % | 21 / 53 % | – | 29 / 56 % | – | 17 / 42 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 28 / 72 % | 0 / 0 % | – | 8 / 19 % | – | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 23 / 46 % | – | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 5 / 18 % | – | 19 / 47 % | – | 13 / 33 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 14 / 47 % | 0 / 0 % | – | 7 / 15 % | – | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 4 / 10 % | – | 14 / 32 % | – | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 2 / 6 % | – | 14 / 33 % | – | 6 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 5 % | – | 10 / 24 % | – | 5 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 10 / 49 % | 0 / 0 % | – | 6 / 13 % | – | 2 / 5 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 9 / 68 % | 0 / 1 % | – | 7 / 18 % | – | 1 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 70 % | 0 / 2 % | – | 9 / 23 % | – | 6 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 17 % | – | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | – | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 3 / 46 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
