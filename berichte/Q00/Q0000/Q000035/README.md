[English](README.md) · [Deutsch](README.de.md)

# When the Agent Is the Incident: NIST, NSA, and CISA's 10 Key Practices for SI Incident Response

Report Q000035 · Source cybersecurityos.net · Date 2026-10-25 · [Open original](https://www.cybersecurityos.net/posts/ai-devsecops/nist-cisa-nsa-si-incident-response-key-practices/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 74 / 87 % | 95 / 97 % | – | 100 / 100 % | 93 / 96 % | 92 / 94 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 78 / 88 % | 97 / 99 % | – | 100 / 100 % | 93 / 95 % | 94 / 96 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 62 / 77 % | 96 / 99 % | – | 100 / 100 % | 89 / 94 % | 91 / 95 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 60 / 73 % | 91 / 98 % | – | 98 / 99 % | 90 / 94 % | 89 / 93 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 43 / 59 % | 93 / 98 % | – | 97 / 99 % | 68 / 84 % | 74 / 86 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 52 / 70 % | 92 / 97 % | – | 95 / 98 % | 83 / 90 % | 87 / 92 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 26 / 43 % | 83 / 97 % | – | 94 / 96 % | 79 / 89 % | 84 / 91 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 45 / 63 % | 74 / 91 % | – | 92 / 95 % | 79 / 87 % | 71 / 80 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 29 / 52 % | 88 / 98 % | – | 76 / 92 % | 69 / 84 % | 51 / 67 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 52 / 67 % | 79 / 93 % | – | 88 / 94 % | 84 / 91 % | 86 / 92 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 26 / 49 % | 87 / 94 % | – | 54 / 62 % | 65 / 80 % | 70 / 81 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 38 / 68 % | – | 82 / 91 % | 8 / 19 % | 9 / 15 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 80 / 95 % | – | 49 / 69 % | 12 / 27 % | 8 / 18 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 78 / 90 % | 30 / 57 % | 12 / 24 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 73 / 97 % | – | 18 / 37 % | 19 / 46 % | 23 / 40 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 49 / 80 % | – | 64 / 82 % | 67 / 83 % | 73 / 83 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 30 / 53 % | 61 / 97 % | – | 71 / 93 % | 48 / 75 % | 38 / 66 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 63 / 82 % | – | 27 / 49 % | 30 / 54 % | 22 / 33 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 36 / 53 % | 26 / 92 % | – | 61 / 89 % | 39 / 62 % | 18 / 38 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 49 % | 35 / 79 % | – | 60 / 79 % | 42 / 63 % | 31 / 50 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 48 / 64 % | 48 / 85 % | – | 21 / 66 % | 57 / 77 % | 52 / 69 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 57 / 73 % | 21 / 32 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 34 / 58 % | – | 40 / 66 % | 55 / 76 % | 51 / 68 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 50 / 80 % | – | 40 / 74 % | 18 / 41 % | 21 / 37 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 49 / 85 % | – | 17 / 35 % | 14 / 33 % | 12 / 21 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 43 / 72 % | – | 5 / 13 % | 8 / 16 % | 7 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 42 / 86 % | – | 18 / 36 % | 10 / 21 % | 11 / 21 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 28 / 64 % | – | 0 / 0 % | 9 / 20 % | 10 / 17 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 26 / 65 % | – | 21 / 42 % | 23 / 47 % | 15 / 29 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 17 / 44 % | 24 / 44 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 10 / 30 % | 17 / 81 % | – | 13 / 47 % | 13 / 33 % | 22 / 42 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 20 / 44 % | 22 / 44 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 11 / 59 % | – | 18 / 45 % | 13 / 28 % | 16 / 27 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 25 % | 0 / 0 % | – | 2 / 10 % | 11 / 27 % | 16 / 29 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 15 / 50 % | – | 6 / 33 % | 10 / 20 % | 7 / 14 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 4 / 75 % | – | 0 / 0 % | 8 / 18 % | 15 / 24 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 20 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 29 % | 7 / 16 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 22 % | 10 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 10 / 73 % | – | 0 / 0 % | 8 / 17 % | 5 / 11 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 12 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 13 % | 6 / 12 % |
