[English](README.md) · [Deutsch](README.de.md)

# Red-teaming auto mode: lessons from our first external monitor campaign with Anthropic

Report Q000816 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/monitoring/pilot-automode-campaign)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Apollo berichtet über einen Pilot-Red-Team-Test von Anthropic Auto Mode, der eine Testmethodik für Monitore autonomer Programmieragenten erproben sollte. Genannt werden Fragen zu Eingriffszeitpunkt, Nutzerautorisierung, Vertrauensgrenzen und Informationsumfang; konkrete Messwerte fehlen. Der bereitgestellte Text wirkt unvollständig und endet abrupt mit „oUR FINDINGS“.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 56 % | 73 / 95 % | 31 / 74 % | – | 44 / 71 % | – | 42 / 69 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 27 / 46 % | 72 / 92 % | 11 / 41 % | – | 54 / 77 % | – | 15 / 38 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 49 / 69 % | 59 / 88 % | 69 / 88 % | – | 70 / 86 % | – | 33 / 61 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 51 % | 65 / 95 % | 15 / 51 % | – | 55 / 77 % | – | 25 / 56 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 23 / 41 % | 56 / 78 % | 2 / 7 % | – | 16 / 37 % | – | 4 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 28 / 51 % | 53 / 95 % | 10 / 35 % | – | 35 / 63 % | – | 24 / 47 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 27 / 49 % | 25 / 82 % | 26 / 56 % | – | 41 / 67 % | – | 24 / 51 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 40 / 81 % | 3 / 15 % | – | 20 / 43 % | – | 7 / 17 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 20 / 45 % | 0 / 0 % | 4 / 19 % | – | 27 / 54 % | – | 12 / 32 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 22 / 44 % | 26 / 93 % | 2 / 12 % | – | 22 / 52 % | – | 7 / 25 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 17 / 39 % | 16 / 74 % | 13 / 38 % | – | 25 / 56 % | – | 12 / 31 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 23 / 49 % | 12 / 54 % | 14 / 46 % | – | 25 / 49 % | – | 21 / 49 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 9 / 37 % | 1 / 9 % | – | 22 / 51 % | – | 5 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 21 / 44 % | – | 0 / 2 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 21 / 55 % | 0 / 0 % | – | 7 / 20 % | – | 4 / 12 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 18 / 47 % | 0 / 4 % | – | 8 / 23 % | – | 6 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 1 / 6 % | – | 15 / 39 % | – | 3 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 11 / 30 % | – | 3 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 1 / 5 % | – | 11 / 35 % | – | 1 / 6 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 1 / 10 % | – | 10 / 31 % | – | 5 / 17 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 10 / 38 % | 1 / 5 % | – | 9 / 24 % | – | 1 / 5 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 3 % | – | 8 / 20 % | – | 2 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 49 % | 0 / 0 % | – | 6 / 14 % | – | 1 / 6 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 5 % | – | 7 / 19 % | – | 4 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 15 % | – | 2 / 7 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 14 % | – | 1 / 3 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | – | 1 / 3 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 11 % | – | 0 / 4 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 4 % | – | 6 / 13 % | – | 2 / 7 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | – | 1 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 1 / 4 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 15 % | – | 1 / 5 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | – | 0 / 1 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 15 % | – | 2 / 9 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 0 / 2 % |
