[English](README.md) · [Deutsch](README.de.md)

# Qwen 3.8 27B Uncensored Just Landed on the Mac — No CUDA, No Cloud

Report Q011215 · Source medium.com · Date 2026-08-20 · [Open original](https://medium.com/coding-nexus/qwen-3-8-27b-uncensored-just-landed-on-the-mac-no-cuda-no-cloud-ab5a063dfb4b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag stellt eine laut Autor lokal auf Apple-Silicon-Macs ausführbare, multimodale 27B-MLX-Version von Qwen 3.8 vor, deren Ablehnungsverhalten durch Abliteration verringert worden sei. Er nennt Quantisierungen von 2 bis 8 Bit und lokale Bild-, Text- und API-Nutzung, warnt aber vor Qualitätsverlusten, Modellfehlern und Sicherheitsrisiken; die Leistungsangaben seien nicht ohne Weiteres auf Macs übertragbar.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 96 / 100 % | 100 / 100 % | 28 / 56 % | 3 / 15 % | 17 / 31 % | 1 / 4 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 50 % | 79 / 96 % | 99 / 100 % | 54 / 77 % | 20 / 51 % | 40 / 64 % | 22 / 58 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 19 / 43 % | 56 / 96 % | 98 / 100 % | 41 / 65 % | 10 / 28 % | 34 / 51 % | 11 / 39 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 42 % | 87 / 94 % | 93 / 98 % | 45 / 70 % | 15 / 39 % | 32 / 58 % | 48 / 75 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 50 / 76 % | 92 / 97 % | 6 / 18 % | 1 / 6 % | 3 / 10 % | 0 / 3 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 11 / 80 % | 89 / 95 % | 7 / 18 % | 2 / 10 % | 5 / 13 % | 0 / 2 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 38 / 73 % | 86 / 93 % | 41 / 66 % | 6 / 22 % | 25 / 49 % | 3 / 14 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 48 % | 4 / 57 % | 76 / 88 % | 38 / 64 % | 7 / 23 % | 15 / 37 % | 5 / 23 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 13 / 65 % | 74 / 87 % | 8 / 23 % | 1 / 5 % | 6 / 11 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 64 / 81 % | 10 / 28 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 31 % | 41 / 74 % | 8 / 30 % | 14 / 37 % | 8 / 27 % | 13 / 35 % | 1 / 9 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 31 / 71 % | 1 / 13 % | 5 / 13 % | 0 / 2 % | 4 / 8 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 9 / 31 % | 30 / 72 % | 28 / 64 % | 7 / 18 % | 5 / 15 % | 9 / 24 % | 1 / 7 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 8 / 34 % | 22 / 56 % | 0 / 0 % | 5 / 13 % | 0 / 3 % | 5 / 11 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 11 / 56 % | 20 / 59 % | 9 / 26 % | 1 / 7 % | 4 / 10 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 19 / 41 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 1 / 6 % | 9 / 22 % | 0 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 6 / 25 % | 14 / 66 % | 14 / 33 % | 9 / 26 % | 2 / 12 % | 6 / 15 % | 0 / 3 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 10 / 30 % | 5 / 13 % | 1 / 5 % | 3 / 7 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 8 / 17 % | 0 / 0 % | 0 / 0 % | 9 / 26 % | 1 / 6 % | 7 / 16 % | 0 / 4 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 1 % | 3 / 7 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 7 / 26 % | 5 / 9 % | 0 / 2 % | 3 / 5 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 7 / 60 % | 0 / 0 % | 5 / 10 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 2 % | 6 / 12 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 2 % | 6 / 14 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 2 % | 4 / 7 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 2 / 6 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 2 / 4 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 4 / 33 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 2 / 5 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 3 / 6 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 3 / 7 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
