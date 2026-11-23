[English](README.md) · [Deutsch](README.de.md)

# AI Agent Security: Threats, Guardrails, Controls

Report Q000202 · Source codegeeks.solutions · Date 2026-10-28 · [Open original](https://www.codegeeks.solutions/blog/ai-agent-security-guide)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht empfiehlt, KI-Agenten durch minimale Rechte, getrennte Identitäten, Protokollierung und menschliche Freigaben für riskante Aktionen abzusichern. Seine Berechtigungsmatrix ist ein redaktioneller Vorschlag; die beschriebenen CodeGeeks-Beispiele sind laut Beitrag nicht durch agentenspezifische Testergebnisse oder Zertifizierungen belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 46 / 57 % | 84 / 97 % | 100 / 100 % | 78 / 89 % | 72 / 85 % | 75 / 86 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 82 / 91 % | 96 / 97 % | 100 / 100 % | 94 / 96 % | 95 / 97 % | 92 / 94 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 57 / 69 % | 99 / 100 % | 100 / 100 % | 92 / 95 % | 88 / 94 % | 92 / 95 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 25 / 40 % | 56 / 86 % | 93 / 98 % | 52 / 76 % | 16 / 31 % | 24 / 49 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 84 / 93 % | 93 / 97 % | 18 / 39 % | 14 / 29 % | 15 / 27 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 74 / 97 % | 65 / 93 % | 20 / 43 % | 11 / 24 % | 12 / 26 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 19 / 42 % | 61 / 94 % | 57 / 80 % | 48 / 72 % | 42 / 67 % | 70 / 83 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 48 / 90 % | 53 / 81 % | 16 / 44 % | 6 / 16 % | 17 / 38 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 52 / 84 % | 12 / 25 % | 7 / 20 % | 3 / 9 % | 6 / 12 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 30 % | 21 / 70 % | 51 / 75 % | 37 / 63 % | 10 / 25 % | 17 / 39 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 50 / 92 % | 30 / 77 % | 21 / 50 % | 2 / 8 % | 18 / 42 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 36 / 63 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 9 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 35 / 79 % | 2 / 15 % | 6 / 14 % | 2 / 4 % | 6 / 10 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 23 / 66 % | 28 / 36 % | 32 / 55 % | 16 / 32 % | 24 / 41 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 31 / 73 % | 20 / 37 % | 10 / 31 % | 7 / 18 % | 8 / 17 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 24 / 41 % | 0 / 0 % | 0 / 0 % | 12 / 38 % | 8 / 19 % | 27 / 53 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 27 / 78 % | 1 / 20 % | 0 / 0 % | 5 / 10 % | 6 / 12 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 21 / 48 % | 25 / 45 % | 6 / 13 % | 2 / 4 % | 0 / 0 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 7 / 23 % | 24 / 72 % | 8 / 53 % | 21 / 44 % | 6 / 14 % | 12 / 28 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 15 / 26 % | 23 / 67 % | 7 / 22 % | 16 / 40 % | 3 / 10 % | 13 / 26 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 20 / 72 % | 10 / 48 % | 15 / 36 % | 6 / 15 % | 17 / 31 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 13 / 32 % | 13 / 59 % | 0 / 0 % | 11 / 33 % | 5 / 10 % | 20 / 40 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 20 / 63 % | 0 / 0 % | 9 / 25 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 9 / 24 % | 6 / 41 % | 19 / 44 % | 8 / 18 % | 3 / 9 % | 6 / 11 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 19 / 90 % | 0 / 0 % | 7 / 18 % | 3 / 9 % | 6 / 12 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 13 / 65 % | 0 / 0 % | 6 / 13 % | 1 / 3 % | 5 / 8 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 11 / 49 % | 1 / 11 % | 8 / 20 % | 2 / 5 % | 6 / 11 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 10 / 34 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 10 / 93 % | 1 / 24 % | 9 / 24 % | 4 / 9 % | 5 / 10 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 5 / 46 % | 0 / 0 % | 8 / 24 % | 4 / 10 % | 9 / 24 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 48 % | 0 / 0 % | 9 / 23 % | 8 / 17 % | 7 / 14 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 5 % | 8 / 18 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 69 % | 0 / 12 % | 7 / 20 % | 2 / 8 % | 8 / 14 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 1 / 5 % | 5 / 11 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 5 / 13 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 7 / 13 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 4 / 9 % | 6 / 11 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 6 / 10 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 2 / 3 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 2 % | 6 / 10 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 36 % | 0 / 0 % | 6 / 13 % | 1 / 3 % | 5 / 10 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 5 / 8 % | – | – |
