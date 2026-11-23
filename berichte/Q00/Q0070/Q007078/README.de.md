[English](README.md) · [Deutsch](README.de.md)

# Unlocking the Codex harness: how we built the App Server

Bericht Q007078 · Quelle openai.com · Datum 2026-02-04 · [Original öffnen](https://openai.com/index/unlocking-the-codex-harness/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt den Codex App Server als rückwärtskompatible JSON-RPC-Schnittstelle, die unterschiedliche Codex-Clients mit demselben Agenten-Harness verbindet und Gesprächsverläufe, gestreamte Ereignisse sowie Freigaben unterstützt. OpenAI empfiehlt ihn für Integrationen mit vollem Funktionsumfang, nennt aber den Aufwand eigener Client-Anbindungen; unabhängige Vergleichsmessungen enthält der Beitrag nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 38 / 57 % | 96 / 100 % | 95 / 99 % | 59 / 77 % | 11 / 31 % | 45 / 63 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 56 / 64 % | 11 / 23 % | 0 / 0 % | 8 / 17 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 40 % | 29 / 92 % | 47 / 70 % | 24 / 48 % | 0 / 0 % | 24 / 43 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 26 / 47 % | 46 / 94 % | 34 / 51 % | 46 / 68 % | 10 / 29 % | 46 / 64 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 8 / 88 % | 36 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 34 % | 34 / 68 % | 0 / 0 % | 8 / 22 % | 0 / 0 % | 8 / 16 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 25 % | 8 / 81 % | 27 / 51 % | 8 / 25 % | 2 / 10 % | 5 / 14 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 20 / 36 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 9 / 22 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 9 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 5 / 11 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 3 / 42 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 2 / 36 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
