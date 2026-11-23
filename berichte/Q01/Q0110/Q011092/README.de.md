[English](README.md) · [Deutsch](README.de.md)

# AI Coding Agents in the SDLC: The Hype, the Wins, and the Hard Truths After a Year in Production

Bericht Q011092 · Quelle medium.com · Datum 2026-05-06 · [Original öffnen](https://medium.com/gitconnected/ai-coding-agents-in-the-sdlc-the-hype-the-wins-and-the-hard-truths-after-a-year-in-production-6d9bb7577fcb)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Quelltext enthält nur einen Auszug; der restliche Artikel ist durch eine Medium-Mitgliederschranke nicht zugänglich. Der Autor berichtet von realen Produktivitätsgewinnen durch KI-Coding-Agenten, betont aber auch nicht näher beschriebene Fehler und sieht den Wandel darin, dass KI inzwischen ganze Aufgaben statt einzelner Autovervollständigungen unterstützt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 21 / 37 % | 8 / 53 % | 27 / 57 % | 11 / 30 % | 1 / 7 % | 7 / 24 % | 1 / 6 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 24 / 45 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 18 / 37 % | 15 / 54 % | 2 / 33 % | 9 / 24 % | 1 / 8 % | 7 / 18 % | 0 / 7 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 16 / 39 % | 1 / 11 % | 5 / 12 % | 0 / 2 % | 3 / 7 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 15 / 31 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 5 / 9 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 35 % | 6 / 51 % | 2 / 17 % | 6 / 19 % | 0 / 3 % | 7 / 16 % | 0 / 2 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 7 / 31 % | 14 / 60 % | 5 / 13 % | 0 / 3 % | 2 / 9 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 31 % | 5 / 31 % | 0 / 8 % | 6 / 17 % | 0 / 6 % | 4 / 14 % | 0 / 3 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 24 % | 3 / 28 % | 2 / 16 % | 5 / 15 % | 0 / 6 % | 4 / 11 % | 0 / 3 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 2 % | 3 / 8 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 2 / 43 % | 6 / 32 % | 5 / 12 % | 0 / 3 % | 3 / 10 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 4 / 46 % | 1 / 20 % | 5 / 14 % | 0 / 2 % | 4 / 10 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 4 / 9 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 3 / 7 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 2 / 6 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 7 % | 0 / 1 % | 4 / 11 % | 0 / 0 % | – |
