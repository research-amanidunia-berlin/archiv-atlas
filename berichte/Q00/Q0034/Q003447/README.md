[English](README.md) · [Deutsch](README.de.md)

# Developing a computer use model

Report Q003447 · Source anthropic.com · Date 2024-10-22 · [Open original](https://www.anthropic.com/news/developing-computer-use)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet über eine öffentliche Beta, in der Claude 3.5 Sonnet Computer per Bildschirm-Screenshots, Cursorbewegungen, Klicks und Texteingaben bedienen kann. Das Unternehmen nennt bessere Benchmarkwerte als bei anderen KI-Modellen, aber einen großen Abstand zu menschlicher Leistung, und verweist auf Prompt-Injection- und Missbrauchsrisiken samt Schutzmaßnahmen. Die Bedienung ist laut Bericht noch langsam und fehleranfällig; manche Aktionen und kurzlebige Bildschirminhalte kann Claude nicht zuverlässig erfassen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 36 / 55 % | 99 / 100 % | 100 / 100 % | 61 / 80 % | 17 / 41 % | 51 / 70 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 41 / 61 % | 97 / 99 % | 99 / 100 % | 64 / 82 % | 15 / 38 % | 46 / 64 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 27 / 48 % | 84 / 99 % | 89 / 95 % | 36 / 65 % | 13 / 33 % | 43 / 63 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 14 / 32 % | 13 / 71 % | 83 / 90 % | 17 / 45 % | 3 / 12 % | 20 / 41 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 25 / 70 % | 82 / 93 % | 10 / 29 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 23 / 39 % | 55 / 94 % | 78 / 91 % | 26 / 53 % | 3 / 16 % | 18 / 42 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 21 / 45 % | 76 / 97 % | 75 / 91 % | 33 / 61 % | 8 / 25 % | 25 / 47 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 11 / 38 % | 76 / 90 % | 7 / 23 % | 1 / 5 % | 8 / 15 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 50 / 84 % | 73 / 85 % | 11 / 32 % | 3 / 8 % | 15 / 32 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 70 / 84 % | 25 / 50 % | 4 / 13 % | 6 / 13 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 30 % | 51 / 83 % | 70 / 86 % | 11 / 30 % | 3 / 10 % | 9 / 21 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 63 / 91 % | 3 / 11 % | 7 / 18 % | 1 / 6 % | 5 / 13 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 25 / 46 % | 59 / 88 % | 41 / 78 % | 38 / 66 % | 9 / 26 % | 28 / 49 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 38 % | 55 / 95 % | 23 / 51 % | 10 / 29 % | 3 / 14 % | 14 / 29 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 28 % | 0 / 0 % | 39 / 64 % | 7 / 24 % | 1 / 6 % | 6 / 14 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 36 % | 18 / 57 % | 30 / 58 % | 34 / 60 % | 8 / 21 % | 19 / 38 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 34 / 79 % | 0 / 0 % | 14 / 30 % | 2 / 7 % | 11 / 21 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 13 / 60 % | 33 / 57 % | 13 / 31 % | 5 / 13 % | 8 / 16 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 31 / 58 % | 9 / 40 % | 10 / 29 % | 0 / 3 % | 9 / 20 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 23 / 56 % | 2 / 16 % | 9 / 25 % | 2 / 7 % | 6 / 14 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 33 % | 21 / 76 % | 4 / 25 % | 17 / 40 % | 8 / 23 % | 22 / 41 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 13 / 26 % | 0 / 0 % | 21 / 40 % | 11 / 30 % | 2 / 8 % | 7 / 15 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 36 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 14 / 38 % | 0 / 0 % | 0 / 0 % | 9 / 25 % | 3 / 12 % | 13 / 29 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 30 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 2 / 7 % | 11 / 23 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 26 % | 0 / 0 % | 3 / 12 % | 12 / 33 % | 4 / 15 % | 9 / 21 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 33 % | 1 / 5 % | 6 / 13 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 29 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 1 / 5 % | 11 / 23 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 11 / 55 % | 0 / 0 % | 6 / 17 % | 1 / 7 % | 4 / 10 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 9 / 27 % | 8 / 19 % | 2 / 8 % | 7 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 1 / 4 % | 6 / 15 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 3 / 38 % | 4 / 23 % | 8 / 23 % | 4 / 12 % | 5 / 14 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 2 % | 4 / 8 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 63 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 4 / 11 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 2 / 39 % | 0 / 0 % | 5 / 10 % | 1 / 2 % | 5 / 8 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 4 / 7 % | – | – |
