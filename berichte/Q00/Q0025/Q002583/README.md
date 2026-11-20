[English](README.md) · [Deutsch](README.de.md)

# Cyber Operation: Phishing and scripting support

Report Q002583 · Source openai.com · Date 2025-10-01 · [Open original](https://openai.com/index/disrupting-malicious-uses-of-ai-phishing-and-scripting-support/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI zufolge nutzte eine Gruppe gesperrter Konten ChatGPT zur Lokalisierung von Phishing-Nachrichten und zur Unterstützung einfacher Malware- und Automatisierungsarbeit; die beobachteten Aktivitäten überschnitten sich mit öffentlich beschriebenen Bedrohungsgruppen und passten nach Einschätzung des Unternehmens zu chinesischen Nachrichtendienstinteressen. OpenAI meldet keine Hinweise auf neuartige Angriffsfähigkeiten, konnte aber auch nicht bestätigen, ob die erkundete Phishing-Automatisierung mit DeepSeek umgesetzt wurde.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 36 / 55 % | 88 / 95 % | – | 99 / 100 % | 50 / 73 % | 38 / 59 % | 17 / 37 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 45 / 87 % | – | 93 / 98 % | 29 / 56 % | 20 / 36 % | 5 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 20 / 81 % | – | 80 / 90 % | 24 / 49 % | 0 / 0 % | 4 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 33 / 54 % | 60 / 92 % | – | 73 / 88 % | 44 / 69 % | 25 / 40 % | 20 / 35 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 38 / 80 % | – | 65 / 78 % | 20 / 39 % | 20 / 38 % | 8 / 19 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 33 / 57 % | 39 / 61 % | – | 52 / 66 % | 48 / 70 % | 27 / 44 % | 16 / 32 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 52 / 67 % | 6 / 12 % | 0 / 0 % | 1 / 3 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 46 / 60 % | 10 / 29 % | 0 / 0 % | 1 / 4 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 8 / 57 % | – | 44 / 62 % | 18 / 41 % | 5 / 13 % | 1 / 7 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 42 / 60 % | 34 / 62 % | 23 / 49 % | 13 / 30 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 41 / 59 % | 5 / 14 % | 0 / 0 % | 1 / 5 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 29 / 57 % | – | 39 / 55 % | 12 / 30 % | 12 / 24 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 15 / 42 % | 18 / 79 % | – | 36 / 78 % | 6 / 13 % | 10 / 24 % | 4 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 31 / 55 % | 28 / 68 % | – | 8 / 49 % | 33 / 60 % | 16 / 37 % | 7 / 21 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 11 / 62 % | – | 33 / 64 % | 15 / 36 % | 21 / 40 % | 5 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 32 / 60 % | 8 / 20 % | 8 / 18 % | 1 / 7 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 0 / 0 % | – | 30 / 53 % | 13 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 30 / 66 % | 13 / 37 % | 0 / 0 % | 5 / 18 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 26 / 58 % | 6 / 20 % | 0 / 0 % | 1 / 6 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 23 / 45 % | 0 / 0 % | 1 / 3 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 40 % | 20 / 40 % | 4 / 15 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 20 / 39 % | 19 / 30 % | 7 / 17 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 33 % | 5 / 10 % | 1 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | – | 11 / 29 % | 11 / 36 % | 0 / 0 % | 2 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 27 % | 6 / 12 % | 2 / 8 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 8 / 18 % | 1 / 7 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 1 / 6 % | 6 / 17 % | 8 / 17 % | 1 / 5 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 2 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 0 / 0 % | 2 / 9 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % | 1 / 6 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 2 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 5 / 16 % | 3 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 1 / 6 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 7 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 4 / 11 % | 0 / 0 % | 1 / 5 % |
