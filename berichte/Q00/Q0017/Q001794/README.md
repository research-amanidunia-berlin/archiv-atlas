[English](README.md) · [Deutsch](README.de.md)

# Red-Teaming Anthropic's Internal Agent Monitoring Systems

Report Q001794 · Source metr.org · Date 2026-03-26 · [Open original](https://metr.org/blog/2026-03-25-red-teaming-anthropic-agent-monitoring/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR beschreibt einen dreiwöchigen Test interner Anthropic-Monitoring-Systeme, bei dem mehrere Schwachstellen und wirksame Wege zur Täuschung von Monitoren gefunden wurden; einige Probleme seien behoben worden. Die damals getesteten Modelle waren bei Angriffsideen deutlich schwächer als Menschen, doch laut Rein beruhte ein Teil des Vertrauens in die Überwachung auf Geheimhaltung, und einzelne Angriffe könnten unentdeckt bleiben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 65 / 80 % | 83 / 95 % | 72 / 88 % | 100 / 100 % | 77 / 87 % | 21 / 45 % | 56 / 73 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 44 / 62 % | 57 / 97 % | 26 / 62 % | 99 / 100 % | 64 / 82 % | 34 / 62 % | 64 / 84 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 49 / 68 % | 92 / 98 % | 78 / 92 % | 90 / 95 % | 81 / 90 % | 71 / 85 % | 85 / 92 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 24 / 46 % | 37 / 65 % | 20 / 45 % | 90 / 95 % | 49 / 69 % | 16 / 32 % | 54 / 68 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 29 / 53 % | 67 / 92 % | 22 / 54 % | 88 / 95 % | 5 / 13 % | 22 / 46 % | 57 / 75 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 47 / 65 % | 64 / 98 % | 38 / 63 % | 87 / 94 % | 71 / 85 % | 39 / 61 % | 73 / 83 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 18 / 38 % | 70 / 96 % | 16 / 37 % | 84 / 89 % | 63 / 81 % | 10 / 28 % | 36 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 34 / 57 % | 0 / 0 % | 30 / 62 % | 80 / 85 % | 56 / 75 % | 29 / 53 % | 37 / 56 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 49 / 70 % | 50 / 94 % | 55 / 77 % | 39 / 68 % | 71 / 86 % | 55 / 74 % | 77 / 86 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 32 / 51 % | 0 / 0 % | 16 / 41 % | 52 / 67 % | 66 / 82 % | 19 / 39 % | 76 / 86 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 65 / 93 % | 5 / 14 % | 43 / 78 % | 27 / 55 % | 2 / 7 % | 20 / 37 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 60 / 72 % | 8 / 20 % | 2 / 7 % | 5 / 9 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 2 / 7 % | 51 / 68 % | 30 / 55 % | 5 / 14 % | 11 / 22 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 42 % | 50 / 80 % | 1 / 5 % | 33 / 58 % | 15 / 39 % | 4 / 13 % | 20 / 39 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 46 / 85 % | 2 / 10 % | 32 / 69 % | 22 / 50 % | 7 / 20 % | 13 / 26 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 18 / 41 % | 43 / 84 % | 12 / 28 % | 22 / 47 % | 38 / 61 % | 17 / 37 % | 37 / 56 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 41 / 62 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 42 % | 0 / 0 % | 4 / 19 % | 21 / 47 % | 35 / 58 % | 8 / 21 % | 21 / 36 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 20 / 35 % | 0 / 0 % | 1 / 4 % | 27 / 47 % | 26 / 51 % | 4 / 13 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 2 / 9 % | 0 / 0 % | 22 / 53 % | 4 / 11 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 18 / 44 % | 6 / 16 % | 2 / 6 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 35 % | 5 / 9 % | 1 / 2 % | 6 / 11 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 7 / 19 % | 1 / 7 % | 16 / 30 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 6 / 18 % | 13 / 32 % | 3 / 15 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 13 / 50 % | 0 / 3 % | 2 / 17 % | 8 / 22 % | 1 / 5 % | 5 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 35 % | 0 / 0 % | 0 / 2 % | 9 / 25 % | 8 / 18 % | 3 / 7 % | 11 / 21 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 35 % | 8 / 25 % | 1 / 4 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 1 / 3 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 7 / 17 % | 3 / 7 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 1 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 1 / 3 % | 4 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 4 / 10 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 2 % | 5 / 13 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 3 / 5 % |
