[English](README.md) · [Deutsch](README.de.md)

# Tencent Just Open-Sourced BrowserSkill: The Missing Bridge Between AI Agents and Your Browser

Bericht Q011195 · Quelle medium.com · Datum 2026-09-19 · [Original öffnen](https://medium.com/coding-nexus/tencent-just-open-sourced-browserskill-the-missing-bridge-between-ai-agents-and-your-browser-90333257104c)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt BrowserSkill als lokales, quelloffenes CLI-Werkzeug vor, mit dem KI-Agenten nach erteilter Berechtigung vorübergehend vorhandene Browser-Tabs und deren Anmeldesitzungen nutzen können. Menschliche Bestätigungen bleiben erforderlich; unabhängige Sicherheits- oder Leistungstests enthält der Artikel nicht, und die Eignung hängt von Website und Berechtigungen ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 56 / 71 % | 98 / 100 % | 100 / 100 % | 61 / 79 % | 33 / 54 % | 55 / 71 % | 38 / 71 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 29 / 45 % | 76 / 90 % | 100 / 100 % | 19 / 39 % | 8 / 18 % | 10 / 23 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 9 / 85 % | 86 / 92 % | 7 / 15 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 25 / 38 % | 13 / 53 % | 74 / 85 % | 20 / 40 % | 9 / 20 % | 21 / 37 % | 3 / 11 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 21 / 39 % | 42 / 82 % | 66 / 75 % | 23 / 46 % | 13 / 28 % | 23 / 42 % | 2 / 8 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 8 / 29 % | 46 / 81 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 32 % | 0 / 0 % | 46 / 62 % | 8 / 24 % | 4 / 13 % | 6 / 15 % | 1 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 15 / 37 % | 0 / 0 % | 29 / 40 % | 14 / 29 % | 2 / 6 % | 12 / 21 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 10 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 1 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 4 / 8 % | 0 / 0 % | – |
