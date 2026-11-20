[English](README.md) · [Deutsch](README.de.md)

# Running Codex safely at OpenAI

Report Q007254 · Source openai.com · Date 2026-05-08 · [Open original](https://openai.com/index/running-codex-safely/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt ein Sicherheitsmodell für Codex aus Sandbox-Grenzen, Freigaberegeln, eingeschränktem Netzwerkzugang, verwalteter Anmeldung und agentenspezifischen Protokollen. Laut Bericht unterstützen diese Protokolle sowohl Sicherheitsprüfungen als auch die betriebliche Beobachtung; unabhängige Wirksamkeitsmessungen oder quantitative Ergebnisse werden nicht vorgelegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 52 / 65 % | 94 / 99 % | – | 100 / 100 % | 83 / 90 % | 78 / 86 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 83 / 91 % | 97 / 98 % | – | 100 / 100 % | 94 / 96 % | 92 / 94 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 21 / 36 % | 85 / 94 % | – | 99 / 100 % | 18 / 36 % | 14 / 26 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 86 / 97 % | – | 84 / 96 % | 47 / 71 % | 28 / 44 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 71 / 97 % | – | 85 / 97 % | 29 / 54 % | 22 / 37 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 43 / 61 % | 77 / 97 % | – | 77 / 90 % | 72 / 85 % | 83 / 90 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 43 / 93 % | – | 74 / 82 % | 20 / 46 % | 23 / 41 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 53 % | 72 / 98 % | – | 42 / 59 % | 36 / 63 % | 52 / 69 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 23 / 65 % | – | 70 / 90 % | 35 / 64 % | 19 / 33 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 20 / 28 % | 63 / 90 % | – | 25 / 46 % | 38 / 60 % | 15 / 25 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 56 / 97 % | – | 43 / 67 % | 20 / 49 % | 20 / 40 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 33 / 93 % | – | 44 / 71 % | 17 / 42 % | 11 / 24 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 24 % | 33 / 66 % | – | 0 / 0 % | 11 / 28 % | 10 / 19 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 32 / 52 % | 5 / 11 % | 5 / 9 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 25 / 49 % | 5 / 13 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 22 / 51 % | – | 0 / 0 % | 9 / 18 % | 8 / 13 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 10 / 23 % | 12 / 40 % | – | 4 / 26 % | 22 / 43 % | 6 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 20 / 72 % | – | 0 / 0 % | 7 / 15 % | 5 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 18 / 84 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 15 / 34 % | 7 / 14 % | 6 / 11 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 14 / 26 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 14 / 46 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 12 / 66 % | – | 0 / 0 % | 8 / 18 % | 4 / 7 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 12 / 43 % | – | 0 / 0 % | 9 / 20 % | 10 / 24 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 12 / 62 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 24 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 13 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 25 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 27 % | 6 / 13 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 25 % | 9 / 17 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 3 / 62 % | – | 0 / 0 % | 6 / 14 % | 4 / 7 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 4 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 6 / 70 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
