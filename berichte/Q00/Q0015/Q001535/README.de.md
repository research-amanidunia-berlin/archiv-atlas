[English](README.md) · [Deutsch](README.de.md)

# NIST RFI: Security Considerations for AI Agents

Bericht Q001535 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/governance/nist-rfi-security-considerations-for-ai-agents)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Apollo Research empfiehlt dem NIST, Forschung zu täuschendem Verhalten und Fehlanpassung, KI-gestützter Überwachung sowie den Risiken von Agenten in Hochrisikobereichen zu beschleunigen. Der bereitgestellte Text ist nur ein Auszug; er nennt keine konkreten Untersuchungsmethoden oder empirischen Ergebnisse und endet mit einer offenen Überschrift.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 21 / 50 % | 56 / 88 % | 6 / 14 % | – | 24 / 53 % | 17 / 41 % | 45 / 63 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 17 / 50 % | 24 / 79 % | 12 / 45 % | – | 19 / 47 % | 21 / 52 % | 51 / 77 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 54 % | 50 / 98 % | 13 / 48 % | – | 34 / 64 % | 20 / 50 % | 42 / 70 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 33 / 56 % | 48 / 88 % | 21 / 37 % | – | 28 / 57 % | 25 / 44 % | 33 / 52 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 20 / 55 % | 46 / 95 % | 24 / 61 % | – | 38 / 67 % | 17 / 48 % | 38 / 66 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 28 / 54 % | 41 / 87 % | 12 / 39 % | – | 28 / 61 % | 27 / 54 % | 43 / 70 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 51 % | 8 / 55 % | 3 / 15 % | – | 34 / 65 % | 11 / 33 % | 35 / 62 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 16 / 37 % | 34 / 71 % | 0 / 4 % | – | 6 / 14 % | 3 / 11 % | 7 / 18 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 14 / 41 % | 33 / 73 % | 1 / 5 % | – | 12 / 29 % | 5 / 14 % | 8 / 19 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 17 / 42 % | 19 / 64 % | 7 / 33 % | – | 27 / 55 % | 16 / 39 % | 31 / 58 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 21 / 52 % | 20 / 61 % | 6 / 21 % | – | 29 / 57 % | 15 / 40 % | 21 / 44 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 41 % | 27 / 80 % | 2 / 12 % | – | 16 / 45 % | 6 / 26 % | 16 / 49 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 27 / 53 % | 8 / 92 % | 3 / 16 % | – | 24 / 55 % | 10 / 31 % | 15 / 47 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 15 / 45 % | 20 / 47 % | 8 / 24 % | – | 19 / 41 % | 12 / 27 % | 24 / 43 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 9 / 41 % | 22 / 59 % | 2 / 8 % | – | 7 / 19 % | 5 / 14 % | 8 / 19 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 43 % | 8 / 75 % | 3 / 20 % | – | 19 / 47 % | 8 / 29 % | 19 / 48 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 13 / 34 % | 2 / 35 % | 1 / 8 % | – | 18 / 44 % | 7 / 21 % | 10 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 18 / 50 % | 1 / 5 % | – | 8 / 18 % | 2 / 8 % | 6 / 18 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 16 / 39 % | 13 / 70 % | 2 / 10 % | – | 14 / 31 % | 4 / 11 % | 13 / 30 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 16 / 47 % | 0 / 0 % | 4 / 20 % | – | 15 / 42 % | 6 / 21 % | 15 / 43 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 14 / 37 % | 0 / 0 % | 0 / 3 % | – | 10 / 26 % | 2 / 9 % | 6 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 13 / 37 % | 0 / 0 % | 1 / 6 % | – | 7 / 18 % | 2 / 10 % | 9 / 24 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 42 % | 0 / 0 % | 0 / 2 % | – | 5 / 12 % | 2 / 9 % | 8 / 16 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 8 / 37 % | 9 / 64 % | 2 / 12 % | – | 11 / 30 % | 4 / 15 % | 7 / 19 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 41 % | 6 / 78 % | 2 / 14 % | – | 11 / 35 % | 5 / 25 % | 10 / 33 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 11 / 22 % | 0 / 2 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 10 / 25 % | 0 / 0 % | 0 / 3 % | – | 8 / 21 % | 1 / 6 % | 6 / 20 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 3 / 47 % | 0 / 3 % | – | 8 / 20 % | 1 / 6 % | 6 / 17 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 3 % | – | 8 / 16 % | 1 / 7 % | 5 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 7 / 27 % | 3 / 61 % | 0 / 2 % | – | 6 / 16 % | 1 / 8 % | 6 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | 1 / 5 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 2 % | 6 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 1 / 5 % | 4 / 8 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 5 / 10 % | 1 / 3 % | 6 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 10 % | 0 / 2 % | 5 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 5 / 23 % | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 2 / 9 % | 5 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 5 / 28 % | 0 / 0 % | 0 / 0 % | – | 6 / 11 % | 1 / 5 % | 4 / 8 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 3 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 3 / 9 % | 5 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 5 % | 5 / 13 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 4 % | 5 / 12 % |
