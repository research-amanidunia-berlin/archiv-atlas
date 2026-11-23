[English](README.md) · [Deutsch](README.de.md)

# Addendum to GPT-6 Astra System Card: GPT-6.1 Sol

Report Q000065 · Source deploymentsafety.openai.com · Date 2026-09-29 · [Open original](https://deploymentsafety.openai.com/gpt-6-1-sol)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, dass GPT-6.1 Sol GPT-6 Astra in vielen Sicherheits- und Gesundheitstests nahekommt oder GPT-6 Sol übertrifft; zugleich stuft es das Modell im Cyberbereich als „Critical“ und bei Bio-Chemie als „High“ ein. Einzelne Tests zeigen Schwächen und unerwünschte Beharrlichkeit; die oft adversarialen Ergebnisse sind laut Bericht nicht repräsentativ für durchschnittlichen Produktionsverkehr.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 64 / 80 % | 98 / 99 % | 100 / 100 % | 81 / 89 % | 50 / 68 % | 80 / 88 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 60 / 77 % | 100 / 100 % | 100 / 100 % | 84 / 90 % | 64 / 78 % | 76 / 86 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 56 / 73 % | 85 / 97 % | 100 / 100 % | 84 / 91 % | 48 / 69 % | 72 / 86 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 44 / 64 % | 78 / 97 % | 99 / 100 % | 82 / 90 % | 26 / 42 % | 19 / 43 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 68 / 81 % | 93 / 95 % | 98 / 99 % | 90 / 94 % | 23 / 40 % | 67 / 81 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 36 / 58 % | 96 / 99 % | 92 / 96 % | 72 / 85 % | 17 / 36 % | 39 / 59 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 50 / 68 % | 86 / 97 % | 94 / 96 % | 85 / 91 % | 66 / 81 % | 89 / 93 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 43 / 64 % | 93 / 99 % | 88 / 92 % | 71 / 85 % | 55 / 72 % | 81 / 90 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 52 / 71 % | 90 / 99 % | 79 / 91 % | 76 / 87 % | 22 / 40 % | 70 / 84 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 31 / 53 % | 85 / 97 % | 88 / 92 % | 40 / 66 % | 13 / 26 % | 32 / 52 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 43 / 66 % | 78 / 93 % | 31 / 43 % | 78 / 88 % | 45 / 64 % | 80 / 88 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 59 / 94 % | 71 / 85 % | 13 / 30 % | 4 / 11 % | 9 / 20 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 43 / 63 % | 34 / 79 % | 66 / 83 % | 66 / 83 % | 10 / 24 % | 32 / 55 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 65 / 79 % | 16 / 41 % | 2 / 8 % | 5 / 12 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 25 / 60 % | 60 / 74 % | 12 / 28 % | 0 / 0 % | 8 / 15 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 58 / 87 % | 56 / 72 % | 27 / 54 % | 5 / 14 % | 13 / 30 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 19 / 36 % | 50 / 95 % | 38 / 58 % | 56 / 73 % | 5 / 15 % | 33 / 47 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 55 / 86 % | 34 / 58 % | 9 / 24 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 47 / 72 % | 20 / 40 % | 18 / 36 % | 0 / 0 % | 9 / 19 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 39 / 70 % | 0 / 0 % | 8 / 20 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 38 / 75 % | 26 / 48 % | 12 / 29 % | 3 / 9 % | 8 / 17 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 38 / 91 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 16 / 42 % | 37 / 96 % | 4 / 16 % | 23 / 48 % | 9 / 22 % | 28 / 50 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 33 / 86 % | 5 / 29 % | 16 / 36 % | 3 / 10 % | 6 / 13 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 17 / 42 % | 32 / 90 % | 0 / 0 % | 15 / 40 % | 6 / 14 % | 14 / 29 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 31 / 66 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 5 / 9 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 21 / 53 % | 0 / 0 % | 0 / 0 % | 30 / 56 % | 7 / 17 % | 12 / 24 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 10 / 77 % | 28 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 25 / 61 % | 0 / 0 % | 0 / 0 % | 15 / 38 % | 5 / 16 % | 22 / 50 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 21 / 64 % | 0 / 0 % | 6 / 16 % | 2 / 6 % | 4 / 9 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 33 % | 10 / 51 % | 0 / 0 % | 10 / 28 % | 4 / 11 % | 9 / 22 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 28 % | 1 / 5 % | 5 / 12 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 11 / 51 % | 9 / 21 % | 9 / 24 % | 3 / 8 % | 10 / 21 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 28 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 19 % | 0 / 0 % | 6 / 12 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 2 / 7 % | 0 / 0 % | – | – |
