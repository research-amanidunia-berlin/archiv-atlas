[English](README.md) · [Deutsch](README.de.md)

# Claude Mythos Preview's cybersecurity capabilities

Report Q001132 · Source anthropic.com · Date 2026-04-07 · [Open original](https://www.anthropic.com/research/mythos-preview)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, Claude Mythos Preview könne in realen Softwareprojekten eigenständig bislang unbekannte Schwachstellen finden und teils zu Angriffen ausbauen; die Tests hätten unter anderem Betriebssysteme, Browser und Bibliotheken betroffen. Da mehr als 99 Prozent der Funde laut Anthropic noch ungepatcht sind, bleiben viele Details verborgen, und die veröffentlichten Beispiele sind nur eine Untergrenze. Das Unternehmen fordert schnellere Patches und den verstärkten Einsatz von KI zur Verteidigung, während Mythos Preview zunächst begrenzt verfügbar bleiben soll.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 62 % | 95 / 99 % | 100 / 100 % | 66 / 83 % | 69 / 82 % | 77 / 87 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 47 % | 94 / 97 % | 99 / 100 % | 63 / 81 % | 30 / 53 % | 55 / 72 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 56 / 74 % | 95 / 98 % | 96 / 98 % | 51 / 66 % | 57 / 77 % | 68 / 81 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 29 / 49 % | 90 / 96 % | 96 / 97 % | 44 / 69 % | 38 / 56 % | 47 / 61 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 36 / 55 % | 60 / 87 % | 93 / 97 % | 56 / 74 % | 18 / 33 % | 39 / 52 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 24 / 48 % | 79 / 96 % | 92 / 95 % | 57 / 76 % | 8 / 21 % | 23 / 41 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 29 / 60 % | 91 / 95 % | 62 / 80 % | 27 / 47 % | 17 / 32 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 37 / 55 % | 89 / 96 % | 90 / 94 % | 42 / 67 % | 12 / 27 % | 32 / 47 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 34 / 59 % | 89 / 91 % | 38 / 62 % | 23 / 38 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 27 / 60 % | 86 / 90 % | 6 / 14 % | 0 / 0 % | 5 / 9 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 62 / 84 % | 72 / 81 % | 8 / 23 % | 2 / 10 % | 9 / 19 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 21 / 42 % | 0 / 0 % | 71 / 83 % | 21 / 43 % | 16 / 29 % | 15 / 22 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 21 / 86 % | 71 / 77 % | 8 / 24 % | 3 / 10 % | 8 / 16 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 68 / 74 % | 15 / 36 % | 0 / 0 % | 10 / 19 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 63 / 95 % | 45 / 64 % | 13 / 36 % | 5 / 16 % | 15 / 29 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 61 / 94 % | 35 / 57 % | 46 / 72 % | 13 / 28 % | 29 / 50 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 54 / 79 % | 21 / 54 % | 14 / 36 % | 4 / 13 % | 11 / 23 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 46 % | 16 / 53 % | 52 / 70 % | 42 / 65 % | 11 / 29 % | 28 / 44 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 51 / 74 % | 11 / 32 % | 4 / 16 % | 7 / 19 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 15 / 34 % | 30 / 84 % | 46 / 63 % | 33 / 57 % | 12 / 28 % | 25 / 41 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 44 / 60 % | 17 / 40 % | 0 / 0 % | 7 / 17 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 14 / 47 % | 41 / 56 % | 9 / 22 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 21 / 45 % | 28 / 95 % | 19 / 71 % | 40 / 66 % | 17 / 40 % | 14 / 41 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 35 / 84 % | 7 / 11 % | 6 / 15 % | 1 / 5 % | 8 / 12 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 28 / 41 % | 32 / 85 % | 33 / 52 % | 23 / 48 % | 8 / 22 % | 19 / 33 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 27 / 43 % | 0 / 0 % | 0 / 0 % | 19 / 45 % | 7 / 21 % | 32 / 42 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 8 / 35 % | 0 / 0 % | 14 / 38 % | 5 / 12 % | 16 / 26 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 16 / 77 % | 0 / 0 % | 10 / 25 % | 4 / 14 % | 6 / 13 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 34 % | 7 / 22 % | 8 / 18 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 10 / 34 % | 9 / 28 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 7 / 18 % | 9 / 20 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 8 / 19 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 3 / 7 % | 7 / 17 % | 3 / 11 % | 6 / 15 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 11 % | 6 / 11 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 6 % | 5 / 9 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
