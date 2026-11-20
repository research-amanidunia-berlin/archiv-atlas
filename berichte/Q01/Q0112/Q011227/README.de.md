[English](README.md) · [Deutsch](README.de.md)

# Stop Building AI Agents Like Monoliths: 5 Architecture Tips Every Developer Should Know

Bericht Q011227 · Quelle medium.com · Datum 2026-08-09 · [Original öffnen](https://medium.com/coding-nexus/stop-building-ai-agents-like-monoliths-5-architecture-tips-every-developer-should-know-6a2515517232)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht empfiehlt spezialisierte Agenten, eine vom Modellanbieter unabhängige Schnittstelle, multimodale Fähigkeiten und offene Protokolle wie MCP. Außerdem solle ein Sprachmodell Aktionen vorschlagen, während geprüfter Code sie nach Validierung und Berechtigungsprüfung ausführt; die Vorteile werden anhand einfacher Beispiele erläutert, aber nicht durch Messungen belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 27 / 49 % | 94 / 99 % | 42 / 73 % | 99 / 100 % | 37 / 65 % | 20 / 45 % | 24 / 52 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 31 / 48 % | 80 / 98 % | 11 / 32 % | 98 / 99 % | 34 / 63 % | 24 / 49 % | 11 / 32 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 36 / 93 % | 0 / 0 % | 65 / 84 % | 5 / 11 % | 4 / 12 % | 1 / 5 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 43 / 72 % | 0 / 0 % | 61 / 75 % | 5 / 11 % | 3 / 9 % | 1 / 5 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 14 / 36 % | 0 / 0 % | 59 / 77 % | 5 / 11 % | 5 / 8 % | 0 / 3 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 15 / 40 % | 32 / 80 % | 1 / 6 % | 11 / 41 % | 12 / 34 % | 13 / 36 % | 9 / 27 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 28 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 28 % | 22 / 92 % | 0 / 5 % | 26 / 52 % | 8 / 28 % | 4 / 15 % | 3 / 14 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 21 / 75 % | 0 / 0 % | 6 / 31 % | 5 / 13 % | 3 / 9 % | 2 / 8 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 16 / 35 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 11 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 6 / 12 % | 0 / 3 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 57 % | 0 / 0 % | 0 / 0 % | 4 / 8 % | 2 / 4 % | 0 / 1 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 8 / 32 % | 6 / 33 % | 0 / 1 % | 0 / 4 % | 5 / 11 % | 5 / 9 % | 0 / 2 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 1 / 36 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 5 / 12 % | 1 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 6 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 6 % | 0 / 1 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 4 / 8 % | 0 / 1 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 6 / 35 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 5 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 7 % | 1 / 4 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 5 / 35 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 13 % | 0 / 0 % |
