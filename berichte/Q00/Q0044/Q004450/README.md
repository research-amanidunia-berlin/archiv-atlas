[English](README.md) · [Deutsch](README.de.md)

# https://docs.x.ai/grok-bot/security-faq.md

Report Q004450 · Source docs.x.ai · Date – · [Open original](https://docs.x.ai/grok-bot/security-faq.md)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Die FAQ beschreibt Nutzerisolation, Zugriffs-, Netzwerk-, Prüf- und Protokollierungskontrollen für Grok Bot; viele davon sind Enterprise-Funktionen. Sie nennt auch Grenzen: Bots eines Nutzers teilen dessen Computer, Website-Zugriffe werden durch App-Sperren nicht verhindert, manche Netzwerkblockaden sind nur Best-Effort, und Auto Review deckt nicht alle Nebenwirkungen ab. Die Angaben stammen vom Anbieter und werden im Bericht nicht unabhängig belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 66 / 79 % | 100 / 100 % | 100 / 100 % | 89 / 94 % | 67 / 80 % | 75 / 84 % | 85 / 92 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 25 / 46 % | 77 / 96 % | 98 / 99 % | 56 / 75 % | 23 / 46 % | 25 / 46 % | 16 / 37 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 58 / 74 % | 94 / 98 % | 94 / 96 % | 78 / 87 % | 56 / 73 % | 80 / 88 % | 60 / 73 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 42 / 57 % | 82 / 92 % | 93 / 96 % | 62 / 79 % | 37 / 55 % | 50 / 69 % | 22 / 44 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 44 / 68 % | 89 / 92 % | 15 / 32 % | 3 / 9 % | 7 / 14 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 56 / 85 % | 27 / 50 % | 11 / 23 % | 6 / 14 % | 8 / 15 % | 2 / 7 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 47 / 68 % | 34 / 59 % | 21 / 47 % | 0 / 0 % | 8 / 18 % | 2 / 6 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 36 / 72 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 51 % | 0 / 0 % | 0 / 0 % | 23 / 48 % | 16 / 30 % | 28 / 47 % | 9 / 18 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 33 / 62 % | 11 / 27 % | 12 / 28 % | 0 / 0 % | 12 / 26 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 30 / 46 % | 7 / 17 % | 1 / 5 % | 4 / 8 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 35 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 27 % | 0 / 0 % | 10 / 18 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 27 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 3 % | 7 / 12 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 27 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 25 % | 4 / 11 % | 9 / 16 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 1 / 4 % | 10 / 17 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 2 / 7 % | 8 / 20 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 4 % | 5 / 10 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 1 / 6 % | 5 / 9 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 6 / 9 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 2 / 6 % | 4 / 8 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 6 % | 6 / 11 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 2 % | 6 / 11 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | – |
