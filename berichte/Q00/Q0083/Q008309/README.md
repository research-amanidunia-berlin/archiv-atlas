[English](README.md) · [Deutsch](README.de.md)

# Improving verifiability in AI development

Report Q008309 · Source openai.com · Date 2020-04-16 · [Open original](https://openai.com/index/improving-verifiability/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Text fasst zehn vorgeschlagene Ansätze zusammen, mit denen sich Aussagen über Sicherheit, Fairness und Datenschutz von KI-Systemen besser prüfen lassen sollen – von externen Audits und Vorfallmeldungen bis zu sicheren Hardwarelösungen und mehr Rechenleistung für akademische Forschung. Er ist eine Zusammenfassung, nicht der vollständige Bericht; Belege, Wirksamkeitsvergleiche und dort erwähnte Einschränkungen werden nicht ausgeführt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 32 / 58 % | 88 / 98 % | 93 / 99 % | 59 / 82 % | 65 / 84 % | 70 / 84 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 42 / 64 % | 89 / 97 % | 58 / 76 % | 70 / 85 % | 57 / 73 % | 74 / 84 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 26 / 59 % | 48 / 97 % | 86 / 96 % | 40 / 67 % | 9 / 35 % | 34 / 65 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 58 % | 67 / 96 % | 85 / 95 % | 41 / 72 % | 12 / 42 % | 53 / 76 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 24 / 50 % | 36 / 74 % | 80 / 92 % | 23 / 57 % | 13 / 34 % | 30 / 63 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 24 / 56 % | 43 / 86 % | 76 / 92 % | 48 / 77 % | 45 / 71 % | 50 / 73 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 17 / 45 % | 53 / 97 % | 73 / 86 % | 15 / 42 % | 5 / 20 % | 15 / 45 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 27 / 55 % | 37 / 82 % | 69 / 86 % | 43 / 71 % | 32 / 59 % | 48 / 70 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 49 % | 65 / 92 % | 68 / 83 % | 35 / 61 % | 35 / 59 % | 44 / 66 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 31 / 60 % | 53 / 93 % | 65 / 93 % | 55 / 79 % | 46 / 72 % | 52 / 75 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 22 / 49 % | 62 / 92 % | 46 / 77 % | 31 / 61 % | 19 / 43 % | 36 / 56 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 45 % | 61 / 96 % | 28 / 52 % | 16 / 44 % | 12 / 32 % | 43 / 65 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 15 / 41 % | 7 / 43 % | 57 / 85 % | 17 / 48 % | 6 / 30 % | 16 / 47 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 25 / 54 % | 36 / 90 % | 53 / 83 % | 37 / 68 % | 22 / 50 % | 21 / 52 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 39 % | 44 / 84 % | 38 / 72 % | 22 / 52 % | 8 / 33 % | 28 / 62 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 22 / 46 % | 37 / 64 % | 43 / 71 % | 32 / 60 % | 16 / 37 % | 37 / 57 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 13 / 41 % | 42 / 93 % | 9 / 54 % | 15 / 42 % | 9 / 30 % | 20 / 44 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 12 / 44 % | 30 / 78 % | 41 / 80 % | 22 / 51 % | 14 / 38 % | 35 / 62 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 14 / 45 % | 38 / 81 % | 23 / 65 % | 17 / 52 % | 3 / 17 % | 11 / 37 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 24 / 48 % | 35 / 75 % | 16 / 55 % | 19 / 52 % | 7 / 25 % | 22 / 54 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 32 / 69 % | 31 / 60 % | 8 / 23 % | 5 / 16 % | 8 / 22 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 32 / 78 % | 9 / 42 % | 10 / 29 % | 3 / 12 % | 12 / 26 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 8 / 35 % | 31 / 89 % | 17 / 65 % | 14 / 43 % | 2 / 16 % | 12 / 33 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 16 / 41 % | 29 / 88 % | 27 / 78 % | 27 / 59 % | 8 / 28 % | 23 / 49 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 7 / 32 % | 28 / 82 % | 0 / 0 % | 9 / 30 % | 0 / 8 % | 7 / 22 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 23 / 70 % | 15 / 47 % | 7 / 23 % | 3 / 11 % | 9 / 22 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 38 % | 23 / 76 % | 1 / 10 % | 8 / 25 % | 3 / 13 % | 12 / 30 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 21 / 77 % | 1 / 24 % | 15 / 43 % | 9 / 26 % | 14 / 29 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 20 / 50 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 11 / 40 % | 3 / 19 % | 12 / 33 % | 2 / 10 % | 13 / 31 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 12 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 38 % | 12 / 33 % | 12 / 30 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 11 / 37 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 31 % | 1 / 5 % | 10 / 22 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 10 / 54 % | 0 / 0 % | 6 / 19 % | 1 / 6 % | 6 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 9 / 54 % | 2 / 14 % | 6 / 22 % | 2 / 10 % | 6 / 17 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 5 / 58 % | 0 / 0 % | 6 / 15 % | 2 / 7 % | 9 / 24 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 4 / 14 % | 7 / 17 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 8 / 17 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 75 % | 0 / 0 % | 6 / 15 % | 1 / 7 % | 8 / 16 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 7 / 18 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 4 / 27 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 6 / 12 % | – | – |
