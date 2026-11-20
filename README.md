[English](README.md) · [Deutsch](README.de.md)

# Archive atlas

One repository for the question atlas of [research.amanidunia.berlin](https://research.amanidunia.berlin/de/quellen/): 44 collected questions, 7924 reports, rated by several decision models. Private working source; a public, filtered edition follows.

Rated reports: clef 7924 · Luna 7924 · d3-ultra 4771 · JEV 5667 · amos 7924 · drex 5685. Export 2026-11-20 03:17.

| Folder | Content |
|---|---|
| [fragen/](fragen/) | one folder per collected question with README and `ergebnisse.json`, subquestions in `T01/` … |
| [berichte/](berichte/README.md) | one folder per report (`Q00/Q0000/Q000001/`), README and `bericht.json` |
| `roh/<model>/` | unrounded distributions over levels 0–7 per collected question |
| `zusammenfassungen/<lang>/` | own summaries per report (tldr, kurz, mittel, ausfuehrlich) |
| `i18n/<lang>/` | questions, subquestions and level names |
| `pruefung/` | review findings of translations |
| `intern/` | runs, tokens, costs; split reports |
| `daten/` | the website's input files |

## Collected questions

- [SF-M1](fragen/SF-M1/README.md): When is an AI incident serious enough that states must report it to each other?
- [SF-M2](fragen/SF-M2/README.md): How must a reporting channel between states be built so that it works reliably, including in a crisis?
- [SF-M3](fragen/SF-M3/README.md): How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it?
- [SF-M4](fragen/SF-M4/README.md): How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders?
- [SF-M5](fragen/SF-M5/README.md): What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders?
- [SF-F1](fragen/SF-F1/README.md): How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side?
- [SF-F2](fragen/SF-F2/README.md): When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable?
- [SF-F3](fragen/SF-F3/README.md): Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology?
- [SF-F4](fragen/SF-F4/README.md): Which models, developers and deployments do testing rules apply to, and when must testing be repeated?
- [SF-F5](fragen/SF-F5/README.md): How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence?
- [SF-P1](fragen/SF-P1/README.md): Under what conditions do states and labs verify each other: with what access, what data and what public results?
- [SF-P2](fragen/SF-P2/README.md): How do evaluators embedded in a lab stay truly independent?
- [SF-P3](fragen/SF-P3/README.md): How can one tell that a lab monitors itself honestly and that its tests are valid?
- [SF-P4](fragen/SF-P4/README.md): How can the scale of training runs be verified without revealing model details?
- [SF-P5](fragen/SF-P5/README.md): How do you verify that commitments between states are kept, including over years and changes of government?
- [SF-T1](fragen/SF-T1/README.md): Which measurable thresholds should trigger a pause, and who checks them?
- [SF-T2](fragen/SF-T2/README.md): How can others tell that a lab has really slowed down?
- [SF-T3](fragen/SF-T3/README.md): How can one tell that AI is starting to drive its own further development, and who may allow it?
- [SF-V1](fragen/SF-V1/README.md): What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough?
- [SF-V3](fragen/SF-V3/README.md): Do a model's values hold when no one is watching or the situation is new?
- [SF-V4](fragen/SF-V4/README.md): What kind of entity is a model, and what follows for how we treat it and for the value of being human?
- [SF-V5](fragen/SF-V5/README.md): What should apply today to how models behave and how they are run?
- [SF-A1](fragen/SF-A1/README.md): Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task?
- [SF-A2](fragen/SF-A2/README.md): Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it?
- [SF-A3](fragen/SF-A3/README.md): Which dangers arise when many AI systems interact or share the same infrastructure?
- [SF-H1](fragen/SF-H1/README.md): Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin?
- [SF-H2](fragen/SF-H2/README.md): What may be released openly, and who is responsible when an open model causes harm elsewhere?
- [SF-H3](fragen/SF-H3/README.md): How can one trace what a model was built from and what it contains?
- [SF-H4](fragen/SF-H4/README.md): What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired?
- [SF-H5](fragen/SF-H5/README.md): When are chip and export controls a security measure, and when a permanent advantage?
- [SF-H6](fragen/SF-H6/README.md): What evidence settles accusations of espionage and data leaks between states?
- [SF-K1](fragen/SF-K1/README.md): How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans?
- [SF-K2](fragen/SF-K2/README.md): How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes?
- [SF-O1](fragen/SF-O1/README.md): How can staff raise safety concerns without risking everything?
- [SF-O2](fragen/SF-O2/README.md): What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions?
- [SF-O3](fragen/SF-O3/README.md): Which text governs, and how do you prove a document has not been altered?
- [SF-E1](fragen/SF-E1/README.md): What real say do other states, smaller labs, universities and civil society get in the rules for AI?
- [SF-E2](fragen/SF-E2/README.md): In what framework should states govern AI, and where is a common floor?
- [SF-E3](fragen/SF-E3/README.md): Which bodies in a state are responsible for AI safety and testing, and which of them already exist?
- [SF-E4](fragen/SF-E4/README.md): How does AI remain a shared asset rather than deepening dependence and market power?
- [SF-E5](fragen/SF-E5/README.md): What say do the people who live with AI have over its pace and limits, and which decisions must stay with them?
- [SF-W2](fragen/SF-W2/README.md): How do competition law and public procurement bear on AI safety?
- [SF-W3](fragen/SF-W3/README.md): How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds?
- [SF-I1](fragen/SF-I1/README.md): How can AI-generated content and AI-generated influence be detected without curbing free expression?
