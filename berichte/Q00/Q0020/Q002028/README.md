[English](README.md) · [Deutsch](README.de.md)

# Frontier AI safety regulations: A reference for lab staff

Report Q002028 · Source metr.org · Date 2026-01-29 · [Open original](https://metr.org/notes/2026-01-29-frontier-ai-safety-regulations/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR fasst Anforderungen an Risikomanagement, Sicherheit, Modellberichte, Vorfallmeldungen und Hinweisgeberschutz für KI-Entwickler nach US-Bundesstaatengesetzen und dem EU-Rahmen zusammen. Fristen und Pflichten unterscheiden sich; Illinois’ ab 2028 vorgesehene unabhängige Prüfung kontrolliert laut Bericht Verfahren, nicht die tatsächliche Modellsicherheit. Die Darstellung ist eine Übersicht und ersetzt keine offiziellen Gesetzestexte.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 90 / 94 % | 98 / 98 % | 100 / 100 % | 100 / 100 % | 96 / 97 % | 98 / 99 % | 96 / 97 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 43 / 62 % | 100 / 100 % | 91 / 95 % | 100 / 100 % | 88 / 93 % | 91 / 95 % | 82 / 90 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 83 / 90 % | 98 / 99 % | 99 / 100 % | 100 / 100 % | 94 / 96 % | 96 / 97 % | 89 / 95 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 75 / 83 % | 95 / 97 % | 99 / 100 % | 100 / 100 % | 90 / 94 % | 95 / 97 % | 87 / 93 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 57 / 70 % | 99 / 100 % | 93 / 97 % | 95 / 99 % | 86 / 93 % | 92 / 96 % | 89 / 95 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 61 / 75 % | 92 / 96 % | 96 / 98 % | 99 / 100 % | 88 / 94 % | 92 / 97 % | 82 / 91 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 59 / 79 % | 87 / 97 % | 80 / 95 % | 99 / 100 % | 63 / 81 % | 75 / 87 % | 49 / 66 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 54 / 67 % | 97 / 99 % | 77 / 92 % | 92 / 97 % | 75 / 87 % | 72 / 86 % | 82 / 91 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 33 / 58 % | 96 / 99 % | 15 / 37 % | 78 / 92 % | 44 / 66 % | 39 / 67 % | 28 / 47 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 48 / 65 % | 96 / 97 % | 80 / 91 % | 92 / 96 % | 90 / 94 % | 87 / 93 % | 81 / 92 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 65 / 78 % | 96 / 98 % | 95 / 98 % | 86 / 92 % | 88 / 93 % | 91 / 95 % | 81 / 90 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 58 / 75 % | 95 / 98 % | 88 / 94 % | 95 / 98 % | 74 / 85 % | 84 / 91 % | 61 / 75 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 58 / 74 % | 84 / 98 % | 94 / 97 % | 86 / 94 % | 86 / 92 % | 93 / 96 % | 76 / 87 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 52 / 68 % | 69 / 94 % | 92 / 97 % | 33 / 75 % | 79 / 88 % | 66 / 81 % | 44 / 60 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 29 / 56 % | 84 / 99 % | 3 / 22 % | 84 / 92 % | 18 / 41 % | 14 / 33 % | 13 / 27 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 60 / 87 % | 3 / 14 % | 72 / 92 % | 40 / 61 % | 29 / 54 % | 8 / 21 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 29 / 47 % | 41 / 75 % | 14 / 35 % | 3 / 26 % | 48 / 71 % | 66 / 83 % | 18 / 41 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 41 / 61 % | 32 / 75 % | 18 / 43 % | 45 / 78 % | 65 / 81 % | 61 / 82 % | 38 / 63 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 16 / 40 % | 65 / 90 % | 4 / 25 % | 36 / 64 % | 15 / 36 % | 15 / 43 % | 9 / 21 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 19 / 42 % | 48 / 91 % | 19 / 37 % | 7 / 33 % | 45 / 68 % | 60 / 79 % | 16 / 34 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 9 / 25 % | 52 / 77 % | 5 / 24 % | 59 / 87 % | 26 / 47 % | 10 / 32 % | 9 / 24 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 21 / 45 % | 48 / 79 % | 39 / 72 % | 45 / 83 % | 30 / 53 % | 58 / 83 % | 56 / 78 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 54 / 83 % | 4 / 12 % | 56 / 74 % | 25 / 50 % | 33 / 58 % | 13 / 31 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 36 % | 53 / 83 % | 3 / 15 % | 6 / 26 % | 15 / 38 % | 18 / 42 % | 8 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 26 % | 49 / 79 % | 1 / 5 % | 15 / 37 % | 16 / 40 % | 9 / 27 % | 7 / 20 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 47 / 92 % | 10 / 26 % | 0 / 0 % | 18 / 40 % | 26 / 62 % | 11 / 28 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 42 / 94 % | 1 / 8 % | 11 / 37 % | 16 / 39 % | 21 / 52 % | 11 / 25 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 41 / 75 % | 2 / 11 % | 0 / 0 % | 18 / 39 % | 18 / 34 % | 7 / 17 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 41 / 83 % | 0 / 4 % | 0 / 0 % | 9 / 22 % | 9 / 22 % | 5 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 40 / 75 % | 1 / 7 % | 13 / 39 % | 10 / 30 % | 9 / 27 % | 4 / 13 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 23 / 40 % | 18 / 39 % | 32 / 55 % | 25 / 54 % | 15 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 32 / 54 % | 0 / 0 % | 17 / 31 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 3 / 10 % | 0 / 0 % | 30 / 58 % | 18 / 42 % | 10 / 22 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 20 / 36 % | 29 / 55 % | 2 / 8 % | 18 / 45 % | 15 / 33 % | 23 / 51 % | 11 / 25 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 22 / 56 % | 13 / 28 % | 0 / 0 % | 29 / 53 % | 20 / 46 % | 19 / 37 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 19 / 65 % | 1 / 5 % | 19 / 49 % | 17 / 44 % | 9 / 24 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 11 / 44 % | 0 / 0 % | 18 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 9 / 20 % | 14 / 27 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 8 / 18 % | 12 / 21 % | 4 / 9 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 11 / 23 % | 11 / 25 % | 6 / 12 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 10 / 54 % | 0 / 1 % | 0 / 0 % | 8 / 17 % | 9 / 23 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 9 / 22 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 9 / 20 % | 7 / 14 % | 5 / 9 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
