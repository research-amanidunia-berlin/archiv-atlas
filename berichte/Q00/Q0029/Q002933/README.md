[English](README.md) · [Deutsch](README.de.md)

# Measuring the impact of post-training enhancements

Report Q002933 · Source metr.org · Date 2024-03-15 · [Open original](https://metr.org/blog/2024-03-15-measuring-post-impact-enhancements/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR berichtet, dass GPT-4-Post-Training die Erfolgsquote eines einfachen Agenten auf dem untersuchten Aufgabenmix deutlich erhöhte, während zusätzliche Werkzeuge, Prompts und ein Reward-Modell nur einen kleineren, statistisch nicht signifikanten Zuwachs brachten. Da die Aufgaben keine gezielte Prüfung gefährlicher Fähigkeiten waren und die Versuche begrenzt blieben, sind die Zahlen vorläufig und erlauben keine abschließende Aussage über weiteres Verbesserungspotenzial.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 60 % | 68 / 96 % | 8 / 36 % | 96 / 98 % | 26 / 59 % | 38 / 62 % | 13 / 36 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 34 / 91 % | 5 / 22 % | 84 / 92 % | 18 / 46 % | 18 / 37 % | 3 / 18 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 40 / 68 % | 56 / 91 % | 36 / 74 % | 64 / 83 % | 0 / 0 % | 44 / 69 % | 13 / 39 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 10 / 60 % | 5 / 22 % | 61 / 78 % | 33 / 62 % | 10 / 25 % | 5 / 18 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 44 % | 54 / 90 % | 5 / 22 % | 48 / 73 % | 31 / 56 % | 21 / 41 % | 2 / 11 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 37 % | 53 / 85 % | 1 / 9 % | 28 / 58 % | 13 / 36 % | 11 / 28 % | 1 / 7 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 20 / 47 % | 38 / 95 % | 9 / 41 % | 32 / 64 % | 30 / 62 % | 19 / 41 % | 4 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 37 / 86 % | 6 / 29 % | 30 / 55 % | 26 / 54 % | 17 / 34 % | 6 / 19 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 19 / 54 % | 0 / 0 % | 35 / 50 % | 10 / 30 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 32 / 86 % | 0 / 0 % | 0 / 12 % | 7 / 18 % | 0 / 0 % | 1 / 6 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 60 % | 5 / 13 % | 0 / 0 % | 1 / 5 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 1 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 28 / 66 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 10 / 21 % | 2 / 8 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 14 / 49 % | 0 / 4 % | 27 / 50 % | 8 / 26 % | 14 / 27 % | 1 / 7 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 20 / 52 % | 0 / 0 % | 14 / 49 % | 6 / 14 % | 0 / 0 % | 1 / 5 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 18 / 47 % | 0 / 0 % | 1 / 7 % | 0 / 0 % | 14 / 40 % | 10 / 21 % | 2 / 10 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 17 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 16 / 56 % | 0 / 0 % | 16 / 41 % | 7 / 18 % | 0 / 0 % | 1 / 4 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 10 / 25 % | 14 / 27 % | 2 / 7 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 12 / 37 % | 13 / 25 % | 2 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 34 % | 12 / 52 % | 0 / 3 % | 0 / 0 % | 9 / 24 % | 8 / 19 % | 1 / 7 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 33 % | 11 / 22 % | 1 / 5 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 9 / 65 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 7 / 14 % | 1 / 7 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 9 / 65 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 1 / 4 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 5 / 9 % | 0 / 2 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 0 / 0 % | 1 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 2 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
