[English](README.md) · [Deutsch](README.de.md)

# Reflections on safety: General-purpose AI developers can learn from the Challenger disaster

Report Q005633 · Source oecd.ai · Date 2024-02-05 · [Open original](https://oecd.ai/en/wonk/safety-ai-the-challenger-disaster)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor leitet aus Challenger ab, dass Zeitdruck, fehlendes Verständnis von Warnzeichen und eine schwache Sicherheitskultur auch bei der Entwicklung von Allzweck-KI schwere Risiken schaffen können. Er fordert mehr Risikoprüfung, Investitionen in nachweislich sichere Architekturen und eine Sicherheitskultur, die Sicherheit konsequent über Termine stellt; der Beitrag ist eine argumentierende Reflexion, keine systematische Risikoanalyse.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 50 % | 90 / 99 % | 96 / 100 % | 29 / 64 % | 14 / 40 % | 21 / 57 % | 18 / 68 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 26 / 47 % | 75 / 94 % | 69 / 94 % | 20 / 59 % | 10 / 35 % | 12 / 46 % | 7 / 50 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 36 / 63 % | 67 / 96 % | 71 / 94 % | 37 / 67 % | 12 / 35 % | 25 / 58 % | 10 / 48 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 66 / 93 % | 16 / 53 % | 9 / 28 % | 3 / 18 % | 6 / 24 % | 1 / 9 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 23 / 42 % | 25 / 90 % | 57 / 80 % | 18 / 53 % | 3 / 14 % | 8 / 25 % | 2 / 16 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 43 % | 21 / 81 % | 43 / 80 % | 13 / 42 % | 3 / 19 % | 8 / 30 % | 3 / 31 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 36 / 82 % | 40 / 67 % | 6 / 14 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 13 / 43 % | 11 / 92 % | 38 / 67 % | 7 / 25 % | 0 / 0 % | 7 / 23 % | 0 / 7 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 7 / 31 % | 36 / 88 % | 0 / 12 % | 7 / 22 % | 4 / 19 % | 7 / 19 % | 1 / 11 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 7 / 35 % | 35 / 95 % | 31 / 85 % | 11 / 44 % | 6 / 23 % | 8 / 30 % | 4 / 30 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 30 / 84 % | 0 / 0 % | 5 / 13 % | 2 / 9 % | 4 / 11 % | 0 / 4 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 11 / 34 % | 29 / 95 % | 24 / 72 % | 8 / 34 % | 2 / 15 % | 8 / 21 % | 2 / 24 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 28 % | 27 / 89 % | 1 / 15 % | 7 / 26 % | 2 / 12 % | 7 / 19 % | 0 / 5 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 33 % | 25 / 88 % | 2 / 35 % | 7 / 27 % | 2 / 14 % | 6 / 20 % | 2 / 16 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 25 / 85 % | 1 / 14 % | 8 / 24 % | 1 / 8 % | 7 / 18 % | 0 / 4 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 6 / 32 % | 20 / 76 % | 2 / 31 % | 8 / 29 % | 3 / 19 % | 7 / 26 % | 1 / 15 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 9 / 27 % | 20 / 93 % | 3 / 48 % | 11 / 40 % | 3 / 18 % | 8 / 26 % | 2 / 17 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 18 / 69 % | 1 / 6 % | 6 / 21 % | 2 / 12 % | 6 / 20 % | 0 / 6 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 17 / 38 % | 15 / 93 % | 14 / 48 % | 9 / 32 % | 3 / 13 % | 9 / 22 % | 3 / 22 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 17 / 94 % | 0 / 0 % | 5 / 14 % | 2 / 8 % | 5 / 12 % | 1 / 5 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 17 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 15 / 86 % | 2 / 17 % | 7 / 27 % | 2 / 12 % | 5 / 14 % | 0 / 6 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 15 / 88 % | 0 / 0 % | 7 / 23 % | 0 / 0 % | 9 / 26 % | 1 / 9 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 15 / 83 % | 0 / 0 % | 10 / 32 % | 1 / 9 % | 8 / 24 % | 0 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 11 / 93 % | 1 / 26 % | 5 / 11 % | 1 / 5 % | 7 / 15 % | 0 / 3 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 6 / 62 % | 5 / 25 % | 11 / 34 % | 4 / 14 % | 11 / 27 % | 1 / 8 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 26 % | 0 / 0 % | 0 / 2 % | 5 / 20 % | 1 / 9 % | 7 / 16 % | 0 / 5 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 9 / 43 % | 9 / 94 % | 1 / 15 % | 8 / 33 % | 1 / 11 % | 5 / 13 % | 1 / 12 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 7 / 55 % | 0 / 0 % | 5 / 12 % | 1 / 6 % | 5 / 12 % | 0 / 3 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 1 / 9 % | 5 / 12 % | 0 / 4 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 27 % | 6 / 88 % | 0 / 0 % | 5 / 20 % | 1 / 9 % | 5 / 15 % | 0 / 2 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 53 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 6 / 15 % | 0 / 2 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 5 / 93 % | 0 / 15 % | 6 / 19 % | 1 / 8 % | 0 / 0 % | 0 / 3 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 5 / 9 % | 0 / 3 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 4 / 94 % | 0 / 10 % | 5 / 15 % | 1 / 10 % | 3 / 12 % | 0 / 6 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 10 % | 0 / 0 % | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 11 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 1 / 5 % | 5 / 15 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
