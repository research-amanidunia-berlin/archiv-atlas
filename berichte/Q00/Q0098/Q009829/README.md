[English](README.md) · [Deutsch](README.de.md)

# Swift: When ExtensionContext.Open Does NOT Open My App! + Solution!

Report Q009829 · Source medium.com · Date 2026-04-07 · [Open original](https://medium.com/@itsuki.enjoy/swift-when-extensioncontext-open-does-not-open-my-app-solution-eaf59ab552c2)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor beschreibt, dass `extensionContext?.open(url)` seine App aus einer iOS-Tastaturerweiterung nicht öffnet, obwohl das URL-Schema aus Safari funktioniert. Er berichtet von Erfolg mit `EnvironmentValues().openURL(url)`, belegt dies aber nur anhand seines Einzelfalls und nennt keine Versionen oder unabhängigen Tests.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
