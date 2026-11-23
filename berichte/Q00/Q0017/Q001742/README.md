[English](README.md) · [Deutsch](README.de.md)

# Trustworthy agents in practice

Report Q001742 · Source anthropic.com · Date 2026-04-09 · [Open original](https://www.anthropic.com/research/trustworthy-agents)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic beschreibt Agentensicherheit als Zusammenspiel von Modell, Schutzregeln, Werkzeugen und Einsatzumgebung. Der Bericht nennt Kontrollen, Nachfragen bei Unsicherheit und mehrschichtige Abwehr gegen Prompt-Injection, räumt aber ein, dass diese keinen vollständigen Schutz garantieren und standardisierte unabhängige Vergleichstests fehlen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 60 / 73 % | 93 / 97 % | 100 / 100 % | 89 / 94 % | 78 / 90 % | 89 / 93 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 79 / 90 % | 98 / 99 % | 100 / 100 % | 93 / 96 % | 92 / 96 % | 92 / 95 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 38 / 59 % | 96 / 98 % | 100 / 100 % | 66 / 85 % | 65 / 80 % | 68 / 82 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 30 / 48 % | 89 / 95 % | 96 / 99 % | 71 / 86 % | 31 / 60 % | 57 / 80 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 16 / 38 % | 47 / 87 % | 93 / 98 % | 45 / 71 % | 35 / 57 % | 32 / 67 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 15 / 37 % | 61 / 93 % | 91 / 96 % | 51 / 74 % | 26 / 49 % | 52 / 70 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 27 / 46 % | 85 / 96 % | 90 / 95 % | 65 / 82 % | 47 / 62 % | 67 / 80 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 10 / 31 % | 83 / 96 % | 89 / 98 % | 20 / 50 % | 10 / 23 % | 15 / 35 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 21 / 44 % | 59 / 80 % | 89 / 95 % | 64 / 83 % | 28 / 53 % | 63 / 81 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 43 % | 86 / 95 % | 87 / 95 % | 56 / 79 % | 49 / 65 % | 68 / 81 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 46 / 75 % | 85 / 94 % | 10 / 33 % | 3 / 11 % | 7 / 11 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 19 / 45 % | 76 / 95 % | 83 / 97 % | 68 / 83 % | 68 / 81 % | 80 / 88 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 24 / 48 % | 58 / 89 % | 75 / 90 % | 58 / 78 % | 59 / 77 % | 81 / 89 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 18 / 37 % | 72 / 87 % | 62 / 74 % | 46 / 68 % | 41 / 54 % | 51 / 66 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 19 / 40 % | 62 / 83 % | 65 / 81 % | 36 / 62 % | 28 / 45 % | 30 / 53 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 46 % | 58 / 85 % | 64 / 81 % | 30 / 53 % | 40 / 52 % | 58 / 74 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 15 / 27 % | 56 / 81 % | 60 / 81 % | 16 / 42 % | 9 / 19 % | 9 / 18 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 14 / 32 % | 55 / 90 % | 32 / 67 % | 25 / 47 % | 11 / 23 % | 23 / 36 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 53 / 89 % | 14 / 44 % | 8 / 27 % | 4 / 15 % | 7 / 13 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 13 / 28 % | 50 / 78 % | 28 / 79 % | 31 / 57 % | 14 / 33 % | 36 / 54 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 15 / 36 % | 46 / 82 % | 26 / 60 % | 11 / 37 % | 5 / 17 % | 8 / 19 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 40 / 70 % | 6 / 51 % | 9 / 28 % | 2 / 9 % | 8 / 17 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 29 % | 38 / 79 % | 26 / 81 % | 28 / 54 % | 27 / 44 % | 14 / 36 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 31 % | 37 / 79 % | 9 / 27 % | 18 / 43 % | 13 / 25 % | 17 / 32 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 31 / 64 % | 23 / 64 % | 37 / 62 % | 10 / 24 % | 16 / 33 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 35 / 73 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 9 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 13 / 20 % | 35 / 72 % | 4 / 35 % | 11 / 36 % | 5 / 14 % | 9 / 20 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 11 / 43 % | 34 / 65 % | 29 / 55 % | 25 / 53 % | 21 / 40 % | 14 / 30 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 9 / 22 % | 25 / 78 % | 10 / 32 % | 7 / 18 % | 7 / 16 % | 6 / 10 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 21 / 73 % | 0 / 14 % | 7 / 18 % | 5 / 16 % | 7 / 13 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 20 / 72 % | 0 / 0 % | 5 / 12 % | 2 / 8 % | 4 / 6 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 18 / 53 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 8 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 15 / 31 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 4 / 12 % | 11 / 27 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 12 / 34 % | 15 / 52 % | 2 / 12 % | 14 / 36 % | 13 / 24 % | 13 / 24 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 34 % | 0 / 0 % | 5 / 8 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 13 / 79 % | 0 / 0 % | 0 / 0 % | 2 / 5 % | 5 / 11 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 13 / 44 % | 0 / 0 % | 5 / 11 % | 5 / 13 % | 5 / 7 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 24 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 3 / 9 % | 8 / 15 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 2 / 8 % | 2 / 5 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 6 / 14 % | – | – |
