[English](README.md) · [Deutsch](README.de.md)

# GPT-4o System Card

Report Q002072 · Source openai.com · Date 2024-08-08 · [Open original](https://openai.com/index/gpt-4o-system-card/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Die System Card berichtet über GPT‑4os multimodale Fähigkeiten, Sicherheitsprüfungen und Schutzmaßnahmen, insbesondere für Sprache. OpenAI stuft Cyber-, Bio- und Autonomierisiken als niedrig ein, Überzeugungsfähigkeit im Text jedoch als mittel; zugleich nennt der Bericht methodische Grenzen, verbleibende Audiofehler und weiteren Forschungsbedarf.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 37 / 59 % | 100 / 100 % | – | 99 / 100 % | 57 / 79 % | 54 / 67 % | 43 / 63 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 61 / 77 % | 93 / 97 % | – | 100 / 100 % | 87 / 93 % | 78 / 87 % | 56 / 75 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 52 / 71 % | 99 / 100 % | – | 100 / 100 % | 77 / 88 % | 84 / 92 % | 63 / 78 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 56 / 70 % | 96 / 99 % | – | 100 / 100 % | 86 / 92 % | 78 / 88 % | 50 / 71 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 40 / 58 % | 97 / 100 % | – | 93 / 96 % | 73 / 86 % | 66 / 82 % | 34 / 57 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 34 / 55 % | 91 / 97 % | – | 97 / 98 % | 60 / 79 % | 55 / 70 % | 18 / 34 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 57 / 74 % | 96 / 98 % | – | 96 / 98 % | 87 / 92 % | 61 / 77 % | 53 / 69 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 49 / 69 % | 73 / 85 % | – | 94 / 97 % | 78 / 89 % | 52 / 66 % | 16 / 36 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 38 / 57 % | 83 / 94 % | – | 94 / 97 % | 78 / 88 % | 77 / 87 % | 36 / 58 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 45 / 63 % | 92 / 97 % | – | 75 / 86 % | 78 / 88 % | 71 / 82 % | 26 / 45 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 53 / 66 % | – | 91 / 95 % | 71 / 85 % | 13 / 27 % | 19 / 36 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 44 / 63 % | 81 / 86 % | – | 91 / 95 % | 86 / 93 % | 66 / 77 % | 19 / 35 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 23 / 42 % | 86 / 100 % | – | 45 / 73 % | 37 / 61 % | 47 / 62 % | 6 / 21 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 67 / 84 % | – | 86 / 93 % | 19 / 44 % | 14 / 34 % | 3 / 12 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 36 / 56 % | 77 / 98 % | – | 84 / 92 % | 69 / 83 % | 48 / 64 % | 13 / 29 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 26 / 53 % | 0 / 0 % | – | 72 / 82 % | 37 / 62 % | 14 / 31 % | 7 / 15 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 8 / 62 % | – | 65 / 83 % | 22 / 47 % | 11 / 24 % | 5 / 15 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 12 / 31 % | 64 / 92 % | – | 8 / 17 % | 15 / 36 % | 12 / 25 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 59 / 93 % | – | 43 / 69 % | 21 / 49 % | 16 / 33 % | 4 / 13 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 37 / 58 % | 40 / 69 % | – | 55 / 74 % | 42 / 67 % | 29 / 49 % | 16 / 28 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 18 / 42 % | 49 / 86 % | – | 14 / 33 % | 37 / 61 % | 30 / 49 % | 13 / 30 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 48 / 90 % | – | 31 / 57 % | 12 / 29 % | 8 / 19 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 34 / 72 % | – | 33 / 57 % | 14 / 34 % | 17 / 29 % | 6 / 15 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 7 / 96 % | – | 33 / 54 % | 9 / 26 % | 10 / 21 % | 3 / 10 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 32 / 87 % | – | 19 / 33 % | 15 / 38 % | 10 / 20 % | 3 / 10 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 30 / 70 % | 0 / 0 % | – | 0 / 0 % | 24 / 51 % | 26 / 46 % | 9 / 25 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 23 / 34 % | – | 0 / 0 % | 15 / 32 % | 10 / 17 % | 5 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 22 / 56 % | – | 0 / 0 % | 12 / 27 % | 8 / 21 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 16 / 59 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 35 % | 11 / 43 % | – | 0 / 0 % | 11 / 29 % | 13 / 27 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 14 / 89 % | – | 3 / 13 % | 9 / 24 % | 8 / 18 % | 2 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 32 % | 11 / 23 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 14 / 64 % | – | 0 / 0 % | 6 / 18 % | 8 / 15 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 13 / 88 % | – | 1 / 11 % | 10 / 24 % | 6 / 14 % | 3 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 8 / 22 % | 9 / 25 % | 12 / 24 % | 2 / 10 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 21 % | 5 / 11 % | 1 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 25 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 8 / 16 % | 2 / 5 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % |
