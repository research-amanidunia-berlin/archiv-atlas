[English](README.md) · [Deutsch](README.de.md)

# Принципы ИИ: Рекомендации по этичному использованию искусственного интеллекта Министерством обороны

Report Q006538 · Source cset.georgetown.edu · Date 2019-12-10 · [Open original](https://cset.georgetown.edu/publication/%d0%bf%d1%80%d0%b8%d0%bd%d1%86%d0%b8%d0%bf%d1%8b-%d0%b8%d0%b8-%d1%80%d0%b5%d0%ba%d0%be%d0%bc%d0%b5%d0%bd%d0%b4%d0%b0%d1%86%d0%b8%d0%b8-%d0%bf%d0%be-%d1%8d%d1%82%d0%b8%d1%87%d0%bd%d0%be%d0%bc%d1%83/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht schlägt fünf ethische Grundsätze für KI im US-Verteidigungsministerium vor: menschliche Verantwortung, Vermeidung unbeabsichtigter Verzerrungen, Nachvollziehbarkeit, Zuverlässigkeit und Kontrollierbarkeit. Zwölf Empfehlungen sollen ihre mögliche Umsetzung unterstützen; ob das Ministerium sie übernimmt, bleibt ihm überlassen. Der vorliegende Text ist laut Vorspann eine nicht offizielle russische Übersetzung und keine Billigung durch CSET.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 40 / 62 % | 60 / 95 % | 100 / 100 % | 80 / 91 % | 42 / 67 % | 51 / 75 % | – | 52 / 78 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 56 / 73 % | 97 / 98 % | 97 / 99 % | 84 / 91 % | 56 / 74 % | 81 / 90 % | – | 68 / 83 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 36 / 57 % | 96 / 98 % | 83 / 93 % | 67 / 85 % | 37 / 63 % | 51 / 67 % | – | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 56 / 71 % | 82 / 93 % | 96 / 98 % | 85 / 92 % | 76 / 88 % | 82 / 90 % | – | 62 / 80 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 26 / 51 % | 91 / 99 % | 96 / 99 % | 54 / 76 % | 21 / 45 % | 37 / 58 % | – | 44 / 71 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 44 / 61 % | 95 / 98 % | 90 / 94 % | 76 / 87 % | 63 / 79 % | 67 / 80 % | – | 52 / 75 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 19 / 33 % | 92 / 98 % | 94 / 98 % | 29 / 57 % | 25 / 54 % | 32 / 55 % | – | 38 / 65 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 26 / 47 % | 68 / 96 % | 85 / 95 % | 58 / 77 % | 27 / 54 % | 35 / 60 % | – | 32 / 62 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 47 % | 81 / 93 % | 61 / 91 % | 64 / 84 % | 33 / 58 % | 61 / 80 % | – | 27 / 50 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 53 % | 78 / 98 % | 50 / 72 % | 37 / 70 % | 28 / 50 % | 44 / 67 % | – | 24 / 41 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 49 / 69 % | 74 / 91 % | 69 / 87 % | 61 / 80 % | 62 / 79 % | 74 / 86 % | – | 32 / 60 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 72 / 88 % | 19 / 47 % | 12 / 25 % | 19 / 33 % | – | 16 / 33 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 29 / 47 % | 71 / 93 % | 61 / 78 % | 49 / 76 % | 12 / 29 % | 32 / 58 % | – | 21 / 43 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 65 / 93 % | 28 / 51 % | 24 / 52 % | 12 / 24 % | 24 / 48 % | – | 19 / 38 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 23 / 51 % | 51 / 90 % | 64 / 89 % | 36 / 70 % | 11 / 31 % | 19 / 57 % | – | 28 / 51 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 11 / 33 % | 58 / 97 % | 42 / 79 % | 31 / 58 % | 26 / 54 % | 30 / 63 % | – | 36 / 60 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 57 / 95 % | 47 / 87 % | 27 / 60 % | 11 / 25 % | 14 / 36 % | – | 32 / 55 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 55 / 87 % | 27 / 61 % | 10 / 25 % | 7 / 15 % | 18 / 30 % | – | 13 / 36 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 54 / 81 % | 16 / 32 % | 17 / 44 % | 7 / 17 % | 11 / 28 % | – | 28 / 52 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 26 / 49 % | 52 / 95 % | 33 / 66 % | 29 / 57 % | 13 / 29 % | 23 / 43 % | – | 26 / 59 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 46 / 89 % | 27 / 75 % | 20 / 47 % | 9 / 27 % | 11 / 37 % | – | 49 / 73 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 28 % | 47 / 86 % | 18 / 62 % | 8 / 24 % | 4 / 11 % | 7 / 14 % | – | 18 / 46 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 16 / 80 % | 37 / 58 % | 14 / 37 % | 6 / 19 % | 17 / 37 % | – | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 37 / 96 % | 2 / 27 % | 17 / 52 % | 3 / 17 % | 21 / 48 % | – | 23 / 53 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 13 / 29 % | 34 / 70 % | 37 / 63 % | 20 / 52 % | 7 / 21 % | 13 / 30 % | – | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 34 / 88 % | 0 / 0 % | 25 / 62 % | 14 / 30 % | 28 / 57 % | – | 16 / 35 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 28 / 78 % | 2 / 12 % | 14 / 46 % | 5 / 15 % | 13 / 34 % | – | 11 / 24 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 43 % | 23 / 75 % | 0 / 0 % | 16 / 46 % | 7 / 18 % | 13 / 29 % | – | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 42 % | 5 / 13 % | 10 / 17 % | – | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 19 / 87 % | 9 / 46 % | 12 / 38 % | 7 / 24 % | 9 / 27 % | – | 20 / 46 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 20 / 95 % | 2 / 32 % | 14 / 43 % | 5 / 17 % | 11 / 23 % | – | 8 / 35 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 19 / 83 % | 0 / 0 % | 13 / 37 % | 6 / 16 % | 16 / 32 % | – | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 19 / 86 % | 12 / 39 % | 13 / 34 % | 7 / 20 % | 9 / 24 % | – | 18 / 40 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 17 / 78 % | 12 / 47 % | 17 / 46 % | 7 / 21 % | 7 / 20 % | – | 11 / 32 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 14 / 25 % | – | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 5 / 53 % | 5 / 21 % | 8 / 23 % | 5 / 13 % | 9 / 20 % | – | 11 / 32 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 4 / 12 % | 10 / 27 % | – | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 4 / 62 % | 1 / 7 % | 8 / 28 % | 2 / 6 % | 10 / 20 % | – | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 64 % | 0 / 0 % | 8 / 25 % | 3 / 10 % | 10 / 19 % | – | 4 / 15 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 5 / 67 % | 0 / 0 % | 7 / 19 % | 4 / 11 % | 9 / 17 % | – | 8 / 24 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 76 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 8 / 19 % | – | 9 / 26 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 8 / 15 % | – | 4 / 18 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 3 / 12 % | 7 / 20 % | – | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 6 / 15 % | – | 0 / 0 % |
