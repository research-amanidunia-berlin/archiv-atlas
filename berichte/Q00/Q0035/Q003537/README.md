[English](README.md) · [Deutsch](README.de.md)

# Claude Fable 5 and Claude Mythos 5

Report Q003537 · Source anthropic.com · Date 2026-06-09 · [Open original](https://www.anthropic.com/news/claude-fable-5-mythos-5)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic stellt Fable 5 als leistungsstarkes, allgemein verfügbares Modell mit vorsichtigen Schutzfiltern vor; Mythos 5 soll ausgewählten Partnern mit teilweise aufgehobenen Filtern zugänglich sein. Der Bericht nennt starke Ergebnisse in Programmierung und Forschung, räumt Risiken und falsch positive Filter ein und gibt Unternehmensangaben wieder, die im Text meist nicht unabhängig bestätigt sind. Zwei Hinweise am Anfang widersprechen sich dazu, ob der Zugang ausgesetzt oder wiederhergestellt wurde; der Haupttext löst das nicht auf.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 58 / 73 % | 98 / 99 % | – | 100 / 100 % | 88 / 93 % | 83 / 89 % | 50 / 67 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 48 / 62 % | 91 / 97 % | – | 100 / 100 % | 85 / 91 % | 82 / 90 % | 59 / 78 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 50 / 65 % | 94 / 99 % | – | 97 / 99 % | 70 / 83 % | 81 / 88 % | 37 / 56 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 42 % | 97 / 100 % | – | 91 / 95 % | 46 / 68 % | 60 / 73 % | 14 / 25 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 41 / 59 % | 74 / 93 % | – | 96 / 97 % | 80 / 89 % | 87 / 92 % | 73 / 85 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 37 / 57 % | 93 / 99 % | – | 96 / 98 % | 66 / 84 % | 54 / 76 % | 45 / 64 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 60 % | 95 / 99 % | – | 95 / 97 % | 69 / 84 % | 86 / 92 % | 54 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 37 / 56 % | 89 / 96 % | – | 90 / 96 % | 68 / 82 % | 51 / 66 % | 18 / 37 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 36 / 55 % | 62 / 91 % | – | 89 / 92 % | 75 / 86 % | 81 / 87 % | 35 / 53 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 47 / 72 % | – | 89 / 94 % | 11 / 28 % | 8 / 17 % | 5 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 76 / 95 % | – | 88 / 92 % | 14 / 37 % | 10 / 21 % | 5 / 14 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 20 / 89 % | – | 86 / 92 % | 58 / 79 % | 12 / 29 % | 12 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 29 / 50 % | 57 / 80 % | – | 86 / 93 % | 53 / 71 % | 48 / 70 % | 47 / 67 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 43 / 59 % | 73 / 85 % | – | 51 / 73 % | 77 / 87 % | 85 / 89 % | 48 / 66 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 68 / 88 % | – | 83 / 91 % | 15 / 39 % | 12 / 25 % | 6 / 15 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 23 / 47 % | 69 / 96 % | – | 78 / 88 % | 26 / 53 % | 29 / 48 % | 4 / 13 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 74 / 99 % | – | 43 / 76 % | 41 / 64 % | 17 / 42 % | 12 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 28 / 79 % | – | 71 / 85 % | 15 / 35 % | 12 / 23 % | 6 / 16 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 30 % | 0 / 0 % | – | 65 / 82 % | 12 / 34 % | 13 / 32 % | 6 / 15 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 26 / 48 % | 62 / 95 % | – | 50 / 71 % | 60 / 79 % | 48 / 68 % | 17 / 32 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 41 / 76 % | – | 62 / 76 % | 17 / 40 % | 12 / 23 % | 2 / 7 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 35 / 52 % | 30 / 74 % | – | 60 / 79 % | 60 / 79 % | 34 / 55 % | 15 / 33 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 51 / 96 % | – | 37 / 49 % | 21 / 44 % | 14 / 26 % | 6 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 42 % | 44 / 61 % | – | 35 / 52 % | 35 / 60 % | 29 / 48 % | 10 / 24 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 38 / 72 % | – | 0 / 0 % | 12 / 27 % | 14 / 28 % | 0 / 2 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 15 / 32 % | 37 / 79 % | – | 24 / 32 % | 28 / 49 % | 18 / 36 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 24 / 49 % | 0 / 0 % | – | 0 / 0 % | 30 / 55 % | 31 / 48 % | 4 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 23 / 77 % | – | 31 / 41 % | 19 / 44 % | 20 / 41 % | 8 / 17 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 20 / 47 % | – | 29 / 43 % | 13 / 32 % | 13 / 25 % | 2 / 6 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 25 % | 22 / 34 % | 3 / 5 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 22 / 68 % | – | 0 / 0 % | 8 / 17 % | 11 / 18 % | 5 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 21 / 82 % | – | 20 / 37 % | 14 / 34 % | 14 / 26 % | 5 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 19 / 40 % | 11 / 23 % | 1 / 4 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 19 / 36 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 28 % | 9 / 24 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 22 % | 12 / 21 % | 3 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 12 / 45 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 4 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 1 / 11 % | 11 / 24 % | 0 / 0 % | 4 / 8 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 26 % | 8 / 14 % | 2 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 21 % | 0 / 0 % | 1 / 5 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 2 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 7 / 20 % | 8 / 18 % | 8 / 14 % | 3 / 8 % |
