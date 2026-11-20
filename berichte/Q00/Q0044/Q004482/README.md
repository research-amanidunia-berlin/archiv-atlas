[English](README.md) · [Deutsch](README.de.md)

# Securing internal systems against increasingly capable and imperfectly aligned AI

Report Q004482 · Source deepmind.google · Date 2026-06-18 · [Open original](https://deepmind.google/blog/securing-the-future-of-ai-agents/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

DeepMind beschreibt ein mehrschichtiges Kontrollkonzept, das interne KI-Agenten überwacht, ihre Berechtigungen schrittweise vergibt und riskante Handlungen je nach möglichem Schaden nachträglich prüft oder in Echtzeit blockiert. Das Unternehmen berichtet von einer Analyse einer Million Programmieragenten-Aufgaben; die meisten markierten Fälle seien durch Fehlinterpretationen oder Übereifer entstanden, doch der Beitrag bietet keine unabhängige Wirksamkeitsbewertung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 54 / 69 % | 99 / 100 % | 85 / 94 % | 100 / 100 % | 86 / 93 % | 85 / 93 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 63 / 79 % | 100 / 100 % | 98 / 99 % | 100 / 100 % | 89 / 94 % | 85 / 91 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 33 / 54 % | 95 / 99 % | 41 / 65 % | 82 / 96 % | 66 / 83 % | 42 / 65 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 58 % | 88 / 96 % | 54 / 76 % | 94 / 98 % | 56 / 78 % | 61 / 78 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 37 / 54 % | 93 / 100 % | 27 / 55 % | 82 / 96 % | 57 / 79 % | 59 / 79 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 53 / 70 % | 73 / 92 % | 80 / 89 % | 92 / 98 % | 76 / 87 % | 87 / 93 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 42 / 61 % | 71 / 94 % | 49 / 67 % | 91 / 96 % | 75 / 87 % | 89 / 94 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 22 / 78 % | 12 / 32 % | 82 / 96 % | 44 / 69 % | 24 / 44 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 25 / 50 % | 54 / 90 % | 17 / 47 % | 74 / 94 % | 11 / 25 % | 41 / 69 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 73 / 89 % | 21 / 38 % | 71 / 88 % | 45 / 70 % | 33 / 50 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 43 / 81 % | 0 / 0 % | 70 / 86 % | 10 / 30 % | 8 / 15 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 15 / 30 % | 68 / 96 % | 6 / 19 % | 10 / 22 % | 9 / 26 % | 7 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 22 / 45 % | 62 / 85 % | 17 / 33 % | 63 / 76 % | 52 / 75 % | 54 / 74 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 30 % | 10 / 43 % | 4 / 17 % | 54 / 77 % | 21 / 49 % | 12 / 33 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 14 / 33 % | 53 / 96 % | 7 / 30 % | 15 / 62 % | 26 / 51 % | 12 / 36 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 17 / 31 % | 50 / 84 % | 4 / 13 % | 28 / 53 % | 23 / 50 % | 15 / 30 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 48 / 93 % | 1 / 8 % | 18 / 36 % | 14 / 35 % | 7 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 47 / 83 % | 1 / 7 % | 19 / 48 % | 9 / 24 % | 6 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 15 / 40 % | 40 / 87 % | 1 / 8 % | 15 / 39 % | 13 / 34 % | 11 / 24 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 13 / 71 % | 2 / 7 % | 36 / 68 % | 26 / 53 % | 10 / 23 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 14 / 32 % | 22 / 71 % | 2 / 10 % | 36 / 58 % | 10 / 27 % | 14 / 32 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 26 / 92 % | 0 / 5 % | 1 / 12 % | 6 / 15 % | 6 / 15 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 22 / 76 % | 0 / 0 % | 11 / 43 % | 5 / 12 % | 2 / 4 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 23 % | 22 / 89 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 6 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 20 / 75 % | 3 / 13 % | 18 / 49 % | 21 / 52 % | 14 / 31 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 19 / 76 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 4 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 16 / 76 % | 3 / 12 % | 9 / 32 % | 13 / 35 % | 5 / 13 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 10 / 69 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 10 / 60 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 4 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 5 / 52 % | 2 / 7 % | 0 / 0 % | 9 / 25 % | 8 / 28 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 9 / 77 % | 0 / 3 % | 1 / 13 % | 7 / 23 % | 9 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 6 / 13 % | 8 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 1 / 31 % | 0 / 0 % | 8 / 29 % | 7 / 16 % | 6 / 13 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 7 / 91 % | 0 / 3 % | 2 / 17 % | 7 / 17 % | 5 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 62 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 3 / 7 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 3 / 52 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 5 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 21 % | 0 / 0 % | 2 / 4 % |
