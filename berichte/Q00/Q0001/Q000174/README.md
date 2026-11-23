[English](README.md) · [Deutsch](README.de.md)

# Expanding the Cyber Verification Program

Report Q000174 · Source anthropic.com · Date 2026-10-06 · [Open original](https://www.anthropic.com/news/cyber-verification-program)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic erweitert sein Cyber Verification Program auf drei Zugangsstufen für defensive Sicherheitsarbeit, autorisierte Red-Team-Tests und besonders kritische Systeme. In einem internen Benchmark blockierte Defense Access 46 von 50 Durchläufen, während Red Team Access keine blockierte Aufgabe und 34 erfolgreiche Abschlüsse verzeichnete. Die berichteten Schwachstellenzahlen beruhen auf unvollständigen Daten und sind laut Anthropic wahrscheinlich zu niedrig.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 37 / 52 % | 99 / 100 % | 100 / 100 % | 71 / 84 % | 28 / 50 % | 53 / 70 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 55 % | 98 / 100 % | 93 / 96 % | 63 / 81 % | 50 / 68 % | 68 / 81 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 49 / 64 % | 97 / 99 % | 97 / 99 % | 13 / 27 % | 60 / 74 % | 72 / 83 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 33 / 48 % | 10 / 47 % | 95 / 97 % | 67 / 82 % | 26 / 45 % | 40 / 56 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 89 / 92 % | 17 / 38 % | 4 / 9 % | 16 / 29 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 76 / 92 % | 84 / 90 % | 42 / 63 % | 8 / 18 % | 28 / 47 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 72 / 85 % | 10 / 29 % | 6 / 15 % | 10 / 22 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 23 / 57 % | 71 / 80 % | 10 / 24 % | 2 / 8 % | 8 / 23 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 65 / 96 % | 39 / 63 % | 27 / 54 % | 9 / 22 % | 17 / 39 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 20 / 68 % | 64 / 74 % | 18 / 41 % | 6 / 15 % | 9 / 24 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 29 / 49 % | 50 / 87 % | 49 / 61 % | 63 / 79 % | 26 / 46 % | 34 / 52 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 21 / 65 % | 58 / 69 % | 11 / 31 % | 3 / 11 % | 8 / 18 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 31 / 48 % | 36 / 72 % | 57 / 73 % | 57 / 74 % | 15 / 31 % | 32 / 49 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 56 / 75 % | 13 / 29 % | 12 / 25 % | 14 / 30 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 23 / 52 % | 48 / 64 % | 21 / 43 % | 8 / 18 % | 13 / 28 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 68 % | 43 / 61 % | 41 / 63 % | 11 / 24 % | 9 / 19 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 18 / 37 % | 41 / 98 % | 28 / 58 % | 37 / 60 % | 18 / 33 % | 20 / 43 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 39 / 60 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 39 / 54 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 17 / 34 % | 20 / 57 % | 0 / 0 % | 29 / 52 % | 14 / 29 % | 37 / 54 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 33 / 53 % | 8 / 18 % | 14 / 33 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 31 / 93 % | 0 / 0 % | 23 / 46 % | 8 / 19 % | 10 / 22 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 7 / 77 % | 4 / 10 % | 21 / 43 % | 7 / 17 % | 11 / 24 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 36 % | 3 / 8 % | 12 / 27 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 2 / 50 % | 2 / 11 % | 11 / 29 % | 0 / 0 % | 12 / 31 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 9 / 18 % | 8 / 18 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 28 % | 2 / 9 % | 8 / 23 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 1 / 38 % | 0 / 0 % | 8 / 16 % | 2 / 8 % | 10 / 25 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 5 % | 10 / 20 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 2 / 7 % | 9 / 16 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 2 / 6 % | 9 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 4 / 13 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 4 / 8 % | 8 / 21 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 5 / 15 % | 8 / 17 % | 0 / 0 % | 7 / 14 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 8 / 19 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 7 / 13 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 1 / 7 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 4 % | 6 / 12 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 3 / 8 % | 5 / 10 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 0 / 0 % | – | – |
