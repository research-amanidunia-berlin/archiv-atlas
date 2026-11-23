[English](README.md) · [Deutsch](README.de.md)

# Patch the Planet: global response coordination as agents uncover critical vulnerabilities

Report Q004105 · Source openai.com · Date 2026-10-21 · [Open original](https://openai.com/index/coordinated-disclosure-of-critical-vulnerabilities/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt eine von PHPs Maintainer geleitete Behebung kritischer Schwachstellen und schlägt ein fünfstufiges Verfahren vor, um solche Fälle künftig mit Forschenden, Anbietern, Behörden und Betreibern zu koordinieren. Das Unternehmen wirbt zugleich um Kritik an offenen Fragen wie Vorabinformationen, Offenlegungsfristen und Notfall-Patching; die Angaben zur Entdeckung und Wirkung sind OpenAIs eigene Darstellung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 99 / 100 % | 100 / 100 % | 82 / 90 % | 59 / 75 % | 69 / 81 % | 69 / 85 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 41 % | 71 / 91 % | 95 / 98 % | 36 / 62 % | 11 / 28 % | 38 / 57 % | 7 / 23 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 60 / 96 % | 93 / 96 % | 31 / 56 % | 14 / 35 % | 27 / 46 % | 6 / 15 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 89 / 92 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 81 / 93 % | 83 / 89 % | 43 / 65 % | 20 / 39 % | 54 / 73 % | 19 / 39 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 34 / 54 % | 79 / 99 % | 52 / 83 % | 68 / 83 % | 54 / 70 % | 77 / 87 % | 51 / 78 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 64 / 89 % | 52 / 71 % | 11 / 33 % | 5 / 15 % | 10 / 26 % | 1 / 6 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 63 / 97 % | 53 / 74 % | 34 / 64 % | 18 / 38 % | 30 / 61 % | 18 / 43 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 62 / 80 % | 5 / 9 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 20 / 56 % | 59 / 80 % | 23 / 49 % | 0 / 0 % | 21 / 38 % | 4 / 15 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 58 / 88 % | 53 / 83 % | 14 / 36 % | 0 / 0 % | 10 / 24 % | 0 / 3 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 16 / 56 % | 58 / 75 % | 20 / 46 % | 11 / 27 % | 14 / 30 % | 6 / 18 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 3 / 23 % | 57 / 77 % | 7 / 15 % | 0 / 0 % | 3 / 7 % | 0 / 0 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 55 / 77 % | 42 / 47 % | 32 / 55 % | 9 / 22 % | 25 / 44 % | 15 / 25 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 48 / 85 % | 51 / 75 % | 24 / 46 % | 8 / 22 % | 17 / 29 % | 4 / 10 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 49 / 83 % | 46 / 71 % | 30 / 56 % | 13 / 31 % | 17 / 34 % | 10 / 26 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 5 / 39 % | 48 / 72 % | 18 / 43 % | 8 / 21 % | 15 / 36 % | 2 / 11 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 45 / 66 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 53 % | 41 / 67 % | 17 / 42 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 24 / 78 % | 41 / 55 % | 23 / 48 % | 7 / 18 % | 15 / 31 % | 3 / 11 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 14 / 38 % | 38 / 86 % | 28 / 73 % | 11 / 26 % | 12 / 32 % | 28 / 56 % | 6 / 26 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 37 / 77 % | 29 / 55 % | 11 / 31 % | 0 / 0 % | 14 / 32 % | 1 / 4 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 35 / 69 % | 37 / 60 % | 17 / 43 % | 6 / 19 % | 19 / 40 % | 3 / 11 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 35 / 78 % | 0 / 0 % | 20 / 50 % | 13 / 35 % | 26 / 52 % | 3 / 12 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 28 / 72 % | 22 / 47 % | 17 / 36 % | 0 / 0 % | 15 / 28 % | 3 / 12 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 27 / 78 % | 0 / 0 % | 13 / 34 % | 9 / 25 % | 16 / 35 % | 2 / 6 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 9 / 79 % | 21 / 65 % | 20 / 47 % | 15 / 33 % | 0 / 0 % | 6 / 22 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 36 % | 6 / 18 % | 5 / 12 % | 1 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 7 / 62 % | 0 / 0 % | 11 / 30 % | 7 / 23 % | 10 / 25 % | 2 / 9 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 3 / 7 % | 7 / 12 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 4 / 9 % | 5 / 9 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
