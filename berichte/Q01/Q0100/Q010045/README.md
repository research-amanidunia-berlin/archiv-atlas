[English](README.md) · [Deutsch](README.de.md)

# The Full Stack Agentic App Architecture I Use + Skeleton App Available

Report Q010045 · Source medium.com · Date 2025-11-09 · [Open original](https://medium.com/gitconnected/the-full-stack-agentic-app-architecture-i-use-skeleton-app-available-22b974b36b35)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Itsuki stellt ein AWS-Skeleton für agentische Chat-Apps vor: Cognito, S3 und Strands Agents bilden zentrale Teile, während AgentCore Runtime Modellaufrufe und API Gateway mit Lambda die Sitzungsverwaltung übernehmen. Das Next.js-Frontend läuft auf App Runner; der Autor erläutert Bereitstellung und lokalen Betrieb mit CDK. Die Architekturbegründungen gelten für seinen beschriebenen Bedarf und werden im Bericht nicht unabhängig bewertet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 45 / 78 % | 0 / 0 % | 33 / 60 % | 9 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 26 / 82 % | 0 / 0 % | 16 / 35 % | 8 / 24 % | 6 / 17 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 13 / 54 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 7 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 5 / 12 % | 0 / 0 % | 1 / 5 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 5 / 10 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
