[English](README.md) · [Deutsch](README.de.md)

# 2023: A Year of Groundbreaking Advances in AI and Computing

Report Q001529 · Source deepmind.google · Date 2023-12-22 · [Open original](https://deepmind.google/blog/2023-a-year-of-groundbreaking-advances-in-ai-and-computing/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Googles Rückblick stellt KI-Produkte wie Gemini und PaLM 2 sowie Fortschritte in Forschung, Algorithmen, Klima, Medizin und verantwortungsvoller KI vor. Die Leistungswerte und Projektergebnisse sind Unternehmensangaben zu konkreten Tests oder Kooperationen; einige Vorhaben sind vorläufig, und der Beitrag bezeichnet seine Auswahl selbst als kleinen Ausschnitt der Jahresarbeit.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 27 / 48 % | 86 / 96 % | – | 97 / 99 % | 49 / 75 % | 63 / 81 % | 18 / 43 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 22 / 45 % | 54 / 87 % | – | 95 / 97 % | 48 / 74 % | 54 / 76 % | 18 / 41 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 56 % | 88 / 99 % | – | 95 / 98 % | 62 / 82 % | 61 / 83 % | 17 / 43 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 27 / 47 % | 94 / 99 % | – | 46 / 67 % | 59 / 80 % | 63 / 78 % | 28 / 53 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 48 / 63 % | 92 / 97 % | – | 94 / 97 % | 84 / 90 % | 85 / 91 % | 77 / 88 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 18 / 41 % | 85 / 99 % | – | 90 / 96 % | 19 / 46 % | 13 / 40 % | 6 / 20 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 32 / 57 % | 72 / 86 % | – | 84 / 94 % | 68 / 81 % | 73 / 85 % | 27 / 48 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 45 % | 48 / 90 % | – | 83 / 93 % | 28 / 55 % | 28 / 52 % | 11 / 33 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 11 / 24 % | 81 / 94 % | – | 12 / 33 % | 12 / 30 % | 14 / 30 % | 5 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 43 / 78 % | – | 73 / 91 % | 9 / 29 % | 9 / 18 % | 1 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 41 % | 69 / 95 % | – | 72 / 86 % | 25 / 52 % | 20 / 43 % | 2 / 15 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 10 / 48 % | – | 71 / 85 % | 38 / 62 % | 13 / 35 % | 7 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 20 / 36 % | 63 / 90 % | – | 70 / 87 % | 25 / 53 % | 23 / 63 % | 7 / 27 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 21 / 48 % | 59 / 97 % | – | 64 / 86 % | 26 / 58 % | 21 / 60 % | 5 / 23 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 24 / 43 % | 46 / 83 % | – | 61 / 77 % | 32 / 58 % | 23 / 47 % | 7 / 25 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 46 / 78 % | – | 21 / 57 % | 34 / 59 % | 27 / 48 % | 4 / 17 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 19 / 53 % | 45 / 90 % | – | 33 / 66 % | 21 / 47 % | 19 / 38 % | 6 / 15 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 36 % | 40 / 89 % | – | 3 / 27 % | 9 / 28 % | 13 / 32 % | 3 / 14 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 35 / 60 % | – | 10 / 29 % | 13 / 32 % | 10 / 21 % | 4 / 12 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 28 / 77 % | – | 33 / 63 % | 16 / 39 % | 12 / 27 % | 4 / 14 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 30 % | 18 / 54 % | – | 33 / 59 % | 17 / 43 % | 13 / 42 % | 5 / 21 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 30 / 63 % | – | 20 / 47 % | 10 / 31 % | 5 / 19 % | 1 / 7 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 30 / 85 % | – | 0 / 0 % | 6 / 15 % | 7 / 13 % | 1 / 5 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 12 / 31 % | 27 / 75 % | – | 14 / 53 % | 21 / 49 % | 13 / 40 % | 3 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 44 % | 0 / 0 % | – | 25 / 36 % | 11 / 35 % | 7 / 25 % | 1 / 10 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 23 / 47 % | – | 0 / 0 % | 10 / 26 % | 10 / 25 % | 1 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 51 % | 10 / 24 % | 4 / 17 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 34 % | 9 / 84 % | – | 0 / 0 % | 18 / 46 % | 15 / 34 % | 5 / 17 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 11 / 34 % | 11 / 81 % | – | 17 / 42 % | 13 / 35 % | 8 / 22 % | 2 / 12 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 28 % | 0 / 9 % | – | 0 / 0 % | 14 / 44 % | 7 / 17 % | 3 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 14 / 46 % | – | 0 / 0 % | 10 / 28 % | 6 / 17 % | 1 / 5 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 3 / 14 % | 13 / 30 % | 6 / 17 % | 3 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 11 / 32 % | 1 / 24 % | – | 9 / 33 % | 9 / 28 % | 10 / 29 % | 3 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 7 / 51 % | – | 0 / 0 % | 11 / 27 % | 9 / 17 % | 3 / 9 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 29 % | 5 / 13 % | 2 / 8 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 15 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 2 / 11 % | 8 / 19 % | 5 / 12 % | 2 / 8 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 14 % | 7 / 13 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 29 % | – | 0 / 0 % | 6 / 15 % | 7 / 16 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 6 / 12 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 5 / 23 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 5 / 10 % | 0 / 3 % |
