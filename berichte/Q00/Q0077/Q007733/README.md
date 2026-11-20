[English](README.md) · [Deutsch](README.de.md)

# Designing AI agents to resist prompt injection

Report Q007733 · Source openai.com · Date 2026-03-11 · [Open original](https://openai.com/index/designing-agents-to-resist-prompt-injection/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht sagt, dass Prompt-Injection-Angriffe zunehmend als soziale Manipulation auftreten und sich nicht zuverlässig allein durch Filter erkennen lassen. OpenAI beschreibt Schutzmaßnahmen, die riskante Datenübermittlungen erkennen, eine Bestätigung verlangen oder sie blockieren sollen; umfassende Wirksamkeitskennzahlen nennt der Text nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 42 / 54 % | 89 / 98 % | – | 100 / 100 % | 68 / 83 % | 58 / 74 % | 33 / 57 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 57 / 74 % | 96 / 99 % | – | 100 / 100 % | 85 / 92 % | 78 / 87 % | 51 / 73 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 30 / 40 % | 59 / 88 % | – | 95 / 98 % | 16 / 32 % | 13 / 28 % | 6 / 15 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 31 / 46 % | 73 / 99 % | – | 92 / 97 % | 42 / 68 % | 33 / 55 % | 11 / 28 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 28 / 81 % | – | 75 / 87 % | 9 / 26 % | 6 / 11 % | 1 / 4 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 39 / 93 % | – | 63 / 78 % | 27 / 56 % | 26 / 46 % | 6 / 14 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 29 % | 61 / 97 % | – | 21 / 43 % | 35 / 58 % | 39 / 57 % | 19 / 39 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 42 / 96 % | – | 39 / 77 % | 8 / 22 % | 5 / 10 % | 2 / 6 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 43 % | 0 / 0 % | – | 32 / 52 % | 13 / 37 % | 22 / 39 % | 6 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 31 / 92 % | – | 28 / 73 % | 10 / 31 % | 6 / 15 % | 0 / 3 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 11 / 28 % | 9 / 67 % | – | 30 / 64 % | 14 / 34 % | 7 / 16 % | 5 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 8 / 27 % | 24 / 72 % | – | 0 / 0 % | 5 / 11 % | 3 / 4 % | 0 / 1 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 23 / 71 % | – | 0 / 0 % | 11 / 31 % | 10 / 18 % | 1 / 4 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 23 / 63 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 9 / 72 % | – | 18 / 46 % | 21 / 47 % | 11 / 26 % | 7 / 27 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 8 / 85 % | – | 20 / 41 % | 7 / 17 % | 7 / 16 % | 2 / 9 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 19 / 46 % | 5 / 14 % | 0 / 0 % | 1 / 5 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 14 / 71 % | – | 11 / 39 % | 8 / 22 % | 5 / 10 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 26 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 26 % | 0 / 0 % | – | 1 / 16 % | 9 / 27 % | 4 / 9 % | 3 / 9 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 10 / 27 % | 6 / 16 % | 0 / 0 % | 1 / 4 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 10 / 39 % | 0 / 0 % | 1 / 3 % | 0 / 1 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 28 % | 8 / 16 % | 1 / 3 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 54 % | – | 0 / 0 % | 0 / 0 % | 1 / 2 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 7 / 46 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 1 / 2 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 5 / 11 % | 1 / 2 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 1 / 2 % | 0 / 2 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 3 / 6 % | 0 / 1 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 5 / 17 % | 5 / 11 % | 0 / 0 % | 0 / 1 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 6 % | 5 / 14 % | 0 / 0 % | 1 / 2 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 4 / 10 % | 0 / 0 % | 1 / 2 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 65 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % |
