[English](README.md) · [Deutsch](README.de.md)

# When AI Fails: Building Fault-Tolerant AI Systems

Bericht Q000214 · Quelle computer.org · Datum 2026-10-30 · [Original öffnen](https://www.computer.org/publications/tech-news/trends/fault-tolerance-for-ai)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel empfiehlt, KI als störungsanfällige Abhängigkeit zu behandeln und neben technischen Fehlern auch falsche, aber plausibel wirkende Antworten abzusichern. Dafür nennt er Prüfungen, begrenzte Zeitbudgets und Wiederholungen, getrennte Ressourcen sowie vorab festgelegte Ausweichpfade bis hin zur menschlichen Prüfung oder zum sicheren Anhalten. Die Empfehlungen sind nicht durch quantitative Versuchsergebnisse im Text belegt, und die passende Ausfallstrategie hängt vom jeweiligen Einsatzfall ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 45 / 62 % | 92 / 98 % | 100 / 100 % | 66 / 82 % | 42 / 64 % | 51 / 73 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 72 / 86 % | 100 / 100 % | 100 / 100 % | 88 / 94 % | 89 / 95 % | 86 / 91 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 26 / 52 % | 94 / 99 % | 98 / 99 % | 60 / 80 % | 57 / 76 % | 61 / 78 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 96 / 99 % | 95 / 99 % | 58 / 78 % | 22 / 42 % | 27 / 45 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 55 / 93 % | 96 / 98 % | 5 / 12 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 81 / 95 % | 82 / 89 % | 7 / 21 % | 1 / 6 % | 7 / 16 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 28 / 48 % | 73 / 99 % | 39 / 82 % | 41 / 67 % | 13 / 25 % | 34 / 52 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 28 / 71 % | 69 / 87 % | 12 / 33 % | 3 / 10 % | 7 / 15 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 13 / 34 % | 60 / 88 % | 66 / 79 % | 33 / 55 % | 17 / 36 % | 28 / 52 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 52 / 85 % | 14 / 31 % | 14 / 43 % | 2 / 8 % | 10 / 22 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 20 / 85 % | 50 / 75 % | 11 / 39 % | 4 / 12 % | 16 / 39 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 31 / 63 % | 2 / 9 % | 6 / 19 % | 1 / 6 % | 8 / 15 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 19 / 60 % | 0 / 0 % | 25 / 54 % | 8 / 21 % | 28 / 50 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 24 / 45 % | 21 / 67 % | 0 / 0 % | 9 / 31 % | 9 / 19 % | 15 / 32 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 24 / 86 % | 0 / 0 % | 6 / 16 % | 0 / 1 % | 5 / 10 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 15 / 79 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 4 / 7 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 13 / 82 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 11 / 59 % | 0 / 0 % | 8 / 22 % | 1 / 4 % | 5 / 9 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 10 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 5 / 8 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 9 / 44 % | 0 / 0 % | 9 / 19 % | 2 / 8 % | 6 / 12 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 3 / 63 % | 0 / 0 % | 9 / 31 % | 0 / 2 % | 8 / 17 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 5 % | 6 / 13 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 8 / 46 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 4 / 7 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 46 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 7 / 13 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 6 / 13 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 3 / 52 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 4 / 7 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 4 / 40 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 2 / 44 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 1 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | – | – |
