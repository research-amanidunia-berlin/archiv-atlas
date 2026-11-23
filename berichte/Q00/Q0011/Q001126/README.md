[English](README.md) · [Deutsch](README.de.md)

# Update on Security at METR

Report Q001126 · Source metr.org · Date 2026-08-31 · [Open original](https://metr.org/blog/2026-08-31-security-update/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht beschreibt zwei Sicherheitsvorfälle bei METR: den Diebstahl eines API-Schlüssels für öffentliche Modelle im März und eine im Mai entdeckte Schwachstelle, durch die sensible Evaluationsergebnisse theoretisch erreichbar gewesen wären. METR zufolge gibt es keine Hinweise, dass im zweiten Vorfall nicht öffentliche Daten abgerufen wurden; das Unternehmen berichtet von verstärkten Sicherheitskontrollen und nennt den 30. Juli 2026 als Stand der beschriebenen Maßnahmen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 99 / 100 % | 100 / 100 % | 63 / 80 % | 24 / 48 % | 60 / 75 % | 45 / 71 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 41 / 57 % | 67 / 86 % | 99 / 100 % | 68 / 84 % | 35 / 58 % | 58 / 75 % | 61 / 79 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 72 / 97 % | 84 / 90 % | 41 / 63 % | 11 / 32 % | 27 / 48 % | 12 / 27 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 66 / 93 % | 78 / 85 % | 31 / 58 % | 21 / 44 % | 34 / 54 % | 7 / 18 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 75 / 91 % | 57 / 77 % | 45 / 65 % | 10 / 26 % | 34 / 52 % | 21 / 41 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 55 / 85 % | 73 / 91 % | 11 / 29 % | 4 / 11 % | 10 / 21 % | 0 / 2 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 56 % | 59 / 88 % | 69 / 81 % | 29 / 59 % | 35 / 56 % | 62 / 79 % | 8 / 23 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 36 / 66 % | 68 / 83 % | 26 / 50 % | 11 / 28 % | 40 / 59 % | 6 / 19 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 63 / 85 % | 48 / 66 % | 39 / 63 % | 14 / 33 % | 20 / 38 % | 5 / 14 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 52 / 92 % | 0 / 0 % | 25 / 47 % | 10 / 24 % | 52 / 69 % | 4 / 10 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 29 / 62 % | 0 / 0 % | 12 / 31 % | 4 / 12 % | 8 / 16 % | 1 / 5 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 3 / 46 % | 0 / 0 % | 10 / 30 % | 6 / 15 % | 16 / 29 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 37 % | 7 / 15 % | 16 / 27 % | 3 / 11 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 12 % | 16 / 40 % | 4 / 12 % | 7 / 16 % | 3 / 13 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 14 / 68 % | 0 / 0 % | 8 / 22 % | 4 / 11 % | 12 / 21 % | 1 / 6 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 14 / 52 % | 11 / 35 % | 5 / 18 % | 0 / 0 % | 2 / 11 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 7 / 50 % | 0 / 0 % | 12 / 28 % | 8 / 22 % | 12 / 24 % | 1 / 4 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 6 % | 11 / 23 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 29 % | 0 / 0 % | 10 / 20 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 4 / 18 % | 6 / 14 % | 3 / 12 % | 10 / 19 % | 0 / 3 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 2 / 9 % | 8 / 15 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | 9 / 17 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 6 % | 8 / 16 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 1 / 3 % | 6 / 11 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
