[English](README.md) · [Deutsch](README.de.md)

# Mapping AI-enabled cyber threats

Report Q001822 · Source anthropic.com · Date 2026-06-03 · [Open original](https://www.anthropic.com/research/attack-navigator)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic wertete 832 wegen mutmaßlich schädlicher Cyberaktivitäten gesperrte Konten aus und berichtet, dass der Anteil mit mittlerem oder höherem KI-Risiko binnen eines Jahres von etwa 33,5 auf 56,1 Prozent gestiegen sei; verbesserte Erkennung könne laut Bericht mitgewirkt haben. Besonders riskant seien KI-gestützte operative Schritte und deren autonome Verknüpfung, während die Analyse nur eine ausgewählte Gruppe gesperrter Konten und Anthropic-eigene Risikobewertungen umfasst.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 42 % | 91 / 99 % | – | 100 / 100 % | 68 / 83 % | 18 / 38 % | 55 / 69 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 32 / 52 % | 92 / 100 % | – | 75 / 90 % | 56 / 78 % | 14 / 33 % | 42 / 63 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 36 / 58 % | 88 / 99 % | – | 85 / 95 % | 28 / 48 % | 30 / 53 % | 77 / 85 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 27 / 48 % | 78 / 97 % | – | 87 / 94 % | 70 / 84 % | 13 / 33 % | 45 / 61 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 24 / 41 % | 66 / 89 % | – | 72 / 86 % | 44 / 67 % | 20 / 37 % | 33 / 52 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 17 / 76 % | – | 69 / 84 % | 38 / 62 % | 7 / 20 % | 12 / 24 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 19 / 41 % | 12 / 58 % | – | 66 / 77 % | 22 / 47 % | 12 / 24 % | 45 / 60 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 50 % | 0 / 0 % | – | 57 / 66 % | 38 / 66 % | 19 / 39 % | 63 / 77 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 4 / 40 % | – | 62 / 84 % | 11 / 27 % | 5 / 12 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 22 / 43 % | 20 / 82 % | – | 55 / 77 % | 36 / 63 % | 8 / 24 % | 19 / 35 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 25 / 46 % | 20 / 100 % | – | 17 / 74 % | 53 / 76 % | 35 / 55 % | 38 / 62 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 41 / 75 % | – | 50 / 70 % | 10 / 30 % | 2 / 11 % | 11 / 23 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 6 / 48 % | – | 50 / 67 % | 7 / 16 % | 0 / 0 % | 8 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 31 % | 16 / 57 % | – | 0 / 0 % | 31 / 55 % | 12 / 27 % | 39 / 53 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 33 / 90 % | – | 30 / 59 % | 28 / 52 % | 9 / 20 % | 19 / 35 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 11 / 51 % | – | 0 / 0 % | 31 / 57 % | 9 / 28 % | 24 / 40 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 30 / 59 % | 11 / 34 % | 4 / 17 % | 10 / 23 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 56 % | – | 21 / 41 % | 25 / 48 % | 8 / 24 % | 13 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 23 / 67 % | – | 10 / 41 % | 24 / 52 % | 6 / 21 % | 20 / 40 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 31 % | 23 / 79 % | – | 22 / 41 % | 11 / 34 % | 6 / 21 % | 12 / 21 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 12 / 75 % | – | 0 / 0 % | 23 / 51 % | 0 / 0 % | 9 / 21 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 12 / 40 % | 0 / 0 % | – | 0 / 0 % | 23 / 47 % | 10 / 24 % | 16 / 34 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 46 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 17 / 43 % | 4 / 10 % | 21 / 33 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 34 % | 0 / 0 % | – | 0 / 0 % | 7 / 26 % | 3 / 12 % | 19 / 31 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 7 / 89 % | – | 18 / 60 % | 13 / 40 % | 6 / 18 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 0 / 0 % | 12 / 27 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 27 % | 2 / 8 % | 9 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 10 / 26 % | 6 / 61 % | – | 0 / 0 % | 8 / 23 % | 3 / 13 % | 8 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 0 / 0 % | 6 / 12 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 20 % | 0 / 0 % | 9 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 2 / 6 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 25 % | 4 / 14 % | 7 / 17 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 8 / 14 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 7 / 21 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 2 / 8 % | 6 / 11 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
