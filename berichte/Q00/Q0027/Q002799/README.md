[English](README.md) · [Deutsch](README.de.md)

# Details about METR's preliminary evaluation of OpenAI o1-preview

Report Q002799 · Source metr.org · Date 2024-09-12 · [Open original](https://metr.org/evaluations/openai-o1-preview-report/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR zufolge übertrafen o1-mini und o1-preview im allgemeinen Autonomietest Claude 3.5 Sonnet nicht; mit angepasstem Agentengerüst erzielten sie vergleichbare Ergebnisse. Bei sieben anspruchsvollen KI-Forschungsaufgaben machte o1-preview in zwei Fällen nennenswerte Fortschritte, doch METR betont, dass kurze Testzeit, API-Latenz und weitere Einschränkungen die vorläufigen Ergebnisse beeinflusst haben könnten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 64 % | 89 / 99 % | 15 / 50 % | 99 / 100 % | 40 / 68 % | 58 / 76 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 52 / 73 % | 94 / 100 % | 56 / 81 % | 92 / 97 % | 59 / 81 % | 57 / 74 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 27 / 53 % | 9 / 52 % | 6 / 25 % | 89 / 95 % | 44 / 70 % | 12 / 28 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 52 % | 12 / 74 % | 9 / 40 % | 89 / 94 % | 33 / 61 % | 27 / 51 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 28 / 47 % | 12 / 49 % | 7 / 19 % | 86 / 90 % | 54 / 74 % | 31 / 49 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 47 / 66 % | 75 / 97 % | 66 / 85 % | 78 / 89 % | 70 / 85 % | 70 / 81 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 26 / 54 % | 67 / 91 % | 12 / 40 % | 76 / 89 % | 47 / 69 % | 23 / 45 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 28 / 49 % | 66 / 96 % | 2 / 11 % | 76 / 89 % | 23 / 48 % | 21 / 38 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 54 % | 23 / 84 % | 13 / 24 % | 74 / 80 % | 48 / 69 % | 22 / 40 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 12 / 81 % | 0 / 0 % | 66 / 78 % | 8 / 21 % | 9 / 17 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 27 / 51 % | 0 / 0 % | 4 / 16 % | 57 / 70 % | 23 / 50 % | 16 / 29 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 24 / 53 % | 11 / 80 % | 8 / 32 % | 24 / 53 % | 39 / 70 % | 22 / 43 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 33 / 55 % | 9 / 62 % | 1 / 7 % | 35 / 52 % | 15 / 43 % | 17 / 33 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 48 % | 0 / 0 % | 2 / 14 % | 0 / 0 % | 28 / 54 % | 16 / 32 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 24 / 54 % | 6 / 15 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 20 / 58 % | 9 / 55 % | 0 / 0 % | 0 / 0 % | 10 / 38 % | 14 / 27 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 40 % | 5 / 11 % | 9 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 34 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 39 % | 13 / 27 % | 1 / 6 % | 0 / 0 % | 14 / 36 % | 12 / 27 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 13 / 49 % | 0 / 0 % | 7 / 40 % | 5 / 12 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 12 / 65 % | 0 / 0 % | 1 / 9 % | 7 / 17 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 4 / 77 % | 0 / 4 % | 0 / 0 % | 8 / 23 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
