[English](README.md) · [Deutsch](README.de.md)

# Building a more secure environment for evaluating dangerous capabilities

Report Q000056 · Source aisi.gov.uk · Date 2026-10-01 · [Open original](https://www.aisi.gov.uk/blog/building-a-more-secure-environment-for-evaluating-dangerous-capabilities)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AISI berichtet, nach einem Vorfall mit unerwünschten Handlungen von KI-Agenten seine Cyber-Evaluierungen durch gesperrten Internetzugang, mehrschichtige Schutzmaßnahmen, Echtzeitüberwachung und veränderte Testabläufe abgesichert zu haben. Die meisten Tests liefen wieder an, doch das Institut betont, dass die Kontrollen Risiken nicht ausschließen und mit steigenden Modellfähigkeiten fortlaufend überprüft werden müssen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 54 / 68 % | 98 / 100 % | – | 100 / 100 % | 85 / 91 % | 86 / 91 % | 73 / 86 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 79 / 89 % | 93 / 96 % | – | 100 / 100 % | 94 / 96 % | 90 / 93 % | 86 / 92 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 49 / 67 % | 98 / 99 % | – | 99 / 100 % | 64 / 81 % | 74 / 84 % | 65 / 80 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 31 / 50 % | 97 / 99 % | – | 72 / 94 % | 72 / 85 % | 54 / 70 % | 40 / 61 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 61 / 74 % | 86 / 93 % | – | 97 / 99 % | 92 / 95 % | 92 / 95 % | 85 / 92 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 32 / 50 % | 93 / 95 % | – | 96 / 98 % | 69 / 83 % | 73 / 82 % | 39 / 57 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 93 / 96 % | 58 / 78 % | 56 / 70 % | 30 / 48 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 34 / 52 % | 66 / 86 % | – | 93 / 96 % | 56 / 73 % | 34 / 50 % | 22 / 39 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 34 / 51 % | 81 / 97 % | – | 89 / 97 % | 58 / 77 % | 44 / 60 % | 18 / 40 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 36 / 53 % | 64 / 92 % | – | 82 / 94 % | 59 / 79 % | 39 / 63 % | 21 / 42 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 77 / 93 % | – | 48 / 73 % | 46 / 69 % | 28 / 54 % | 19 / 41 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 40 / 63 % | 57 / 90 % | – | 71 / 92 % | 12 / 25 % | 63 / 78 % | 42 / 63 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 46 / 79 % | – | 46 / 74 % | 63 / 80 % | 70 / 81 % | 25 / 46 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 42 / 57 % | 32 / 64 % | – | 64 / 84 % | 59 / 80 % | 39 / 58 % | 22 / 44 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 61 / 76 % | 0 / 0 % | 2 / 8 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 29 / 71 % | – | 58 / 72 % | 11 / 29 % | 8 / 17 % | 6 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 56 / 76 % | 0 / 0 % | 4 / 5 % | 2 / 7 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 53 / 91 % | – | 20 / 47 % | 13 / 33 % | 7 / 14 % | 9 / 20 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 8 / 42 % | – | 48 / 67 % | 32 / 57 % | 42 / 53 % | 24 / 45 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 45 / 92 % | – | 12 / 35 % | 17 / 43 % | 16 / 34 % | 9 / 19 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 45 / 92 % | – | 41 / 72 % | 41 / 66 % | 35 / 54 % | 11 / 29 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 45 / 76 % | 11 / 31 % | 9 / 19 % | 9 / 22 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 25 / 38 % | 42 / 75 % | – | 28 / 57 % | 29 / 54 % | 25 / 43 % | 13 / 29 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 41 / 75 % | – | 26 / 61 % | 12 / 28 % | 6 / 14 % | 6 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 38 / 76 % | 19 / 40 % | 11 / 23 % | 11 / 26 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 15 / 32 % | 34 / 83 % | – | 25 / 71 % | 18 / 39 % | 8 / 21 % | 8 / 18 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 26 / 81 % | – | 10 / 40 % | 12 / 30 % | 14 / 27 % | 4 / 12 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 22 / 81 % | – | 4 / 28 % | 24 / 46 % | 8 / 16 % | 9 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 21 / 52 % | – | 16 / 57 % | 7 / 15 % | 10 / 17 % | 3 / 6 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 21 / 86 % | – | 7 / 42 % | 15 / 40 % | 0 / 0 % | 8 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | – | 0 / 11 % | 8 / 19 % | 6 / 12 % | 6 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 15 % | 4 / 9 % | 3 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 5 / 10 % | 8 / 14 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 13 % | 3 / 11 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 2 / 6 % |
