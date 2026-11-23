[English](README.md) · [Deutsch](README.de.md)

# AI cyberattacks: a timeline of real cases

Report Q000360 · Source ully.com · Date 2026-11-13 · [Open original](https://www.ully.com/en/ai-hacking-incidents/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht ordnet 563 bis zum 14. November 2026 erfasste Cybervorfälle ein, bei denen Quellen KI-Beteiligung zuschreiben, und beschreibt eine Entwicklung von KI-Hilfe bei Einzelschritten zu stärker agentengesteuerten Angriffen. Der bereitgestellte Quelltext enthält jedoch nicht die einzelnen Fälle der Chronologie; zudem seien KI-Zuschreibungen teils unsicher und die wichtigste bislang belegte Wirkung liege laut Autor eher in geringeren Kosten und kürzerer Ausführungszeit als in grundsätzlich neuen Techniken.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 35 / 63 % | 93 / 99 % | 98 / 100 % | 70 / 86 % | 22 / 49 % | 61 / 81 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 31 / 83 % | 91 / 97 % | 37 / 65 % | 3 / 12 % | 11 / 23 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 22 / 45 % | 7 / 77 % | 80 / 92 % | 25 / 58 % | 4 / 19 % | 18 / 37 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 18 / 45 % | 26 / 84 % | 70 / 88 % | 46 / 71 % | 7 / 28 % | 21 / 45 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 53 % | 4 / 52 % | 61 / 75 % | 47 / 71 % | 9 / 22 % | 20 / 35 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 6 / 40 % | 56 / 73 % | 9 / 20 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 16 / 42 % | 8 / 77 % | 25 / 43 % | 52 / 74 % | 8 / 31 % | 21 / 49 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 3 / 37 % | 39 / 66 % | 8 / 24 % | 1 / 4 % | 11 / 18 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 23 / 49 % | 19 / 97 % | 9 / 54 % | 36 / 64 % | 14 / 35 % | 22 / 52 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 17 % | 34 / 57 % | 9 / 21 % | 0 / 0 % | 14 / 26 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 14 / 68 % | 31 / 63 % | 29 / 57 % | 8 / 21 % | 25 / 42 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 24 / 45 % | 7 / 63 % | 31 / 64 % | 22 / 55 % | 6 / 17 % | 26 / 50 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 42 % | 14 / 88 % | 28 / 50 % | 17 / 40 % | 3 / 9 % | 19 / 38 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 14 / 34 % | 20 / 85 % | 12 / 51 % | 27 / 61 % | 8 / 25 % | 16 / 44 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 11 / 38 % | 25 / 83 % | 20 / 58 % | 8 / 20 % | 6 / 20 % | 22 / 47 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 17 / 43 % | 22 / 74 % | 5 / 11 % | 25 / 49 % | 7 / 17 % | 18 / 33 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 18 / 40 % | 4 / 41 % | 24 / 58 % | 21 / 51 % | 4 / 16 % | 17 / 37 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 10 / 29 % | 0 / 0 % | 24 / 51 % | 7 / 23 % | 1 / 6 % | 6 / 15 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 38 % | 21 / 80 % | 0 / 0 % | 23 / 51 % | 7 / 23 % | 20 / 38 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 10 / 52 % | 3 / 52 % | 23 / 46 % | 18 / 46 % | 2 / 8 % | 12 / 21 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 4 / 58 % | 22 / 53 % | 9 / 22 % | 1 / 6 % | 6 / 12 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 7 / 78 % | 21 / 46 % | 11 / 33 % | 0 / 2 % | 17 / 34 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 10 / 29 % | 0 / 0 % | 0 / 0 % | 21 / 49 % | 2 / 9 % | 14 / 30 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 48 % | 2 / 6 % | 17 / 28 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 34 % | 4 / 55 % | 0 / 0 % | 21 / 47 % | 5 / 20 % | 15 / 34 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 48 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 8 / 36 % | 4 / 39 % | 0 / 0 % | 15 / 51 % | 2 / 9 % | 13 / 32 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 13 / 49 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 1 / 4 % | 11 / 24 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 3 / 89 % | 4 / 31 % | 13 / 43 % | 3 / 14 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 43 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 3 % | 11 / 21 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 11 / 44 % | 1 / 8 % | 9 / 25 % | 2 / 6 % | 9 / 17 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 2 / 7 % | 10 / 16 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 0 / 0 % | 10 / 17 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 4 % | 10 / 16 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 26 % | 0 / 3 % | 8 / 16 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 9 / 13 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 1 % | 9 / 15 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 8 / 13 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 2 / 9 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 27 % | 1 / 17 % | 0 / 0 % | 7 / 19 % | 2 / 8 % | 5 / 11 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
