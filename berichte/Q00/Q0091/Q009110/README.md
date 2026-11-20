[English](README.md) · [Deutsch](README.de.md)

# Introducing Superalignment

Report Q009110 · Source openai.com · Date 2023-07-05 · [Open original](https://openai.com/index/introducing-superalignment/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI kündigt ein vierjähriges Forschungsprogramm an, das Superintelligenz durch automatisierte Aufsicht, Prüfungen auf problematisches Verhalten und adversariale Tests an menschliche Absichten binden soll. Dafür plant das Unternehmen ein neues Team und den Einsatz von 20 Prozent seiner bislang gesicherten Rechenleistung; es bezeichnet das Ziel als ambitioniert und den Erfolg als ungewiss. Der Bericht beschreibt Vorhaben und Erwartungen, keine bereits abgeschlossene Lösung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 26 / 48 % | 92 / 99 % | – | 83 / 95 % | 30 / 61 % | 8 / 25 % | 25 / 51 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 28 / 55 % | 76 / 98 % | – | 72 / 96 % | 37 / 68 % | 17 / 46 % | 38 / 65 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 36 / 68 % | – | 72 / 90 % | 11 / 36 % | 1 / 10 % | 11 / 29 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 19 / 88 % | – | 62 / 76 % | 10 / 28 % | 1 / 6 % | 10 / 26 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 24 / 52 % | 50 / 96 % | – | 57 / 81 % | 29 / 57 % | 8 / 28 % | 30 / 51 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 32 / 56 % | 32 / 89 % | – | 56 / 85 % | 57 / 79 % | 23 / 49 % | 57 / 75 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 33 % | 57 / 92 % | – | 42 / 66 % | 15 / 40 % | 3 / 16 % | 8 / 31 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 52 / 91 % | – | 3 / 15 % | 7 / 19 % | 1 / 6 % | 5 / 14 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 45 / 89 % | – | 32 / 76 % | 15 / 37 % | 2 / 10 % | 8 / 19 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 9 / 37 % | 44 / 91 % | – | 5 / 47 % | 11 / 39 % | 2 / 12 % | 10 / 31 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 10 / 35 % | 25 / 77 % | – | 43 / 79 % | 13 / 35 % | 3 / 12 % | 9 / 25 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 25 / 50 % | 42 / 80 % | – | 32 / 65 % | 23 / 53 % | 7 / 28 % | 28 / 58 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 38 / 76 % | – | 14 / 30 % | 12 / 33 % | 2 / 13 % | 7 / 20 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 33 / 80 % | – | 11 / 44 % | 10 / 29 % | 2 / 7 % | 8 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 35 % | 33 / 90 % | – | 2 / 29 % | 14 / 39 % | 4 / 18 % | 10 / 27 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 33 % | 20 / 85 % | – | 33 / 49 % | 7 / 25 % | 2 / 11 % | 5 / 17 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 21 / 54 % | – | 24 / 49 % | 11 / 27 % | 1 / 4 % | 8 / 14 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 19 / 78 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 16 / 46 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 29 % | 1 / 6 % | 15 / 32 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 14 / 86 % | – | 11 / 34 % | 9 / 28 % | 1 / 4 % | 9 / 19 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 32 % | 0 / 0 % | – | 2 / 11 % | 11 / 33 % | 0 / 0 % | 12 / 21 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 12 / 67 % | – | 9 / 36 % | 10 / 30 % | 1 / 7 % | 4 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 12 / 69 % | – | 1 / 8 % | 7 / 25 % | 1 / 8 % | 4 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 44 % | – | 0 / 0 % | 10 / 33 % | 0 / 0 % | 11 / 21 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 8 / 30 % | 3 / 38 % | – | 9 / 32 % | 11 / 34 % | 2 / 10 % | 7 / 26 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 9 / 43 % | – | 0 / 0 % | 8 / 27 % | 0 / 0 % | 5 / 11 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 4 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 1 / 22 % | – | 2 / 17 % | 5 / 13 % | 0 / 0 % | 6 / 13 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 24 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 6 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 13 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 4 % | 6 / 11 % | 0 / 0 % | 4 / 9 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 2 / 47 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 4 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 2 % | 4 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 4 / 50 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 4 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 12 % |
