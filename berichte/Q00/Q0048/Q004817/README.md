[English](README.md) · [Deutsch](README.de.md)

# Fast Remediation Is the New Trust Model: JFrog and OpenAI Collaboration on Zero-Day Security Findings

Report Q004817 · Source jfrog.com · Date 2026-07-27 · [Open original](https://jfrog.com/blog/jfrog-and-openai-collaboration-on-zero-day-security-findings/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

JFrog zufolge fanden OpenAI-Modelle bislang unbekannte Schwachstellen in selbst gehostetem Artifactory; nach verantwortungsvoller Meldung habe JFrog Korrekturen für Cloud- und selbst gehostete Kunden bereitgestellt. Der Beitrag betont schnelle Behebung als entscheidenden Schutz und warnt, dass Agenten zugängliche Ressourcen wie liegengebliebene Zugangsdaten verwenden könnten; technische Einzelheiten und unabhängige Bestätigung fehlen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 47 / 69 % | 97 / 99 % | 99 / 99 % | 80 / 89 % | 66 / 79 % | 74 / 85 % | 75 / 87 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 50 % | 85 / 97 % | 97 / 99 % | 56 / 77 % | 23 / 50 % | 47 / 73 % | 22 / 68 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 35 / 55 % | 77 / 90 % | 97 / 99 % | 70 / 84 % | 55 / 74 % | 53 / 72 % | 61 / 86 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 58 / 80 % | 96 / 98 % | 9 / 24 % | 1 / 4 % | 6 / 9 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 27 / 48 % | 84 / 99 % | 95 / 98 % | 52 / 75 % | 25 / 48 % | 43 / 66 % | 19 / 63 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 21 / 48 % | 42 / 74 % | 87 / 95 % | 57 / 77 % | 15 / 38 % | 35 / 59 % | 40 / 73 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 34 % | 38 / 78 % | 75 / 86 % | 20 / 46 % | 7 / 22 % | 26 / 44 % | 1 / 7 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 30 / 52 % | 29 / 77 % | 75 / 88 % | 53 / 77 % | 53 / 73 % | 42 / 71 % | 45 / 83 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 25 / 48 % | 72 / 92 % | 70 / 82 % | 46 / 69 % | 36 / 53 % | 49 / 66 % | 25 / 56 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 32 / 52 % | 50 / 85 % | 51 / 73 % | 58 / 77 % | 19 / 38 % | 24 / 42 % | 9 / 30 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 53 / 78 % | 18 / 44 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 43 / 90 % | 48 / 77 % | 11 / 28 % | 3 / 8 % | 10 / 18 % | 1 / 8 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 48 / 69 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 43 / 58 % | 20 / 44 % | 5 / 16 % | 10 / 24 % | 7 / 28 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 38 / 64 % | 40 / 68 % | 7 / 22 % | 1 / 3 % | 4 / 12 % | 0 / 3 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 46 % | 7 / 65 % | 23 / 41 % | 25 / 57 % | 23 / 46 % | 39 / 67 % | 8 / 34 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 3 / 30 % | 35 / 54 % | 9 / 27 % | 2 / 7 % | 10 / 20 % | 1 / 8 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 32 / 89 % | 34 / 57 % | 7 / 18 % | 1 / 5 % | 5 / 10 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 57 % | 4 / 10 % | 20 / 34 % | 1 / 5 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 38 % | 25 / 72 % | 11 / 39 % | 30 / 56 % | 12 / 35 % | 26 / 51 % | 5 / 22 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 20 / 44 % | 27 / 75 % | 8 / 50 % | 25 / 52 % | 10 / 24 % | 11 / 32 % | 10 / 51 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 8 / 42 % | 26 / 55 % | 15 / 43 % | 6 / 18 % | 11 / 27 % | 1 / 8 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 14 / 45 % | 13 / 77 % | 14 / 55 % | 6 / 15 % | 8 / 28 % | 20 / 50 % | 7 / 45 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 13 / 30 % | 0 / 0 % | 9 / 27 % | 16 / 41 % | 0 / 0 % | 11 / 26 % | 2 / 14 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 15 / 40 % | 6 / 20 % | 1 / 6 % | 4 / 10 % | 0 / 7 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 34 % | 1 / 5 % | 14 / 24 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 7 / 52 % | 8 / 44 % | 13 / 43 % | 0 / 0 % | 14 / 28 % | 4 / 26 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 12 / 32 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 2 / 9 % | 12 / 22 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 4 / 11 % | 6 / 15 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 3 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 1 % | 3 / 6 % | 0 / 0 % | – |
