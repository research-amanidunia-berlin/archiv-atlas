[English](README.md) · [Deutsch](README.de.md)

# ControlConf 2026: What is AI control and how has the field grown?

Report Q001593 · Source far.ai · Date 2026-07-16 · [Open original](https://www.far.ai/blog/controlconf-2026)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt KI-Kontrolle als Prüfung von Schutzmaßnahmen dar, die auch dann funktionieren sollen, wenn ein fehlangepasstes Modell sie zu umgehen versucht. Er beschreibt wachsende praktische Aktivitäten, nennt Prognosen zur möglichen Entwicklung leistungsfähiger KI und hebt drei ungelöste Fragen hervor: Übertragbarkeit heutiger Verfahren, externe Kontrolle und Prüfbarkeit der Maßnahmen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 45 / 66 % | 89 / 97 % | 96 / 100 % | 78 / 89 % | 78 / 90 % | 89 / 94 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 30 / 61 % | 62 / 87 % | 94 / 99 % | 70 / 85 % | 26 / 56 % | 62 / 79 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 18 / 43 % | 81 / 98 % | 94 / 97 % | 63 / 82 % | 18 / 45 % | 52 / 75 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 58 % | 88 / 99 % | 90 / 99 % | 69 / 86 % | 38 / 71 % | 64 / 85 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 30 / 58 % | 83 / 97 % | 89 / 96 % | 62 / 80 % | 54 / 76 % | 52 / 69 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 32 / 56 % | 40 / 84 % | 49 / 81 % | 73 / 86 % | 60 / 80 % | 87 / 93 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 39 / 63 % | 85 / 98 % | 86 / 95 % | 64 / 81 % | 61 / 75 % | 74 / 82 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 25 / 55 % | 36 / 83 % | 85 / 97 % | 37 / 63 % | 33 / 59 % | 74 / 87 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 33 / 59 % | 70 / 97 % | 82 / 99 % | 62 / 81 % | 46 / 71 % | 65 / 84 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 42 % | 65 / 92 % | 67 / 87 % | 27 / 51 % | 12 / 26 % | 36 / 58 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 15 / 41 % | 67 / 90 % | 9 / 20 % | 20 / 44 % | 6 / 17 % | 15 / 33 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 24 / 55 % | 63 / 92 % | 33 / 59 % | 29 / 58 % | 29 / 48 % | 57 / 72 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 10 / 40 % | 61 / 98 % | 24 / 75 % | 27 / 58 % | 11 / 31 % | 33 / 60 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 21 / 60 % | 58 / 78 % | 11 / 32 % | 2 / 6 % | 8 / 18 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 53 % | 54 / 94 % | 46 / 73 % | 37 / 66 % | 11 / 36 % | 57 / 77 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 22 / 47 % | 53 / 88 % | 57 / 78 % | 20 / 45 % | 8 / 23 % | 10 / 26 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 18 / 42 % | 54 / 93 % | 19 / 55 % | 37 / 64 % | 11 / 26 % | 16 / 36 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 50 / 87 % | 52 / 78 % | 12 / 34 % | 4 / 13 % | 8 / 24 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 13 / 37 % | 35 / 77 % | 44 / 86 % | 30 / 58 % | 7 / 17 % | 22 / 53 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 19 / 44 % | 30 / 77 % | 23 / 43 % | 18 / 43 % | 11 / 23 % | 43 / 60 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 44 % | 38 / 84 % | 18 / 56 % | 28 / 56 % | 17 / 48 % | 32 / 61 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 26 / 57 % | 0 / 0 % | 14 / 37 % | 1 / 3 % | 13 / 30 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 8 / 25 % | 0 / 0 % | 25 / 62 % | 12 / 37 % | 6 / 18 % | 10 / 26 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 17 / 52 % | 25 / 51 % | 11 / 31 % | 3 / 11 % | 9 / 20 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 6 / 26 % | 21 / 76 % | 0 / 0 % | 9 / 25 % | 2 / 9 % | 7 / 20 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 37 % | 0 / 0 % | 8 / 16 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 11 / 39 % | 12 / 49 % | 4 / 28 % | 8 / 17 % | 1 / 4 % | 12 / 21 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 2 / 7 % | 11 / 29 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 5 / 45 % | 0 / 0 % | 9 / 26 % | 1 / 4 % | 10 / 20 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 10 / 16 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 3 / 50 % | 1 / 14 % | 10 / 26 % | 1 / 6 % | 5 / 14 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 25 % | 1 / 4 % | 9 / 22 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 78 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 10 / 18 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 9 / 29 % | 0 / 0 % | 3 / 24 % | 8 / 22 % | 3 / 11 % | 8 / 18 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 9 / 23 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 2 % | 8 / 14 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 3 / 8 % | 6 / 16 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 8 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 1 / 28 % | 0 / 0 % | 6 / 15 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 6 / 13 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 3 / 6 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % | – | – |
