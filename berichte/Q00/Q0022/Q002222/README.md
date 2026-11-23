[English](README.md) · [Deutsch](README.de.md)

# Advanced AI evaluations at AISI: May update

Report Q002222 · Source aisi.gov.uk · Date 2024-05-20 · [Open original](https://www.aisi.gov.uk/blog/advanced-ai-evaluations-may-update)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Das AISI berichtet, dass fünf öffentlich verfügbare Sprachmodelle einfache Cyberaufgaben und manche kurzen digitalen Aufgaben bewältigten und bei Chemie- und Biologiefragen teils Expertenniveau erreichten. Zugleich waren sie mit einfachen Angriffen auf ihre Schutzvorkehrungen verwundbar; keines schloss eine der geprüften längerfristigen Agentenaufgaben ab. Laut AISI sind die Tests nur eine Momentaufnahme und kein Nachweis dafür, dass ein Modell sicher oder unsicher ist.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 71 / 83 % | 99 / 100 % | 100 / 100 % | 11 / 28 % | 76 / 87 % | 86 / 92 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 63 % | 98 / 100 % | 100 / 100 % | 45 / 71 % | 35 / 59 % | 65 / 81 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 55 % | 56 / 95 % | 98 / 99 % | 62 / 82 % | 14 / 39 % | 49 / 74 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 43 / 65 % | 96 / 99 % | 94 / 96 % | 61 / 77 % | 31 / 48 % | 58 / 71 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 28 / 49 % | 93 / 100 % | 92 / 97 % | 43 / 67 % | 12 / 26 % | 43 / 62 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 43 / 59 % | 76 / 99 % | 92 / 96 % | 74 / 86 % | 19 / 38 % | 52 / 74 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 33 / 57 % | 55 / 97 % | 88 / 96 % | 72 / 85 % | 11 / 35 % | 49 / 71 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 33 / 59 % | 82 / 99 % | 28 / 65 % | 65 / 84 % | 15 / 32 % | 46 / 68 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 16 / 90 % | 71 / 91 % | 60 / 79 % | 14 / 28 % | 18 / 44 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 28 / 48 % | 29 / 70 % | 66 / 79 % | 62 / 81 % | 11 / 28 % | 68 / 83 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 27 / 58 % | 66 / 98 % | 65 / 84 % | 44 / 67 % | 9 / 23 % | 26 / 43 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 35 / 90 % | 58 / 76 % | 9 / 25 % | 0 / 0 % | 7 / 14 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 31 / 50 % | 57 / 93 % | 51 / 69 % | 23 / 51 % | 9 / 22 % | 19 / 34 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 33 / 56 % | 46 / 86 % | 23 / 54 % | 52 / 74 % | 13 / 29 % | 57 / 73 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 28 / 96 % | 45 / 76 % | 13 / 30 % | 3 / 8 % | 12 / 20 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 42 / 92 % | 25 / 40 % | 15 / 36 % | 5 / 14 % | 8 / 18 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 9 / 26 % | 41 / 97 % | 8 / 59 % | 18 / 43 % | 3 / 10 % | 7 / 22 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 22 / 47 % | 34 / 94 % | 21 / 66 % | 39 / 71 % | 6 / 20 % | 22 / 50 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 57 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 34 / 75 % | 24 / 42 % | 9 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 15 / 36 % | 0 / 0 % | 29 / 68 % | 9 / 28 % | 5 / 14 % | 10 / 23 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 29 / 69 % | 9 / 47 % | 11 / 28 % | 2 / 9 % | 9 / 21 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 45 % | 15 / 93 % | 15 / 38 % | 25 / 54 % | 3 / 16 % | 14 / 34 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 25 / 73 % | 24 / 49 % | 12 / 33 % | 1 / 6 % | 6 / 12 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 34 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 3 / 9 % | 11 / 20 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 6 / 89 % | 11 / 35 % | 14 / 38 % | 3 / 12 % | 8 / 24 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 12 / 35 % | 8 / 79 % | 0 / 0 % | 11 / 32 % | 4 / 14 % | 12 / 27 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 1 / 8 % | 10 / 24 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 26 % | 1 / 4 % | 7 / 14 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 69 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 2 / 22 % | 8 / 25 % | 2 / 6 % | 9 / 18 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 1 / 6 % | 7 / 16 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 81 % | 0 / 0 % | 8 / 21 % | 3 / 9 % | 5 / 11 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 1 / 4 % | 4 / 8 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 53 % | 0 / 0 % | 6 / 17 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 3 / 7 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 5 / 10 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 4 / 6 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 52 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
