[English](README.md) · [Deutsch](README.de.md)

# GPT-6 Sol and GPT-6 Luna: October 2026 update

Report Q000082 · Source deploymentsafety.openai.com · Date 2026-10-07 · [Open original](https://deploymentsafety.openai.com/gpt-6-october)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet für GPT‑6 Sol und Luna von Verbesserungen bei mehreren Tests zu Jailbreaks, Faktenrichtigkeit und Gesundheit, zugleich aber von Rückgängen in einzelnen Sicherheits- und Jugendtests. Die Bewertungen beruhen vielfach auf gezielt schwierigen Fällen ohne systemweite Schutzmaßnahmen und sind laut Bericht keine Schätzung des typischen Produktbetriebs.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 62 / 76 % | 96 / 98 % | 91 / 96 % | 100 / 100 % | 81 / 89 % | 80 / 88 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 63 / 77 % | 93 / 95 % | 91 / 95 % | 100 / 100 % | 90 / 94 % | 72 / 83 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 48 / 67 % | 99 / 100 % | 49 / 76 % | 100 / 100 % | 74 / 87 % | 79 / 89 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 48 / 66 % | 100 / 100 % | 71 / 84 % | 98 / 99 % | 83 / 90 % | 74 / 85 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 53 / 69 % | 93 / 99 % | 80 / 90 % | 100 / 100 % | 85 / 92 % | 81 / 90 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 38 / 58 % | 75 / 94 % | 24 / 41 % | 97 / 98 % | 74 / 87 % | 16 / 32 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 48 / 66 % | 78 / 96 % | 61 / 79 % | 95 / 97 % | 85 / 91 % | 87 / 93 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 32 / 54 % | 95 / 98 % | 8 / 19 % | 93 / 96 % | 44 / 69 % | 37 / 56 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 53 / 70 % | 93 / 99 % | 30 / 53 % | 91 / 96 % | 77 / 88 % | 66 / 80 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 28 / 48 % | 91 / 97 % | 60 / 73 % | 93 / 95 % | 71 / 85 % | 67 / 79 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 41 / 59 % | 56 / 89 % | 22 / 46 % | 86 / 93 % | 74 / 87 % | 47 / 66 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 40 / 60 % | 73 / 91 % | 15 / 20 % | 50 / 62 % | 73 / 86 % | 77 / 85 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 66 / 86 % | 0 / 3 % | 0 / 0 % | 9 / 24 % | 6 / 13 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 63 / 76 % | 14 / 36 % | 7 / 13 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 59 / 77 % | 16 / 41 % | 7 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 54 / 88 % | 1 / 5 % | 50 / 62 % | 27 / 56 % | 18 / 38 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 20 / 55 % | 1 / 6 % | 54 / 72 % | 15 / 34 % | 14 / 26 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 35 % | 43 / 93 % | 5 / 12 % | 3 / 11 % | 25 / 50 % | 46 / 65 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 43 / 68 % | 1 / 7 % | 30 / 54 % | 13 / 36 % | 8 / 18 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 34 / 54 % | 9 / 26 % | 5 / 13 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 28 / 65 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 17 / 44 % | 18 / 40 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 18 / 42 % | 28 / 73 % | 3 / 10 % | 0 / 0 % | 17 / 44 % | 18 / 37 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 45 % | 0 / 0 % | 2 / 8 % | 0 / 0 % | 28 / 56 % | 10 / 18 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 27 / 57 % | 0 / 0 % | 0 / 0 % | 12 / 32 % | 9 / 18 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 8 / 57 % | 0 / 2 % | 5 / 14 % | 14 / 34 % | 6 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 10 / 30 % | 11 / 22 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 5 / 16 % | 9 / 25 % | 11 / 23 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 2 / 15 % | 11 / 27 % | 6 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 11 / 30 % | 8 / 18 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 7 / 14 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 10 / 62 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 5 / 10 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 6 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 6 / 9 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 24 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 5 / 8 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % |
