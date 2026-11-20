[English](README.md) · [Deutsch](README.de.md)

# GTIG AI Threat Tracker: From Prompting to Autonomy – The Evolution of Adversarial AI

Report Q000136 · Source cloud.google.com · Date 2026-09-08 · [Open original](https://cloud.google.com/blog/topics/threat-intelligence/from-prompting-to-autonomy-the-evolution-of-adversarial-ai/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

GTIG berichtet, dass Angreifer KI zunehmend mit Agenten und automatisierten Abläufen für Lieferkettenangriffe, Diebstahl von KI-Eigentum, Aufklärung und Zugangsdatenraub einsetzen. Die Gruppe nennt auch Grenzen ihrer Beobachtungen: Sie habe keine vollständig autonomen Exploit-Pipelines gegen Ziele und bei untersuchten Einflusskampagnen keine erfolgreichen interaktiven Bots festgestellt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 29 / 52 % | 98 / 100 % | 62 / 83 % | 94 / 97 % | 73 / 86 % | 74 / 86 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 57 / 75 % | 84 / 92 % | 95 / 98 % | 84 / 93 % | 89 / 93 % | 91 / 93 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 50 % | 81 / 91 % | 18 / 53 % | 94 / 98 % | 62 / 81 % | 58 / 76 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 35 / 54 % | 93 / 100 % | 10 / 37 % | 89 / 97 % | 43 / 72 % | 31 / 57 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 41 / 57 % | 81 / 89 % | 54 / 61 % | 76 / 84 % | 71 / 85 % | 62 / 73 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 3 / 48 % | 2 / 8 % | 81 / 89 % | 23 / 50 % | 8 / 18 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 20 / 44 % | 76 / 93 % | 36 / 71 % | 81 / 90 % | 71 / 85 % | 59 / 76 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 24 / 46 % | 35 / 94 % | 9 / 22 % | 36 / 57 % | 61 / 79 % | 79 / 88 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 58 / 96 % | 4 / 14 % | 74 / 85 % | 52 / 74 % | 22 / 50 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 21 / 42 % | 62 / 90 % | 4 / 20 % | 46 / 68 % | 38 / 66 % | 40 / 69 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 31 / 53 % | 55 / 92 % | 19 / 48 % | 61 / 79 % | 43 / 70 % | 36 / 54 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 6 / 37 % | 0 / 4 % | 56 / 66 % | 30 / 59 % | 20 / 46 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 41 / 84 % | 10 / 26 % | 35 / 59 % | 44 / 70 % | 34 / 59 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 18 / 42 % | 40 / 87 % | 8 / 38 % | 28 / 59 % | 21 / 48 % | 27 / 50 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 38 / 77 % | 3 / 18 % | 29 / 53 % | 25 / 49 % | 25 / 51 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 36 / 84 % | 2 / 9 % | 37 / 54 % | 18 / 42 % | 21 / 45 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 36 / 72 % | 0 / 3 % | 21 / 47 % | 9 / 29 % | 7 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 10 / 35 % | 35 / 75 % | 4 / 19 % | 11 / 47 % | 9 / 26 % | 16 / 41 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 18 / 43 % | 34 / 98 % | 13 / 46 % | 4 / 50 % | 32 / 60 % | 12 / 34 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 34 / 62 % | 3 / 11 % | 26 / 58 % | 19 / 49 % | 16 / 39 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 46 % | 0 / 0 % | 4 / 15 % | 0 / 0 % | 27 / 59 % | 33 / 60 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 27 / 59 % | 0 / 0 % | 30 / 52 % | 7 / 17 % | 6 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 12 / 58 % | 0 / 4 % | 25 / 48 % | 7 / 23 % | 9 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 23 / 36 % | 1 / 4 % | 22 / 32 % | 22 / 46 % | 13 / 26 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 8 % | 20 / 54 % | 7 / 23 % | 7 / 18 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 15 / 67 % | 2 / 10 % | 0 / 0 % | 16 / 44 % | 19 / 41 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 18 / 62 % | 0 / 4 % | 0 / 0 % | 7 / 20 % | 7 / 16 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 17 / 63 % | 0 / 0 % | 3 / 14 % | 7 / 21 % | 6 / 14 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 2 / 46 % | 1 / 7 % | 8 / 31 % | 16 / 47 % | 13 / 39 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 40 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 28 % | 13 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 12 / 36 % | 6 / 16 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 28 % | 11 / 22 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 10 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 10 / 31 % | 10 / 21 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 10 / 20 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 10 / 23 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 42 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 9 / 19 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 30 % | 6 / 20 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 8 / 21 % | 7 / 16 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 3 / 71 % | 1 / 6 % | 1 / 22 % | 8 / 29 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 7 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 7 / 15 % |
