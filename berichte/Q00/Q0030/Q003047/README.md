[English](README.md) · [Deutsch](README.de.md)

# Update on ARC's recent eval efforts

Report Q003047 · Source metr.org · Date 2023-03-17 · [Open original](https://metr.org/blog/2023-03-18-update-on-recent-evals/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

ARC zufolge konnten die getesteten Claude- und GPT-4-Versionen keinen vollständigen Plan zur autonomen Selbstreplikation zuverlässig entwickeln und ausführen, beherrschten aber mehrere dafür relevante Teilaufgaben und konnten Menschen einbeziehen. Der Bericht ist ein vorläufiger Überblick mit menschlicher Aufsicht und simulierten Versuchsteilen; METR fordert daher systematische Prüfungen künftiger, leistungsfähigerer Modelle.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 58 % | 95 / 100 % | 38 / 76 % | 99 / 100 % | 54 / 79 % | 28 / 61 % | 59 / 78 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 46 / 70 % | 85 / 96 % | 42 / 79 % | 99 / 100 % | 70 / 85 % | 17 / 53 % | 60 / 76 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 60 % | 93 / 100 % | 45 / 82 % | 97 / 99 % | 51 / 77 % | 43 / 72 % | 67 / 82 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 51 / 71 % | 90 / 100 % | 69 / 91 % | 95 / 99 % | 17 / 41 % | 48 / 74 % | 64 / 80 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 46 % | 75 / 99 % | 8 / 30 % | 89 / 96 % | 30 / 56 % | 9 / 21 % | 24 / 43 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 44 / 61 % | 88 / 99 % | 18 / 45 % | 81 / 90 % | 56 / 78 % | 18 / 45 % | 42 / 64 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 52 / 88 % | 14 / 42 % | 77 / 86 % | 60 / 79 % | 16 / 42 % | 63 / 77 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 24 / 60 % | 1 / 5 % | 76 / 87 % | 10 / 29 % | 2 / 14 % | 10 / 21 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 29 / 47 % | 42 / 92 % | 14 / 52 % | 72 / 93 % | 58 / 79 % | 11 / 33 % | 51 / 66 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 27 / 54 % | 71 / 99 % | 37 / 71 % | 50 / 88 % | 55 / 80 % | 27 / 55 % | 57 / 77 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 22 / 50 % | 57 / 94 % | 3 / 21 % | 68 / 89 % | 20 / 49 % | 13 / 42 % | 28 / 52 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 24 / 52 % | 64 / 89 % | 6 / 28 % | 53 / 77 % | 28 / 55 % | 10 / 30 % | 12 / 26 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 62 / 91 % | 1 / 7 % | 50 / 79 % | 9 / 28 % | 2 / 11 % | 7 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 25 / 61 % | 3 / 15 % | 60 / 83 % | 35 / 63 % | 8 / 25 % | 8 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 18 / 43 % | 60 / 89 % | 9 / 29 % | 26 / 60 % | 39 / 65 % | 16 / 45 % | 41 / 61 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 36 / 60 % | 44 / 94 % | 13 / 43 % | 47 / 70 % | 44 / 70 % | 23 / 44 % | 48 / 65 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 41 / 97 % | 6 / 29 % | 45 / 70 % | 23 / 52 % | 6 / 31 % | 13 / 28 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 29 / 63 % | 0 / 3 % | 40 / 67 % | 14 / 39 % | 2 / 8 % | 10 / 21 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 35 / 91 % | 1 / 12 % | 1 / 13 % | 9 / 24 % | 3 / 12 % | 8 / 19 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 32 / 80 % | 0 / 2 % | 17 / 59 % | 5 / 13 % | 1 / 5 % | 5 / 9 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 32 / 77 % | 0 / 3 % | 2 / 15 % | 7 / 21 % | 4 / 16 % | 6 / 14 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 29 / 66 % | 1 / 7 % | 4 / 28 % | 8 / 23 % | 3 / 10 % | 8 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 48 % | 0 / 3 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 9 / 47 % | 1 / 12 % | 26 / 59 % | 9 / 31 % | 3 / 16 % | 6 / 19 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 24 / 69 % | 0 / 0 % | 0 / 0 % | 10 / 27 % | 0 / 2 % | 9 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 23 / 72 % | 0 / 2 % | 7 / 25 % | 7 / 16 % | 1 / 4 % | 9 / 20 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 13 / 35 % | 21 / 88 % | 2 / 13 % | 19 / 49 % | 15 / 45 % | 5 / 18 % | 16 / 37 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 18 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 18 / 54 % | 0 / 3 % | 3 / 30 % | 7 / 20 % | 4 / 12 % | 6 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 16 / 57 % | 0 / 3 % | 0 / 0 % | 11 / 31 % | 1 / 5 % | 9 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 37 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 21 % | 2 / 9 % | 12 / 24 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 10 / 85 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 2 / 11 % | 5 / 13 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 6 / 93 % | 0 / 6 % | 2 / 30 % | 9 / 26 % | 2 / 9 % | 5 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 6 / 92 % | 0 / 0 % | 8 / 47 % | 6 / 20 % | 1 / 5 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 24 % | 7 / 20 % | 1 / 8 % | 7 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 6 % | 5 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 5 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 6 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 4 / 88 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 5 / 8 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 1 % | 4 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 6 % | 3 / 6 % |
