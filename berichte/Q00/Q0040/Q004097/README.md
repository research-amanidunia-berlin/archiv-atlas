[English](README.md) · [Deutsch](README.de.md)

# Updating the Frontier Safety Framework

Report Q004097 · Source deepmind.google · Date 2025-02-04 · [Open original](https://deepmind.google/blog/updating-the-frontier-safety-framework/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind aktualisiert sein Frontier Safety Framework mit Mindestempfehlungen für Sicherheitsstufen, einem Prüfverfahren vor der allgemeinen Bereitstellung kritischer Modelle und ersten Ansätzen gegen mögliche Täuschung durch autonome Systeme. Das Unternehmen betont, dass die Wahrscheinlichkeit solcher Fähigkeiten unklar sei, automatisierte Überwachung langfristig womöglich nicht genüge und gemeinsame Forschung nötig bleibe; konkrete Schwellenwerte und Wirksamkeitsdaten nennt der Bericht nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 43 / 60 % | 99 / 100 % | 100 / 100 % | 68 / 83 % | 42 / 67 % | 67 / 83 % | 69 / 88 % | 57 / 76 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 39 / 60 % | 77 / 93 % | 98 / 99 % | 66 / 83 % | 27 / 54 % | 63 / 79 % | 47 / 76 % | 32 / 60 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 54 % | 90 / 99 % | 94 / 99 % | 44 / 73 % | 31 / 59 % | 57 / 79 % | 38 / 72 % | 18 / 38 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 23 / 49 % | 34 / 80 % | 91 / 97 % | 49 / 72 % | 15 / 40 % | 31 / 59 % | 14 / 41 % | 38 / 64 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 31 / 54 % | 90 / 97 % | 69 / 88 % | 57 / 77 % | 34 / 56 % | 70 / 82 % | 52 / 66 % | 38 / 63 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 30 / 57 % | 87 / 99 % | 84 / 96 % | 61 / 80 % | 33 / 59 % | 69 / 84 % | 30 / 62 % | 40 / 66 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 45 % | 83 / 97 % | 77 / 88 % | 39 / 63 % | 19 / 40 % | 48 / 67 % | 21 / 43 % | 23 / 45 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 27 / 56 % | 40 / 82 % | 78 / 96 % | 26 / 51 % | 25 / 55 % | 51 / 77 % | 22 / 68 % | 30 / 59 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 27 / 47 % | 54 / 82 % | 76 / 85 % | 33 / 58 % | 14 / 29 % | 24 / 45 % | 11 / 23 % | 10 / 23 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 21 / 48 % | 67 / 95 % | 72 / 85 % | 35 / 60 % | 15 / 38 % | 25 / 50 % | 13 / 34 % | 25 / 52 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 32 % | 68 / 94 % | 72 / 85 % | 20 / 47 % | 9 / 30 % | 24 / 49 % | 3 / 19 % | 25 / 51 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 30 / 52 % | 42 / 89 % | 69 / 90 % | 46 / 70 % | 19 / 41 % | 19 / 53 % | 14 / 32 % | 12 / 28 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 17 / 40 % | 62 / 88 % | 50 / 78 % | 20 / 44 % | 7 / 22 % | 15 / 29 % | 4 / 17 % | 38 / 61 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 42 / 82 % | 59 / 79 % | 10 / 29 % | 2 / 8 % | 8 / 14 % | 0 / 0 % | 17 / 36 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 33 / 53 % | 19 / 60 % | 24 / 51 % | 58 / 78 % | 24 / 48 % | 55 / 74 % | 15 / 36 % | 5 / 17 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 39 % | 58 / 95 % | 49 / 79 % | 25 / 48 % | 8 / 24 % | 18 / 42 % | 12 / 30 % | 28 / 55 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 37 % | 56 / 92 % | 24 / 60 % | 21 / 46 % | 12 / 37 % | 23 / 51 % | 9 / 26 % | 20 / 48 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 56 / 92 % | 20 / 51 % | 14 / 37 % | 6 / 19 % | 11 / 26 % | 2 / 9 % | 20 / 47 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 55 / 87 % | 4 / 21 % | 13 / 31 % | 6 / 21 % | 10 / 26 % | 3 / 14 % | 21 / 48 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 14 / 48 % | 53 / 90 % | 16 / 54 % | 29 / 56 % | 10 / 29 % | 22 / 52 % | 8 / 32 % | 15 / 39 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 47 % | 28 / 82 % | 49 / 71 % | 13 / 39 % | 9 / 27 % | 15 / 46 % | 4 / 18 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 11 / 29 % | 48 / 96 % | 33 / 56 % | 13 / 37 % | 5 / 18 % | 11 / 33 % | 1 / 7 % | 23 / 48 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 34 / 80 % | 38 / 75 % | 41 / 67 % | 15 / 42 % | 13 / 36 % | 11 / 35 % | 17 / 43 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 37 / 84 % | 30 / 65 % | 16 / 37 % | 5 / 16 % | 7 / 23 % | 2 / 9 % | 18 / 44 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 16 / 46 % | 15 / 71 % | 35 / 64 % | 22 / 49 % | 10 / 28 % | 14 / 38 % | 8 / 25 % | 9 / 27 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 34 / 61 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 9 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 34 / 57 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 15 / 29 % | 27 / 83 % | 11 / 25 % | 11 / 33 % | 5 / 16 % | 11 / 28 % | 6 / 18 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 11 / 33 % | 16 / 80 % | 14 / 37 % | 10 / 28 % | 4 / 17 % | 8 / 23 % | 1 / 7 % | 21 / 48 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 3 / 36 % | 6 / 25 % | 9 / 20 % | 3 / 14 % | 8 / 18 % | 0 / 2 % | 18 / 36 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 18 / 55 % | 3 / 23 % | 10 / 25 % | 1 / 7 % | 10 / 25 % | 0 / 0 % | 12 / 32 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 15 / 52 % | 8 / 24 % | 8 / 20 % | 1 / 5 % | 6 / 16 % | 0 / 0 % | 5 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 32 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 4 / 13 % | 8 / 20 % | 0 / 3 % | 4 / 15 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 14 / 43 % | 0 / 0 % | 14 / 38 % | 1 / 10 % | 11 / 37 % | 1 / 8 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 12 / 45 % | 13 / 35 % | 13 / 35 % | 4 / 12 % | 12 / 34 % | 1 / 5 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 25 % | 0 / 0 % | 7 / 11 % | 0 / 2 % | 9 / 27 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 11 / 31 % | 9 / 28 % | 0 / 0 % | 9 / 18 % | 0 / 3 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 5 / 13 % | 8 / 22 % | 3 / 12 % | 11 / 35 % | 1 / 4 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 10 / 51 % | 10 / 31 % | 7 / 17 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 10 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 28 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 77 % | 0 / 7 % | 9 / 22 % | 3 / 11 % | 9 / 18 % | 0 / 3 % | 5 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 8 / 17 % | 3 / 8 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 5 / 16 % |
