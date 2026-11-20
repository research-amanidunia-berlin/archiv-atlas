[English](README.md) · [Deutsch](README.de.md)

# Amazon Nova Reel - AWS AI Service Cards

Report Q004873 · Source docs.aws.amazon.com · Date 2025-07-16 · [Open original](https://docs.aws.amazon.com/ai/responsible-ai/nova-reel/overview.html)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AWS beschreibt Nova Reel als Bedrock-Modell, das aus englischen Textprompts und optionalen Bildern Videos von bis zu 120 Sekunden erzeugt. Der Anbieter berichtet über Sicherheitsprüfungen, betont aber, dass Kunden Wirksamkeit und Risiken selbst für ihren Einsatzfall bewerten müssen. Zu den Grenzen zählen mögliche unerwünschte oder fehlerhafte Inhalte, fehlende Audio- und 3D-Ausgabe sowie eingeschränkte Sprach- und Eingabeformate.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 46 / 64 % | 90 / 99 % | 59 / 79 % | 100 / 100 % | 81 / 90 % | 77 / 88 % | 34 / 58 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 29 / 48 % | 92 / 95 % | 20 / 38 % | 99 / 100 % | 64 / 82 % | 52 / 68 % | 11 / 27 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 24 / 43 % | 94 / 99 % | 5 / 13 % | 98 / 99 % | 21 / 47 % | 20 / 47 % | 9 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 24 / 44 % | 91 / 95 % | 62 / 68 % | 97 / 98 % | 60 / 79 % | 65 / 75 % | 17 / 30 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 62 / 77 % | 92 / 99 % | 97 / 98 % | 97 / 99 % | 88 / 93 % | 89 / 93 % | 86 / 92 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 95 / 98 % | 22 / 34 % | 96 / 99 % | 38 / 67 % | 52 / 68 % | 28 / 48 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 75 / 92 % | 24 / 42 % | 96 / 97 % | 60 / 81 % | 60 / 79 % | 23 / 44 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 22 / 47 % | 71 / 96 % | 19 / 36 % | 96 / 99 % | 53 / 77 % | 39 / 66 % | 15 / 36 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 54 % | 93 / 98 % | 58 / 75 % | 94 / 96 % | 65 / 84 % | 80 / 89 % | 43 / 65 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 47 / 77 % | 0 / 0 % | 91 / 96 % | 9 / 24 % | 6 / 12 % | 1 / 8 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 22 / 48 % | 74 / 94 % | 32 / 47 % | 88 / 94 % | 25 / 49 % | 44 / 65 % | 15 / 33 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 39 % | 77 / 93 % | 15 / 29 % | 82 / 90 % | 37 / 61 % | 40 / 59 % | 15 / 30 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 81 / 98 % | 4 / 10 % | 81 / 94 % | 25 / 55 % | 14 / 42 % | 6 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 30 / 66 % | 2 / 7 % | 75 / 88 % | 26 / 53 % | 6 / 15 % | 6 / 16 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 61 / 86 % | 5 / 9 % | 42 / 63 % | 26 / 51 % | 17 / 33 % | 6 / 14 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 58 / 81 % | 9 / 17 % | 59 / 71 % | 25 / 46 % | 19 / 30 % | 10 / 18 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 58 / 88 % | 25 / 33 % | 50 / 66 % | 35 / 61 % | 22 / 39 % | 12 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 15 / 36 % | 57 / 86 % | 6 / 14 % | 45 / 68 % | 21 / 45 % | 24 / 43 % | 7 / 20 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 54 / 85 % | 1 / 7 % | 7 / 18 % | 9 / 21 % | 9 / 18 % | 2 / 8 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 8 % | 53 / 71 % | 18 / 41 % | 10 / 25 % | 3 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 49 / 69 % | 10 / 27 % | 6 / 15 % | 4 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 44 / 83 % | 0 / 2 % | 0 / 0 % | 8 / 23 % | 4 / 11 % | 1 / 6 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 2 / 6 % | 41 / 65 % | 24 / 55 % | 17 / 38 % | 3 / 9 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 40 / 71 % | 0 / 2 % | 35 / 59 % | 8 / 24 % | 6 / 15 % | 2 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 28 / 45 % | 0 / 0 % | 0 / 0 % | 39 / 63 % | 13 / 23 % | 21 / 32 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 33 / 57 % | 2 / 7 % | 37 / 62 % | 13 / 32 % | 10 / 21 % | 4 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 31 / 73 % | 2 / 5 % | 0 / 0 % | 13 / 34 % | 13 / 26 % | 1 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 31 / 68 % | 6 / 9 % | 28 / 51 % | 29 / 50 % | 21 / 31 % | 9 / 18 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 30 / 64 % | 1 / 4 % | 17 / 31 % | 14 / 33 % | 7 / 17 % | 3 / 10 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 24 / 64 % | 0 / 2 % | 15 / 34 % | 7 / 19 % | 5 / 14 % | 2 / 10 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | 19 / 45 % | 7 / 17 % | 4 / 14 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 36 % | 0 / 0 % | 0 / 3 % | 1 / 12 % | 11 / 35 % | 7 / 16 % | 4 / 11 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 6 / 18 % | 14 / 38 % | 7 / 16 % | 3 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 27 % | 11 / 23 % | 3 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 10 / 28 % | 11 / 29 % | 3 / 10 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 10 / 24 % | 6 / 13 % | 2 / 9 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 5 / 14 % | 1 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 7 / 18 % | 5 / 10 % | 2 / 7 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 12 % | 1 / 4 % |
