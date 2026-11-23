[English](README.md) · [Deutsch](README.de.md)

# Brief #32: Tencent, DeepSeek and Alibaba on AI safety and open-source

Report Q000678 · Source aisafetychina.substack.com · Date 2026-11-11 · [Open original](https://aisafetychina.substack.com/p/brief-32-tencent-deepseek-and-alibaba)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt eine zunehmend öffentliche Debatte chinesischer KI-Labore über Sicherheitsrisiken offener Modellgewichte. Tencent zufolge habe Hy4 bei internen Tests kein erhöhtes Cyberrisiko gezeigt und bei einem Biosecurity-Benchmark deutlich unter der Hochrisikoschwelle gelegen; die Messmethode ist öffentlich jedoch kaum beschrieben. Alibaba und DeepSeek benennen Risiken offener Gewichte, während die Unternehmen weiter an offenen Veröffentlichungen festhalten und zugleich Schutzmaßnahmen erwägen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 49 % | 98 / 100 % | – | 42 / 66 % | 27 / 48 % | 56 / 73 % | 15 / 37 % | 35 / 60 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 63 / 84 % | 95 / 99 % | – | 78 / 89 % | 79 / 89 % | 84 / 92 % | 91 / 97 % | 60 / 80 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 55 % | 88 / 98 % | – | 55 / 77 % | 26 / 54 % | 62 / 82 % | 37 / 70 % | 51 / 73 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 24 / 52 % | 86 / 100 % | – | 36 / 61 % | 11 / 30 % | 31 / 57 % | 15 / 38 % | 36 / 68 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 51 / 74 % | 86 / 98 % | – | 63 / 83 % | 35 / 57 % | 78 / 89 % | 55 / 78 % | 23 / 53 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 28 / 50 % | 81 / 92 % | – | 60 / 80 % | 35 / 56 % | 55 / 72 % | 61 / 74 % | 24 / 48 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 42 / 66 % | 80 / 99 % | – | 38 / 64 % | 33 / 54 % | 59 / 75 % | 33 / 55 % | 32 / 59 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 44 / 67 % | 78 / 98 % | – | 45 / 69 % | 24 / 43 % | 57 / 72 % | 25 / 50 % | 33 / 61 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 29 / 55 % | 76 / 98 % | – | 38 / 64 % | 39 / 55 % | 71 / 83 % | 22 / 44 % | 52 / 75 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 45 % | 74 / 98 % | – | 46 / 71 % | 18 / 45 % | 36 / 63 % | 13 / 39 % | 36 / 65 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 28 / 53 % | 71 / 92 % | – | 19 / 43 % | 44 / 66 % | 69 / 83 % | 72 / 89 % | 38 / 69 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 34 / 56 % | 57 / 99 % | – | 60 / 81 % | 30 / 58 % | 72 / 87 % | 27 / 62 % | 36 / 65 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 72 / 93 % | – | 18 / 46 % | 12 / 29 % | 18 / 45 % | 3 / 16 % | 26 / 51 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 26 / 49 % | 71 / 91 % | – | 47 / 74 % | 43 / 69 % | 63 / 80 % | 50 / 78 % | 26 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 48 % | 69 / 95 % | – | 27 / 55 % | 12 / 35 % | 17 / 44 % | 9 / 31 % | 19 / 44 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 21 / 41 % | 39 / 64 % | – | 42 / 66 % | 33 / 55 % | 51 / 64 % | 8 / 14 % | 27 / 50 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 50 / 93 % | – | 19 / 49 % | 9 / 29 % | 24 / 45 % | 2 / 9 % | 10 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 48 / 96 % | – | 42 / 68 % | 11 / 29 % | 9 / 27 % | 4 / 15 % | 14 / 41 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 48 / 89 % | – | 17 / 43 % | 5 / 18 % | 10 / 31 % | 1 / 6 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 38 / 78 % | – | 10 / 25 % | 4 / 10 % | 7 / 17 % | 1 / 6 % | 7 / 24 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 33 % | 37 / 86 % | – | 14 / 38 % | 8 / 23 % | 20 / 38 % | 3 / 11 % | 20 / 47 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 31 / 91 % | – | 10 / 33 % | 4 / 13 % | 5 / 16 % | 2 / 11 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 26 / 80 % | – | 11 / 30 % | 1 / 9 % | 8 / 14 % | 0 / 0 % | 14 / 31 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 24 / 86 % | – | 11 / 38 % | 2 / 9 % | 9 / 30 % | 1 / 5 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 11 / 39 % | 7 / 91 % | – | 9 / 29 % | 3 / 14 % | 8 / 21 % | 1 / 6 % | 23 / 48 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 22 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 20 / 56 % | – | 15 / 42 % | 4 / 13 % | 15 / 32 % | 1 / 7 % | 7 / 24 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 9 / 58 % | – | 6 / 14 % | 1 / 6 % | 6 / 16 % | 0 / 1 % | 20 / 50 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | 2 / 9 % | 6 / 12 % | 0 / 2 % | 16 / 35 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 16 / 95 % | – | 13 / 40 % | 2 / 12 % | 8 / 29 % | 1 / 6 % | 14 / 31 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 7 / 67 % | – | 11 / 33 % | 7 / 24 % | 14 / 49 % | 2 / 11 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 8 / 19 % | 4 / 11 % | 7 / 15 % | 0 / 1 % | 13 / 38 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 11 / 84 % | – | 10 / 27 % | 5 / 16 % | 11 / 22 % | 1 / 7 % | 12 / 36 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 12 / 39 % | – | 12 / 33 % | 3 / 11 % | 10 / 28 % | 0 / 2 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 12 / 79 % | – | 12 / 37 % | 7 / 20 % | 12 / 40 % | 2 / 10 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 3 / 95 % | – | 10 / 30 % | 5 / 19 % | 10 / 28 % | 1 / 5 % | 8 / 29 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 10 / 71 % | – | 7 / 18 % | 1 / 9 % | 6 / 17 % | 0 / 1 % | 8 / 25 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 7 / 19 % | 4 / 12 % | 8 / 19 % | 0 / 2 % | 4 / 18 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 8 / 23 % | 2 / 7 % | 7 / 15 % | 0 / 1 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 4 / 59 % | – | 8 / 21 % | 5 / 18 % | 6 / 15 % | 0 / 2 % | 7 / 25 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 1 / 5 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 3 / 8 % | 6 / 10 % | 0 / 2 % | 4 / 17 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 2 / 6 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
