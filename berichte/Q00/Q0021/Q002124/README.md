[English](README.md) · [Deutsch](README.de.md)

# 人工智能控制：如何利用违规人工智能体

Report Q002124 · Source cset.georgetown.edu · Date 2025-11-05 · [Open original](https://cset.georgetown.edu/publication/ai-control-chinese/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der CSET-Bericht beschreibt KI-Kontrolle als zweite Schutzlinie neben der Ausrichtung: Sie soll verhindern, dass Agenten mit unerwünschten Zielen Schaden anrichten, selbst wenn sie sich regelwidrig verhalten. Vorgeschlagen werden unter anderem begrenzte Zugriffsrechte, Modellüberwachung, alternative Ausgaben und menschliche Prüfung. Der Text betont, dass Kosten, Verzögerungen und die Schwierigkeit, sehr leistungsfähige Agenten zuverlässig zu überwachen, zentrale offene Fragen bleiben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 56 / 69 % | 88 / 98 % | 77 / 92 % | 99 / 100 % | 82 / 91 % | 77 / 90 % | 81 / 90 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 59 / 79 % | 98 / 100 % | 97 / 99 % | 99 / 100 % | 90 / 94 % | 69 / 86 % | 82 / 90 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 47 / 64 % | 93 / 99 % | 59 / 83 % | 98 / 100 % | 77 / 88 % | 71 / 84 % | 78 / 88 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 55 / 73 % | 76 / 98 % | 85 / 93 % | 89 / 96 % | 84 / 92 % | 75 / 89 % | 86 / 92 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 40 / 60 % | 57 / 93 % | 39 / 69 % | 71 / 88 % | 80 / 89 % | 69 / 85 % | 86 / 92 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 30 / 50 % | 65 / 99 % | 53 / 77 % | 86 / 93 % | 73 / 87 % | 42 / 70 % | 74 / 87 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 25 / 52 % | 79 / 96 % | 6 / 22 % | 82 / 90 % | 41 / 67 % | 12 / 37 % | 49 / 68 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 26 / 62 % | 0 / 0 % | 72 / 88 % | 11 / 34 % | 5 / 13 % | 10 / 16 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 62 / 92 % | 1 / 7 % | 69 / 85 % | 9 / 29 % | 3 / 15 % | 7 / 20 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 54 % | 65 / 98 % | 42 / 72 % | 62 / 88 % | 45 / 73 % | 24 / 50 % | 52 / 71 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 61 / 94 % | 4 / 14 % | 32 / 74 % | 34 / 63 % | 4 / 12 % | 20 / 37 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 56 / 91 % | 9 / 23 % | 52 / 73 % | 11 / 36 % | 5 / 16 % | 13 / 28 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 15 / 36 % | 50 / 94 % | 13 / 36 % | 37 / 84 % | 37 / 66 % | 11 / 34 % | 26 / 51 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 14 / 40 % | 33 / 94 % | 13 / 43 % | 50 / 87 % | 20 / 51 % | 14 / 39 % | 40 / 65 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 16 / 33 % | 50 / 89 % | 8 / 19 % | 50 / 67 % | 29 / 52 % | 10 / 25 % | 32 / 49 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 11 / 28 % | 9 / 58 % | 3 / 16 % | 48 / 76 % | 21 / 49 % | 6 / 18 % | 11 / 30 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 15 / 35 % | 41 / 94 % | 8 / 34 % | 31 / 75 % | 34 / 62 % | 9 / 26 % | 32 / 50 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 40 / 94 % | 0 / 3 % | 12 / 48 % | 12 / 33 % | 2 / 10 % | 13 / 30 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 32 / 97 % | 1 / 7 % | 21 / 52 % | 10 / 32 % | 3 / 10 % | 17 / 37 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 32 / 94 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 4 / 15 % | 7 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 30 / 82 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 8 % | 6 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 27 % | 29 / 83 % | 2 / 14 % | 5 / 40 % | 15 / 39 % | 6 / 19 % | 7 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 27 / 79 % | 2 / 10 % | 25 / 49 % | 19 / 51 % | 5 / 14 % | 15 / 39 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 27 / 80 % | 0 / 3 % | 7 / 19 % | 12 / 33 % | 7 / 19 % | 9 / 19 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 21 / 89 % | 1 / 5 % | 7 / 29 % | 24 / 52 % | 7 / 20 % | 11 / 23 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 24 / 84 % | 0 / 0 % | 14 / 40 % | 13 / 39 % | 4 / 11 % | 12 / 26 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 23 / 47 % | 11 / 78 % | 1 / 6 % | 0 / 0 % | 9 / 24 % | 4 / 17 % | 18 / 42 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 21 / 67 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 4 / 10 % | 6 / 12 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 19 / 59 % | 2 / 10 % | 0 / 0 % | 17 / 46 % | 6 / 19 % | 13 / 29 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 7 / 81 % | 0 / 2 % | 18 / 37 % | 8 / 23 % | 3 / 12 % | 8 / 17 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 16 / 55 % | 0 / 0 % | 8 / 23 % | 12 / 36 % | 6 / 22 % | 10 / 18 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 16 / 53 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 2 / 6 % | 5 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 11 / 31 % | 4 / 15 % | 12 / 24 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 12 / 50 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 4 % | 4 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 10 / 38 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 3 / 7 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 9 / 57 % | 0 / 0 % | 1 / 17 % | 0 / 0 % | 7 / 14 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 7 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 2 / 10 % | 6 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 8 / 28 % | 6 / 15 % | 7 / 17 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 20 % | 1 / 3 % | 7 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 4 / 92 % | 0 / 0 % | 0 / 10 % | 7 / 22 % | 2 / 9 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 3 % | 6 / 12 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 3 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
