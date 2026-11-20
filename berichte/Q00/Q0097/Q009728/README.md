[English](README.md) · [Deutsch](README.de.md)

# https://github.com/UKGovernmentBEIS/aisi-sandboxing/blob/main/Technical%20Guidance.pdf

Report Q009728 · Source github.com · Date – · [Open original](https://github.com/UKGovernmentBEIS/aisi-sandboxing/blob/main/Technical%20Guidance.pdf)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt ein AISI-internes Schema vor, das Sandboxen für KI-Evaluationen nach Werkzeugzugriff, Host-Isolation und Netzwerkzugriff einteilt und Beispiele für Docker Compose, Kubernetes und Proxmox gibt. Er warnt, dass dies keine offizielle Regierungsleitlinie ist und keine vollständige Sicherheit garantiert; manche Konfigurationsbeispiele sind zudem uneinheitlich.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 57 / 73 % | 93 / 97 % | 85 / 95 % | 99 / 100 % | 86 / 92 % | 69 / 81 % | 72 / 85 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 53 % | 84 / 97 % | 37 / 70 % | 97 / 99 % | 61 / 81 % | 55 / 73 % | 44 / 66 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 51 / 69 % | 59 / 82 % | 42 / 69 % | 77 / 89 % | 66 / 83 % | 60 / 77 % | 64 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 53 % | 57 / 85 % | 10 / 31 % | 41 / 66 % | 27 / 58 % | 28 / 53 % | 13 / 28 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 52 / 91 % | 1 / 7 % | 12 / 41 % | 15 / 35 % | 7 / 15 % | 6 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 14 / 37 % | 45 / 91 % | 3 / 17 % | 52 / 79 % | 32 / 60 % | 15 / 38 % | 11 / 31 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 32 / 55 % | 47 / 84 % | 9 / 35 % | 26 / 65 % | 12 / 22 % | 33 / 60 % | 23 / 47 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 36 / 72 % | 0 / 0 % | 35 / 44 % | 11 / 25 % | 9 / 19 % | 3 / 7 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 34 / 70 % | 0 / 0 % | 3 / 18 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 34 / 81 % | 1 / 5 % | 0 / 0 % | 11 / 27 % | 9 / 17 % | 3 / 7 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 28 / 50 % | 7 / 22 % | 5 / 11 % | 2 / 6 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 26 / 48 % | 9 / 20 % | 5 / 9 % | 1 / 2 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 25 / 47 % | 6 / 16 % | 0 / 0 % | 1 / 4 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 1 / 8 % | 16 / 43 % | 18 / 43 % | 14 / 30 % | 7 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 42 % | 5 / 10 % | 4 / 11 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 12 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 35 % | 15 / 27 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 14 / 59 % | 0 / 0 % | 0 / 0 % | 11 / 33 % | 11 / 25 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 31 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 30 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 30 % | 3 / 6 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 26 % | 10 / 25 % | 5 / 11 % | 2 / 7 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 4 / 7 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 26 % | 5 / 10 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 19 % | 2 / 4 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 5 % | 0 / 1 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 5 / 10 % | 1 / 4 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 2 / 3 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 2 / 7 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 1 / 5 % |
