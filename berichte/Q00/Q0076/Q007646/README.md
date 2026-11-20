[English](README.md) · [Deutsch](README.de.md)

# OpenAI safety practices

Report Q007646 · Source openai.com · Date 2024-05-21 · [Open original](https://openai.com/index/openai-safety-update/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt zehn eigene Sicherheitspraktiken, darunter Modelltests, Missbrauchsüberwachung, Schutzmaßnahmen für Kinder und Wahlen, Sicherheitsforschung und Aufsicht über Veröffentlichungsentscheidungen. Das Unternehmen sagt, die bisherigen Maßnahmen hätten sichere Bereitstellungen auf dem damaligen Fähigkeitsniveau ermöglicht, räumt aber weiteren Handlungsbedarf ein und kündigt für das nächste Frontier-Modell stärkere Abwehr und längere Testphasen an.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 45 / 67 % | 100 / 100 % | – | 100 / 100 % | 83 / 90 % | 84 / 91 % | 63 / 80 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 61 % | 99 / 100 % | – | 100 / 100 % | 66 / 84 % | 81 / 90 % | 68 / 85 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 53 / 72 % | 94 / 99 % | – | 100 / 100 % | 82 / 90 % | 76 / 87 % | 71 / 86 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 44 / 62 % | 85 / 95 % | – | 99 / 100 % | 77 / 88 % | 65 / 78 % | 42 / 68 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 33 / 56 % | 98 / 99 % | – | 99 / 100 % | 73 / 85 % | 79 / 88 % | 45 / 69 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 48 / 66 % | 95 / 99 % | – | 92 / 96 % | 80 / 88 % | 80 / 87 % | 63 / 80 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 19 / 48 % | 49 / 88 % | – | 94 / 97 % | 52 / 77 % | 54 / 76 % | 37 / 67 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 34 / 60 % | 51 / 85 % | – | 92 / 98 % | 36 / 61 % | 65 / 82 % | 55 / 77 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 27 / 53 % | 29 / 70 % | – | 90 / 97 % | 47 / 71 % | 33 / 61 % | 16 / 44 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 53 % | 72 / 95 % | – | 88 / 97 % | 50 / 75 % | 51 / 76 % | 36 / 63 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 26 / 54 % | 69 / 93 % | – | 86 / 93 % | 38 / 63 % | 31 / 53 % | 14 / 39 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 19 / 37 % | 61 / 88 % | – | 83 / 92 % | 30 / 56 % | 27 / 54 % | 9 / 26 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 47 % | 53 / 93 % | – | 81 / 88 % | 39 / 65 % | 46 / 70 % | 20 / 48 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 10 / 37 % | 81 / 90 % | – | 12 / 33 % | 15 / 36 % | 15 / 38 % | 10 / 31 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 18 / 46 % | 75 / 88 % | – | 66 / 82 % | 56 / 78 % | 63 / 77 % | 26 / 55 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 24 / 53 % | 49 / 78 % | – | 72 / 90 % | 41 / 66 % | 48 / 67 % | 24 / 57 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 36 % | 70 / 94 % | – | 37 / 61 % | 11 / 31 % | 13 / 32 % | 5 / 22 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 15 / 34 % | 70 / 93 % | – | 63 / 83 % | 19 / 47 % | 21 / 55 % | 12 / 36 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 33 / 83 % | – | 67 / 88 % | 54 / 76 % | 16 / 40 % | 19 / 45 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 26 / 46 % | 59 / 95 % | – | 47 / 74 % | 24 / 53 % | 25 / 44 % | 13 / 36 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 44 % | 59 / 95 % | – | 26 / 59 % | 33 / 57 % | 35 / 58 % | 22 / 47 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 54 / 95 % | – | 43 / 74 % | 17 / 39 % | 18 / 43 % | 8 / 27 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 33 / 67 % | – | 52 / 74 % | 7 / 18 % | 7 / 12 % | 3 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 17 / 39 % | 44 / 94 % | – | 16 / 46 % | 29 / 55 % | 13 / 42 % | 10 / 30 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 43 / 78 % | – | 24 / 46 % | 16 / 44 % | 17 / 37 % | 9 / 31 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 31 % | 35 / 80 % | – | 27 / 47 % | 9 / 25 % | 9 / 21 % | 6 / 23 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 33 / 78 % | – | 12 / 35 % | 9 / 23 % | 8 / 21 % | 4 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 32 / 72 % | – | 11 / 35 % | 13 / 35 % | 12 / 33 % | 2 / 14 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 30 / 74 % | – | 0 / 7 % | 7 / 16 % | 7 / 16 % | 3 / 13 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 28 / 71 % | – | 20 / 53 % | 14 / 34 % | 15 / 33 % | 9 / 28 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 31 % | 25 / 77 % | – | 20 / 49 % | 8 / 24 % | 7 / 21 % | 4 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 24 / 55 % | – | 21 / 46 % | 18 / 46 % | 14 / 48 % | 5 / 19 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 16 / 41 % | 21 / 69 % | – | 14 / 47 % | 13 / 34 % | 17 / 36 % | 8 / 27 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 6 / 36 % | – | 0 / 0 % | 19 / 46 % | 11 / 49 % | 9 / 30 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 8 / 26 % | – | 14 / 30 % | 16 / 36 % | 17 / 32 % | 2 / 8 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 16 / 80 % | – | 3 / 25 % | 11 / 28 % | 11 / 27 % | 4 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 16 / 36 % | 0 / 0 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 15 / 32 % | 9 / 20 % | 5 / 14 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 13 / 39 % | – | 0 / 0 % | 7 / 16 % | 8 / 24 % | 2 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 35 % | 8 / 57 % | – | 1 / 6 % | 9 / 25 % | 11 / 25 % | 8 / 27 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 29 % | 11 / 24 % | 2 / 7 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 6 / 12 % | 3 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 6 / 22 % | 7 / 58 % | – | 1 / 5 % | 6 / 14 % | 4 / 10 % | 2 / 9 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 13 % |
