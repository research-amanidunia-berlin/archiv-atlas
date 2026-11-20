[English](README.md) · [Deutsch](README.de.md)

# The Loss of Control Playbook: Degrees, Dynamics, and Preparedness

Report Q000810 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/governance/loss-of-control)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht ordnet Kontrollverlust durch KI in drei ungefähre Stufen ein und empfiehlt mit DAP, Einsatzkontext, Handlungsmöglichkeiten und Berechtigungen systematisch zu prüfen und zu begrenzen. Die Autoren halten einen künftigen Zustand erhöhter Verwundbarkeit für möglich und raten, ihn zu vermeiden oder durch mehrschichtige Governance- und Technikmaßnahmen unter Kontrolle zu halten; ihre Zukunftsszenarien sind spekulativ, und die Maßnahmen beseitigen das Risiko nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 54 / 69 % | 100 / 100 % | 73 / 91 % | – | 81 / 91 % | 78 / 89 % | 83 / 91 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 17 / 36 % | 97 / 100 % | 25 / 39 % | – | 56 / 79 % | 44 / 66 % | 41 / 63 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 56 / 74 % | 92 / 98 % | 90 / 97 % | – | 83 / 91 % | 75 / 88 % | 79 / 89 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 32 % | 74 / 96 % | 2 / 14 % | – | 12 / 33 % | 9 / 25 % | 10 / 35 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 27 / 50 % | 39 / 95 % | 34 / 77 % | – | 70 / 86 % | 21 / 48 % | 46 / 76 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 21 / 51 % | 65 / 95 % | 7 / 25 % | – | 35 / 63 % | 19 / 43 % | 41 / 61 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 24 / 50 % | 64 / 98 % | 24 / 57 % | – | 45 / 71 % | 44 / 70 % | 54 / 78 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 16 / 41 % | 53 / 98 % | 21 / 61 % | – | 33 / 65 % | 23 / 52 % | 27 / 62 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 19 / 38 % | 44 / 87 % | 13 / 43 % | – | 38 / 66 % | 14 / 42 % | 42 / 66 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 22 / 48 % | 40 / 97 % | 9 / 35 % | – | 19 / 55 % | 19 / 43 % | 31 / 64 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 10 / 33 % | 36 / 97 % | 6 / 28 % | – | 17 / 44 % | 10 / 32 % | 18 / 49 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 17 / 36 % | 33 / 76 % | 6 / 21 % | – | 19 / 53 % | 10 / 33 % | 17 / 63 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 24 / 45 % | 29 / 96 % | 3 / 14 % | – | 19 / 42 % | 9 / 24 % | 24 / 48 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 14 / 34 % | 28 / 89 % | 1 / 8 % | – | 9 / 26 % | 5 / 13 % | 20 / 38 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 9 / 28 % | 26 / 97 % | 1 / 12 % | – | 14 / 38 % | 7 / 20 % | 10 / 32 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 15 / 41 % | 7 / 51 % | 1 / 6 % | – | 21 / 58 % | 9 / 29 % | 25 / 61 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 24 / 50 % | 1 / 30 % | 1 / 9 % | – | 8 / 25 % | 5 / 17 % | 10 / 27 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 15 / 36 % | 23 / 80 % | 1 / 7 % | – | 13 / 41 % | 9 / 29 % | 15 / 42 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 21 / 44 % | 3 / 97 % | 4 / 26 % | – | 20 / 51 % | 8 / 36 % | 22 / 50 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 21 / 42 % | 10 / 82 % | 2 / 11 % | – | 15 / 44 % | 6 / 22 % | 17 / 41 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 8 / 29 % | 19 / 78 % | 7 / 22 % | – | 17 / 41 % | 14 / 43 % | 20 / 53 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 1 / 62 % | 2 / 10 % | – | 19 / 48 % | 9 / 30 % | 9 / 23 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 19 / 61 % | 0 / 2 % | – | 6 / 13 % | 3 / 6 % | 6 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 17 / 41 % | 15 / 95 % | 1 / 9 % | – | 18 / 55 % | 8 / 32 % | 13 / 57 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 18 / 59 % | 0 / 0 % | – | 7 / 23 % | 0 / 0 % | 7 / 12 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 14 / 66 % | 1 / 7 % | – | 8 / 25 % | 4 / 13 % | 11 / 24 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 32 % | 0 / 0 % | 0 / 1 % | – | 5 / 13 % | 0 / 0 % | 7 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 12 / 41 % | 7 / 49 % | 3 / 14 % | – | 12 / 39 % | 7 / 30 % | 10 / 34 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 11 / 26 % | 1 / 74 % | 0 / 4 % | – | 6 / 18 % | 4 / 12 % | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 6 / 23 % | 11 / 89 % | 0 / 1 % | – | 6 / 15 % | 3 / 12 % | 5 / 10 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 7 / 27 % | 10 / 61 % | 0 / 6 % | – | 10 / 29 % | 7 / 21 % | 9 / 23 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 4 % | – | 9 / 34 % | 0 / 6 % | 6 / 21 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 8 / 20 % | 5 / 87 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 7 / 16 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 3 % | – | 8 / 26 % | 1 / 9 % | 8 / 34 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 7 / 57 % | 0 / 0 % | – | 5 / 15 % | 2 / 7 % | 7 / 16 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 6 / 28 % | 3 / 76 % | 0 / 2 % | – | 7 / 23 % | 5 / 15 % | 6 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 5 / 13 % | 4 / 10 % | 6 / 12 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 2 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 5 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 4 / 81 % | 0 / 2 % | – | 5 / 13 % | 0 / 0 % | 4 / 7 % |
