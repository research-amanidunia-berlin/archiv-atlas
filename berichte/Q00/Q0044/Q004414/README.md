[English](README.md) · [Deutsch](README.de.md)

# https://docs.x.ai/grok-bot/security.md

Report Q004414 · Source docs.x.ai · Date – · [Open original](https://docs.x.ai/grok-bot/security.md)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt Netzwerkregeln, Genehmigungen, Auto Review, Identitäts- und Datenkontrollen für Grok Bot; viele Verwaltungsfunktionen seien Enterprise vorbehalten. Er hebt Grenzen hervor: Netzwerk-Sperren seien keine verlässliche Sicherheitsgrenze, Auto Review erfasse nicht alle Nebenwirkungen und Prompt-Injection-Risiken würden reduziert, aber nicht beseitigt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 78 / 87 % | 100 / 100 % | 89 / 95 % | 100 / 100 % | 90 / 94 % | 82 / 90 % | 86 / 91 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 65 / 76 % | 94 / 97 % | 67 / 79 % | 98 / 99 % | 85 / 91 % | 71 / 84 % | 89 / 93 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 51 / 66 % | 87 / 96 % | 31 / 57 % | 95 / 97 % | 72 / 85 % | 59 / 76 % | 73 / 84 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 34 / 47 % | 87 / 93 % | 2 / 8 % | 95 / 96 % | 41 / 64 % | 10 / 21 % | 19 / 33 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 14 / 31 % | 67 / 97 % | 4 / 12 % | 66 / 77 % | 31 / 56 % | 12 / 29 % | 22 / 43 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 25 / 38 % | 36 / 66 % | 4 / 10 % | 63 / 82 % | 31 / 60 % | 5 / 12 % | 13 / 22 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 57 / 76 % | 9 / 20 % | 1 / 4 % | 4 / 8 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 55 / 91 % | 1 / 6 % | 0 / 0 % | 20 / 47 % | 4 / 17 % | 16 / 38 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 47 / 70 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 6 / 17 % | 8 / 13 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 7 / 18 % | 26 / 56 % | 0 / 0 % | 0 / 0 % | 42 / 63 % | 5 / 11 % | 8 / 16 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 41 / 91 % | 4 / 10 % | 30 / 58 % | 14 / 30 % | 5 / 13 % | 9 / 17 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 39 / 72 % | 0 / 0 % | 0 / 0 % | 13 / 28 % | 3 / 9 % | 9 / 17 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 48 % | 0 / 0 % | 10 / 21 % | 0 / 0 % | 27 / 54 % | 25 / 45 % | 39 / 57 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 39 / 65 % | 0 / 0 % | 0 / 0 % | 19 / 39 % | 3 / 8 % | 9 / 15 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 38 / 59 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 4 / 10 % | 16 / 25 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 36 / 66 % | 3 / 7 % | 0 / 0 % | 10 / 21 % | 3 / 9 % | 8 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 32 / 89 % | 0 / 0 % | 31 / 59 % | 15 / 35 % | 0 / 1 % | 16 / 28 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 29 / 74 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 4 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 27 / 63 % | 0 / 0 % | 0 / 0 % | 13 / 32 % | 3 / 10 % | 16 / 27 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 27 / 46 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 5 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 22 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 26 % | 2 / 11 % | 7 / 14 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 25 % | 3 / 7 % | 12 / 19 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 26 % | 5 / 11 % | 7 / 14 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 10 / 40 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 7 % | 5 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 10 / 15 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 2 / 9 % | 10 / 23 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 9 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 5 % | 8 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 3 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % | 6 / 10 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 3 % | 5 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 6 / 43 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 6 / 11 % |
