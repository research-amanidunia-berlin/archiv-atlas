[English](README.md) · [Deutsch](README.de.md)

# OpenAI’s Approach to Frontier Risk

Report Q002791 · Source openai.com · Date 2023-10-26 · [Open original](https://openai.com/global-affairs/our-approach-to-frontier-risk/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet über Sicherheitsprüfungen und freiwillige Maßnahmen für fortgeschrittene KI und stellt ein geplantes Framework zur Überwachung und Begrenzung von Risiken vor. Die beschriebenen Tests lieferten laut Unternehmen gemischte Befunde; OpenAI räumt ein, dass Wissen über katastrophale Risiken begrenzt ist und Labortests späteren Missbrauch nicht vollständig vorhersagen können.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 61 % | 99 / 100 % | – | 100 / 100 % | 65 / 84 % | 70 / 85 % | 84 / 92 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 49 / 66 % | 98 / 100 % | – | 100 / 100 % | 77 / 89 % | 57 / 80 % | 78 / 88 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 30 / 52 % | 99 / 100 % | – | 100 / 100 % | 73 / 85 % | 64 / 79 % | 78 / 88 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 49 / 65 % | 99 / 100 % | – | 99 / 100 % | 79 / 89 % | 58 / 74 % | 84 / 90 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 53 / 72 % | 88 / 97 % | – | 99 / 100 % | 83 / 91 % | 59 / 79 % | 78 / 87 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 39 / 62 % | 97 / 99 % | – | 98 / 99 % | 58 / 79 % | 68 / 82 % | 86 / 93 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 51 / 70 % | 94 / 98 % | – | 98 / 100 % | 30 / 56 % | 64 / 80 % | 79 / 89 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 31 / 49 % | 95 / 98 % | – | 98 / 99 % | 66 / 82 % | 47 / 65 % | 58 / 73 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 10 / 30 % | 96 / 98 % | – | 9 / 23 % | 13 / 30 % | 7 / 21 % | 15 / 30 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 34 % | 19 / 79 % | – | 93 / 98 % | 26 / 54 % | 9 / 30 % | 18 / 47 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 42 / 63 % | 92 / 98 % | – | 91 / 97 % | 77 / 88 % | 80 / 90 % | 84 / 90 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 52 / 92 % | – | 90 / 97 % | 51 / 74 % | 17 / 45 % | 18 / 42 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 22 / 48 % | 41 / 82 % | – | 89 / 94 % | 48 / 74 % | 23 / 48 % | 57 / 77 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 17 / 50 % | 79 / 93 % | – | 87 / 95 % | 34 / 61 % | 19 / 50 % | 22 / 52 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 22 / 52 % | 83 / 99 % | – | 71 / 94 % | 58 / 78 % | 34 / 57 % | 59 / 78 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 22 / 44 % | 39 / 94 % | – | 83 / 94 % | 39 / 68 % | 8 / 34 % | 30 / 70 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 22 / 45 % | 83 / 98 % | – | 79 / 89 % | 34 / 59 % | 12 / 30 % | 22 / 46 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 21 / 46 % | 81 / 95 % | – | 76 / 89 % | 35 / 60 % | 18 / 40 % | 30 / 56 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 23 / 44 % | 76 / 98 % | – | 75 / 89 % | 34 / 62 % | 13 / 34 % | 30 / 56 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 20 / 33 % | 54 / 85 % | – | 75 / 90 % | 33 / 62 % | 19 / 44 % | 25 / 64 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 21 / 46 % | 71 / 94 % | – | 69 / 83 % | 43 / 66 % | 16 / 39 % | 41 / 61 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 39 % | 70 / 96 % | – | 35 / 76 % | 24 / 49 % | 16 / 40 % | 34 / 58 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 23 / 45 % | 67 / 93 % | – | 69 / 86 % | 41 / 64 % | 13 / 34 % | 26 / 50 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 13 / 31 % | 67 / 98 % | – | 69 / 81 % | 11 / 31 % | 6 / 21 % | 11 / 28 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 26 % | 68 / 94 % | – | 63 / 87 % | 17 / 42 % | 8 / 28 % | 20 / 55 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 39 / 76 % | – | 63 / 81 % | 10 / 24 % | 1 / 9 % | 11 / 18 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 44 % | 45 / 91 % | – | 62 / 83 % | 23 / 51 % | 20 / 49 % | 34 / 69 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 57 / 99 % | – | 18 / 56 % | 18 / 40 % | 9 / 24 % | 10 / 31 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 27 % | 44 / 91 % | – | 24 / 49 % | 7 / 21 % | 4 / 15 % | 10 / 24 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 41 / 74 % | – | 16 / 47 % | 13 / 34 % | 5 / 20 % | 15 / 35 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 13 / 33 % | 37 / 84 % | – | 23 / 50 % | 14 / 34 % | 12 / 28 % | 15 / 43 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 37 / 93 % | – | 17 / 56 % | 15 / 38 % | 11 / 38 % | 16 / 33 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 30 % | 31 / 92 % | – | 5 / 31 % | 15 / 43 % | 9 / 29 % | 21 / 46 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 26 / 44 % | 13 / 31 % | 5 / 27 % | 13 / 29 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 23 / 67 % | – | 20 / 53 % | 13 / 33 % | 6 / 18 % | 14 / 34 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 21 / 90 % | – | 6 / 32 % | 7 / 19 % | 2 / 11 % | 10 / 22 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 10 / 27 % | – | 0 / 0 % | 20 / 41 % | 0 / 0 % | 13 / 22 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 90 % | – | 1 / 16 % | 8 / 19 % | 5 / 18 % | 9 / 21 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 37 % | 8 / 23 % | 13 / 38 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 11 / 68 % | – | 0 / 0 % | 10 / 23 % | 8 / 21 % | 10 / 20 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 11 % | 9 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 9 / 68 % | – | 1 / 8 % | 7 / 14 % | 3 / 10 % | 7 / 16 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 1 / 6 % | 8 / 16 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 2 / 11 % | 7 / 13 % |
