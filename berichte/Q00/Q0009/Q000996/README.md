[English](README.md) · [Deutsch](README.de.md)

# Addendum to GPT-5 system card: GPT-5-Codex

Report Q000996 · Source deploymentsafety.openai.com · Date 2025-09-15 · [Open original](https://deploymentsafety.openai.com/gpt-5-codex)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Das Addendum berichtet über Sicherheitsbenchmarks, Prompt-Injection-Schutz und Sandbox-Voreinstellungen für GPT‑5‑Codex, das laut Text nicht mehr in Produktion ist. OpenAI stuft das Modell als hochriskant im biologischen und chemischen Bereich ein, aber unterhalb der Schwelle für hohe Cyberfähigkeiten; freigegebener Netzwerkzugriff könne zusätzliche Risiken schaffen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 48 / 66 % | 96 / 100 % | 72 / 85 % | 100 / 100 % | 84 / 91 % | 80 / 89 % | 46 / 68 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 58 / 74 % | 97 / 98 % | 98 / 99 % | 100 / 100 % | 87 / 93 % | 88 / 92 % | 69 / 82 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 49 / 67 % | 85 / 96 % | 84 / 91 % | 98 / 99 % | 34 / 56 % | 80 / 87 % | 67 / 81 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 28 / 50 % | 90 / 99 % | 55 / 69 % | 97 / 98 % | 80 / 90 % | 60 / 74 % | 38 / 58 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 65 / 88 % | 10 / 24 % | 97 / 98 % | 70 / 84 % | 75 / 87 % | 29 / 51 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 36 / 54 % | 93 / 99 % | 12 / 28 % | 97 / 98 % | 77 / 87 % | 61 / 78 % | 47 / 63 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 56 % | 81 / 96 % | 30 / 58 % | 96 / 98 % | 63 / 82 % | 78 / 87 % | 55 / 72 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 81 / 96 % | 12 / 19 % | 96 / 97 % | 21 / 42 % | 13 / 24 % | 5 / 12 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 42 / 90 % | 16 / 31 % | 95 / 98 % | 70 / 85 % | 17 / 30 % | 32 / 50 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 77 / 97 % | 4 / 13 % | 94 / 97 % | 30 / 55 % | 23 / 41 % | 9 / 17 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 46 / 65 % | 73 / 99 % | 55 / 67 % | 51 / 69 % | 70 / 84 % | 80 / 87 % | 57 / 74 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 33 / 53 % | 32 / 76 % | 17 / 38 % | 73 / 89 % | 69 / 84 % | 41 / 59 % | 14 / 30 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 33 / 57 % | 72 / 97 % | 16 / 32 % | 39 / 74 % | 69 / 84 % | 51 / 66 % | 21 / 40 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 61 / 93 % | 1 / 4 % | 61 / 78 % | 13 / 38 % | 10 / 18 % | 5 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 20 / 31 % | 60 / 88 % | 0 / 2 % | 5 / 11 % | 30 / 48 % | 12 / 20 % | 7 / 13 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 47 / 83 % | 1 / 3 % | 0 / 0 % | 8 / 21 % | 9 / 17 % | 4 / 10 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 44 / 95 % | 1 / 5 % | 3 / 19 % | 12 / 28 % | 6 / 13 % | 7 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 16 / 43 % | 0 / 0 % | 43 / 60 % | 7 / 17 % | 6 / 10 % | 1 / 5 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 42 / 62 % | 12 / 34 % | 6 / 12 % | 5 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 36 / 68 % | 0 / 2 % | 4 / 20 % | 9 / 28 % | 8 / 18 % | 1 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 33 / 73 % | 0 / 1 % | 25 / 49 % | 9 / 23 % | 7 / 15 % | 1 / 6 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 32 / 86 % | 1 / 5 % | 26 / 44 % | 9 / 21 % | 7 / 13 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 27 / 93 % | 1 / 6 % | 17 / 32 % | 21 / 45 % | 11 / 22 % | 10 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 12 / 39 % | 0 / 0 % | 2 / 8 % | 0 / 0 % | 22 / 49 % | 9 / 20 % | 6 / 14 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 43 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 15 / 38 % | 20 / 37 % | 6 / 15 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 20 / 49 % | 0 / 1 % | 0 / 0 % | 11 / 32 % | 7 / 20 % | 2 / 6 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 20 / 47 % | 0 / 1 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 4 / 11 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 19 / 75 % | 0 / 3 % | 0 / 0 % | 9 / 30 % | 13 / 27 % | 4 / 15 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 11 / 50 % | 2 / 7 % | 0 / 0 % | 12 / 36 % | 18 / 35 % | 5 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 34 % | 0 / 0 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 30 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 21 % | 8 / 18 % | 5 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 7 / 15 % | 8 / 15 % | 3 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 7 / 18 % | 0 / 3 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 51 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 5 / 11 % | 3 / 10 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % | 6 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 1 / 5 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 3 / 8 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 4 / 7 % | 3 / 7 % |
