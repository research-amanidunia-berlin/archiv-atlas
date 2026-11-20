[English](README.md) · [Deutsch](README.de.md)

# Redeploying Claude Fable 5

Report Q003023 · Source anthropic.com · Date 2026-06-30 · [Open original](https://www.anthropic.com/news/redeploying-fable-5)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic erklärt, die Exportkontrollen für Fable 5 und Mythos 5 seien aufgehoben; Fable 5 solle ab 1. Juli wieder weltweit verfügbar sein. Nach einem Bericht über eine Umgehung seiner Schutzmaßnahmen habe Anthropic einen neuen Klassifikator eingeführt, der die beschriebene Methode laut Unternehmen in über 99 Prozent der Fälle blockiere, aber auch mehr harmlose Anfragen treffen könne. Zudem schlägt Anthropic mit Partnern einen Bewertungsrahmen für Jailbreaks vor und kündigt engere Zusammenarbeit mit US-Behörden an.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 40 / 59 % | 99 / 100 % | – | 100 / 100 % | 71 / 85 % | 68 / 81 % | 32 / 56 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 30 / 56 % | 99 / 100 % | – | 98 / 99 % | 70 / 83 % | 82 / 90 % | 56 / 72 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 48 / 69 % | 47 / 86 % | – | 99 / 100 % | 67 / 83 % | 68 / 82 % | 34 / 53 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 49 / 66 % | 99 / 100 % | – | 98 / 99 % | 79 / 88 % | 85 / 91 % | 50 / 65 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 58 % | 97 / 100 % | – | 98 / 100 % | 64 / 83 % | 79 / 89 % | 67 / 83 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 50 / 65 % | 93 / 97 % | – | 97 / 99 % | 79 / 88 % | 84 / 91 % | 51 / 68 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 46 / 65 % | 92 / 97 % | – | 95 / 99 % | 22 / 40 % | 88 / 93 % | 51 / 71 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 50 / 69 % | 54 / 97 % | – | 95 / 98 % | 79 / 88 % | 58 / 73 % | 26 / 45 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 35 / 53 % | 95 / 99 % | – | 83 / 95 % | 62 / 80 % | 68 / 82 % | 27 / 44 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 53 / 70 % | 85 / 98 % | – | 95 / 98 % | 53 / 69 % | 89 / 93 % | 79 / 88 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 40 / 59 % | 65 / 92 % | – | 93 / 96 % | 78 / 87 % | 80 / 86 % | 49 / 65 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 38 / 58 % | 55 / 96 % | – | 91 / 97 % | 74 / 86 % | 79 / 88 % | 32 / 53 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 28 / 52 % | 90 / 99 % | – | 75 / 92 % | 69 / 84 % | 58 / 74 % | 41 / 65 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 21 / 50 % | – | 81 / 86 % | 34 / 61 % | 36 / 58 % | 10 / 22 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 43 / 96 % | – | 78 / 86 % | 49 / 73 % | 30 / 53 % | 16 / 34 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 44 / 65 % | 34 / 87 % | – | 76 / 88 % | 77 / 87 % | 76 / 83 % | 48 / 62 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 73 / 93 % | – | 70 / 86 % | 14 / 36 % | 13 / 29 % | 6 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 53 / 93 % | – | 69 / 85 % | 40 / 67 % | 37 / 63 % | 13 / 30 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 27 / 50 % | 67 / 93 % | – | 59 / 78 % | 35 / 59 % | 29 / 47 % | 18 / 33 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 64 / 98 % | – | 61 / 75 % | 16 / 35 % | 11 / 23 % | 7 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 17 / 47 % | – | 56 / 74 % | 7 / 15 % | 7 / 10 % | 1 / 4 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 45 / 77 % | – | 49 / 72 % | 24 / 46 % | 29 / 50 % | 13 / 34 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 46 / 58 % | 31 / 57 % | 34 / 50 % | 13 / 31 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 46 / 97 % | – | 25 / 44 % | 31 / 59 % | 31 / 57 % | 21 / 41 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 41 / 97 % | – | 42 / 79 % | 39 / 63 % | 46 / 61 % | 21 / 41 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 27 / 78 % | – | 46 / 65 % | 21 / 44 % | 17 / 32 % | 8 / 15 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 45 / 70 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 33 / 65 % | – | 44 / 59 % | 22 / 46 % | 29 / 54 % | 10 / 22 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 40 / 92 % | – | 35 / 54 % | 10 / 21 % | 8 / 16 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 34 / 80 % | – | 39 / 58 % | 27 / 52 % | 20 / 43 % | 7 / 17 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 9 / 54 % | – | 38 / 52 % | 8 / 16 % | 0 / 0 % | 2 / 6 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 23 / 55 % | – | 21 / 44 % | 28 / 49 % | 30 / 46 % | 12 / 27 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 11 / 55 % | – | 0 / 0 % | 25 / 54 % | 27 / 51 % | 16 / 44 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 26 / 78 % | – | 3 / 16 % | 11 / 26 % | 10 / 20 % | 6 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 41 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 18 / 37 % | 13 / 29 % | 19 / 36 % | 8 / 20 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 17 / 29 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 16 % | 15 / 26 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 15 / 49 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 3 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 48 % | – | 0 / 0 % | 9 / 22 % | 0 / 0 % | 4 / 11 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 5 / 59 % | – | 0 / 0 % | 7 / 16 % | 9 / 15 % | 4 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
