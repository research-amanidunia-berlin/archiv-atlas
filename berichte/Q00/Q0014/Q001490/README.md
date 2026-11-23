[English](README.md) · [Deutsch](README.de.md)

# Introducing the AI Security Leaderboard: Frontier AI Is Only as Safe as Its Weakest Model

Report Q001490 · Source far.ai · Date 2026-07-31 · [Open original](https://www.far.ai/blog/ai-security-leaderboard)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

FAR.AI berichtet, dass Tests mit mehreren hunderttausend Prompts große Unterschiede zwischen vier KI-Modellen zeigten: Für Grok 4.5 habe ein Jailbreak mit geringem Aufwand funktioniert, während bei Claude Fable 5 und GPT-5.6 Sol im Test keiner gefunden worden sei. Das neue Leaderboard und ein Mindeststandard sollen Schutzmaßnahmen vergleichbar machen; die Ergebnisse sind laut Bericht keine Sicherheitszertifizierung, da nur eine Auswahl von Angriffen geprüft wurde und die Kostenangaben auf FAR.AI-Werkzeugen beruhen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 73 / 84 % | 98 / 100 % | 100 / 100 % | 69 / 79 % | 89 / 94 % | 89 / 93 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 42 / 59 % | 85 / 99 % | 100 / 100 % | 77 / 87 % | 30 / 54 % | 76 / 87 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 34 / 58 % | 81 / 99 % | 100 / 100 % | 71 / 85 % | 22 / 43 % | 49 / 70 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 48 / 66 % | 92 / 99 % | 94 / 98 % | 60 / 79 % | 76 / 87 % | 74 / 85 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 21 / 47 % | 89 / 97 % | 72 / 90 % | 78 / 89 % | 20 / 44 % | 66 / 80 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 56 / 93 % | 85 / 93 % | 69 / 83 % | 12 / 27 % | 13 / 32 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 24 / 47 % | 67 / 95 % | 85 / 92 % | 31 / 57 % | 20 / 37 % | 33 / 56 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 32 / 52 % | 44 / 82 % | 84 / 93 % | 78 / 88 % | 23 / 47 % | 77 / 88 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 28 / 51 % | 79 / 98 % | 82 / 93 % | 45 / 70 % | 8 / 26 % | 19 / 40 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 25 / 55 % | 22 / 71 % | 78 / 93 % | 36 / 61 % | 16 / 36 % | 18 / 39 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 39 / 58 % | 75 / 98 % | 71 / 80 % | 42 / 66 % | 17 / 35 % | 36 / 64 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 37 / 72 % | 73 / 87 % | 8 / 26 % | 2 / 9 % | 6 / 16 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 27 % | 14 / 91 % | 58 / 75 % | 10 / 30 % | 3 / 12 % | 8 / 23 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 51 / 83 % | 56 / 73 % | 14 / 39 % | 16 / 32 % | 23 / 43 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 19 / 41 % | 42 / 79 % | 28 / 50 % | 43 / 65 % | 20 / 33 % | 55 / 67 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 52 / 87 % | 32 / 65 % | 11 / 33 % | 5 / 16 % | 9 / 27 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 12 / 39 % | 43 / 95 % | 50 / 79 % | 16 / 38 % | 6 / 18 % | 10 / 28 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 15 / 45 % | 0 / 0 % | 36 / 62 % | 10 / 21 % | 44 / 66 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 44 / 85 % | 1 / 19 % | 12 / 34 % | 9 / 25 % | 10 / 34 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 19 / 72 % | 41 / 76 % | 7 / 19 % | 2 / 7 % | 6 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 34 / 92 % | 9 / 27 % | 8 / 26 % | 3 / 13 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 53 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 11 / 37 % | 26 / 47 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 4 / 38 % | 24 / 32 % | 10 / 30 % | 3 / 11 % | 22 / 48 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 21 / 92 % | 11 / 55 % | 23 / 49 % | 6 / 20 % | 8 / 31 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 15 / 48 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 12 / 67 % | 0 / 0 % | 9 / 29 % | 1 / 7 % | 7 / 21 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 11 / 80 % | 10 / 33 % | 8 / 20 % | 0 / 0 % | 8 / 18 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 28 % | 3 / 46 % | 0 / 0 % | 9 / 25 % | 3 / 11 % | 11 / 26 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 26 % | 1 / 7 % | 8 / 26 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 3 / 33 % | 0 / 0 % | 7 / 17 % | 0 / 5 % | 6 / 13 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 7 / 43 % | 2 / 17 % | 7 / 20 % | 1 / 8 % | 6 / 17 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 3 % | 7 / 22 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 6 / 13 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 71 % | 1 / 20 % | 6 / 19 % | 2 / 9 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 5 / 11 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 4 / 48 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
