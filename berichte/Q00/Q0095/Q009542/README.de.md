[English](README.md) · [Deutsch](README.de.md)

# Sam Altmans Rede vor dem Sicherheitsrat der Vereinten Nationen

Bericht Q009542 · Quelle openai.com · Datum – · [Original öffnen](https://openai.com/index/sam-altman-un-security-council-remarks/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

In seiner Rede vor dem UN-Sicherheitsrat beschreibt Sam Altman KI als Chance, menschliche Fähigkeiten zu erweitern, aber auch als Gefahr für menschliche Kontrolle und eine gerechte Machtverteilung. Er fordert demokratische Mitsprache und internationale Standards für Risikobewertung, Aufsicht und Vorfallmeldungen; die im Bericht genannten Modellleistungen und Sicherheitsbehauptungen werden dort nicht unabhängig belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 58 / 81 % | 99 / 100 % | 100 / 100 % | 83 / 92 % | 82 / 93 % | 79 / 92 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 60 / 82 % | 99 / 100 % | 100 / 100 % | 58 / 81 % | 70 / 85 % | 73 / 88 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 50 / 73 % | 98 / 99 % | 100 / 100 % | 67 / 84 % | 85 / 94 % | 83 / 92 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 36 / 60 % | 97 / 99 % | 99 / 100 % | 57 / 80 % | 60 / 83 % | 70 / 87 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 85 / 93 % | 99 / 100 % | 18 / 49 % | 13 / 44 % | 27 / 62 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 44 / 70 % | 95 / 99 % | 96 / 99 % | 53 / 77 % | 76 / 88 % | 63 / 82 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 37 / 58 % | 92 / 97 % | 95 / 99 % | 61 / 81 % | 67 / 83 % | 70 / 84 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 26 / 51 % | 90 / 96 % | 94 / 99 % | 45 / 72 % | 47 / 73 % | 59 / 76 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 17 / 47 % | 91 / 98 % | 64 / 91 % | 21 / 55 % | 24 / 58 % | 27 / 73 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 58 % | 87 / 97 % | 60 / 88 % | 23 / 53 % | 28 / 63 % | 23 / 60 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 11 / 43 % | 86 / 98 % | 58 / 91 % | 27 / 58 % | 25 / 57 % | 22 / 58 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 30 / 55 % | 59 / 88 % | 82 / 91 % | 44 / 70 % | 57 / 75 % | 58 / 75 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 19 / 53 % | 76 / 95 % | 82 / 92 % | 16 / 38 % | 16 / 39 % | 24 / 59 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 9 / 34 % | 79 / 97 % | 42 / 83 % | 66 / 84 % | 35 / 65 % | 23 / 73 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 16 / 35 % | 61 / 88 % | 79 / 88 % | 23 / 55 % | 48 / 71 % | 25 / 68 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 47 % | 64 / 87 % | 76 / 88 % | 24 / 51 % | 22 / 49 % | 36 / 57 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 34 / 55 % | 76 / 95 % | 14 / 56 % | 44 / 72 % | 53 / 74 % | 47 / 66 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 14 / 43 % | 70 / 94 % | 66 / 94 % | 24 / 58 % | 16 / 52 % | 11 / 62 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 15 / 41 % | 46 / 84 % | 69 / 95 % | 24 / 53 % | 18 / 49 % | 15 / 43 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 12 / 42 % | 68 / 93 % | 25 / 71 % | 14 / 34 % | 11 / 26 % | 16 / 32 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 67 / 97 % | 49 / 79 % | 29 / 60 % | 27 / 57 % | 16 / 57 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 15 / 47 % | 67 / 94 % | 38 / 79 % | 26 / 55 % | 28 / 58 % | 20 / 51 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 19 / 44 % | 54 / 88 % | 65 / 88 % | 31 / 58 % | 15 / 42 % | 17 / 50 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 21 / 48 % | 61 / 88 % | 18 / 48 % | 18 / 53 % | 25 / 59 % | 34 / 67 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 17 / 47 % | 50 / 83 % | 59 / 81 % | 40 / 73 % | 44 / 75 % | 32 / 74 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 18 / 46 % | 50 / 86 % | 0 / 0 % | 16 / 45 % | 14 / 43 % | 24 / 51 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 17 / 43 % | 49 / 81 % | 16 / 57 % | 12 / 31 % | 9 / 25 % | 11 / 40 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 11 / 31 % | 46 / 84 % | 22 / 64 % | 31 / 59 % | 25 / 53 % | 41 / 67 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 35 % | 43 / 94 % | 13 / 61 % | 13 / 37 % | 13 / 41 % | 10 / 42 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 8 / 50 % | 36 / 92 % | 2 / 15 % | 8 / 23 % | 10 / 29 % | 6 / 20 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 11 / 39 % | 31 / 81 % | 12 / 38 % | 9 / 26 % | 6 / 16 % | 11 / 26 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 22 / 91 % | 2 / 27 % | 5 / 11 % | 5 / 14 % | 8 / 16 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 35 % | 21 / 88 % | 11 / 47 % | 9 / 31 % | 7 / 29 % | 8 / 29 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 10 / 28 % | 14 / 65 % | 3 / 19 % | 6 / 18 % | 5 / 19 % | 7 / 19 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 11 / 42 % | 14 / 98 % | 8 / 53 % | 6 / 21 % | 4 / 15 % | 8 / 24 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 13 / 89 % | 3 / 20 % | 5 / 9 % | 0 / 3 % | 7 / 16 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 33 % | 6 / 73 % | 1 / 13 % | 6 / 17 % | 4 / 16 % | 9 / 19 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 5 / 34 % | 1 / 26 % | 11 / 39 % | 6 / 14 % | 4 / 18 % | 7 / 15 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 2 / 7 % | 9 / 15 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 81 % | 0 / 9 % | 5 / 11 % | 1 / 6 % | 8 / 15 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 3 / 55 % | 4 / 26 % | 5 / 13 % | 1 / 5 % | 8 / 15 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 2 / 37 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 7 / 13 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 5 / 45 % | 0 / 0 % | 5 / 13 % | 1 / 7 % | 6 / 13 % | – | – |
