[English](README.md) · [Deutsch](README.de.md)

# Genie 4: A new generation of world simulation

Report Q000012 · Source deepmind.google · Date 2026-10-27 · [Open original](https://deepmind.google/blog/genie-4-a-new-generation-of-world-simulation/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

DeepMind beschreibt Genie 4 als interaktives Weltmodell, das Szenen in Echtzeit erzeugt und per Text verändern kann, einschließlich Bewegung, Geräuschen und Dialog. Die vorgestellten Einsatzfelder reichen von kreativen Prototypen bis zu Robotik-Simulationen, werden aber als frühe Erprobungen dargestellt. Das Modell ist noch experimentell: Über längere Sitzungen können Details und Objekte driften; auch Physik, Audio, Textdarstellung und räumliche Genauigkeit bleiben laut Bericht ungelöst.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 85 / 98 % | 4 / 7 % | 98 / 99 % | 13 / 35 % | 12 / 23 % | 4 / 14 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 45 / 60 % | 80 / 96 % | 94 / 95 % | 80 / 84 % | 75 / 85 % | 74 / 82 % | 74 / 83 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 21 / 36 % | 72 / 92 % | 11 / 18 % | 93 / 96 % | 24 / 54 % | 27 / 54 % | 12 / 30 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 50 / 90 % | 19 / 31 % | 92 / 95 % | 44 / 68 % | 43 / 65 % | 9 / 27 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 9 / 38 % | 2 / 7 % | 87 / 91 % | 11 / 36 % | 13 / 33 % | 4 / 14 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 6 / 11 % | 87 / 91 % | 13 / 36 % | 14 / 37 % | 7 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 29 / 61 % | 0 / 4 % | 83 / 93 % | 7 / 22 % | 5 / 11 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 25 / 74 % | 5 / 12 % | 75 / 88 % | 14 / 37 % | 10 / 20 % | 5 / 15 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 54 / 86 % | 5 / 11 % | 74 / 87 % | 18 / 42 % | 9 / 24 % | 3 / 10 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 57 / 87 % | 2 / 6 % | 68 / 82 % | 10 / 27 % | 7 / 20 % | 1 / 8 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 41 % | 58 / 95 % | 0 / 5 % | 31 / 51 % | 8 / 24 % | 5 / 12 % | 1 / 7 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 27 / 72 % | 2 / 11 % | 58 / 77 % | 18 / 38 % | 9 / 20 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 12 / 82 % | 1 / 6 % | 49 / 70 % | 11 / 37 % | 7 / 24 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 48 / 72 % | 8 / 21 % | 3 / 8 % | 2 / 7 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 45 / 50 % | 18 / 43 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 22 / 51 % | 0 / 0 % | 35 / 47 % | 7 / 17 % | 4 / 11 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 39 % | 0 / 0 % | 30 / 46 % | 6 / 16 % | 3 / 9 % | 1 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 23 / 80 % | 0 / 2 % | 14 / 40 % | 9 / 28 % | 6 / 24 % | 1 / 7 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 23 / 65 % | 1 / 5 % | 3 / 16 % | 12 / 31 % | 9 / 24 % | 4 / 15 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 38 % | 5 / 15 % | 3 / 9 % | 1 / 6 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 15 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 2 / 5 % | 10 / 27 % | 11 / 31 % | 8 / 22 % | 3 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 32 % | 0 / 3 % | 8 / 23 % | 6 / 19 % | 3 / 9 % | 1 / 7 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 7 / 15 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 8 / 24 % | 2 / 6 % | 1 / 6 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 4 / 13 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 4 / 9 % | 0 / 3 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 6 / 16 % | 5 / 13 % | 1 / 6 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 3 / 8 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 5 / 11 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 4 / 9 % | 1 / 7 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 6 % | 1 / 3 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 1 % |
