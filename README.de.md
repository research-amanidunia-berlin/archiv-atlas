[English](README.md) · [Deutsch](README.de.md)

# Archiv-Atlas

Ein Repo für den Fragen-Atlas von [research.amanidunia.berlin](https://research.amanidunia.berlin/de/quellen/): 44 Sammelfragen, 7924 Berichte, bewertet von mehreren Entscheidungsmodellen. Private Arbeitsquelle; eine öffentliche, gefilterte Fassung folgt.

Bewertete Berichte: clef 7924 · Luna 7924 · d3-ultra 4771 · JEV 5667 · amos 7924 · drex 7047 · SubQ 7924. Exportzeit: [STAND.json](STAND.json).

| Ordner | Inhalt |
|---|---|
| [fragen/](fragen/) | je Sammelfrage ein Ordner mit README und `ergebnisse.json`, Teilfragen in `T01/` … |
| [berichte/](berichte/README.de.md) | je Bericht ein Ordner (`Q00/Q0000/Q000001/`), README und `bericht.json` |
| `roh/<modell>/` | ungerundete Verteilungen über die Stufen 0–7 je Sammelfrage |
| `zusammenfassungen/<sprache>/` | eigene Zusammenfassungen je Bericht (tldr, kurz, mittel, ausfuehrlich) |
| `i18n/<sprache>/` | Fragen, Teilfragen und Stufennamen |
| `pruefung/` | Prüfbefunde der Übersetzungen |
| `intern/` | Läufe, Token, Kosten; geteilte Berichte |
| `daten/` | die Eingabedateien der Website |

## Sammelfragen

- [SF-M1](fragen/SF-M1/README.de.md): Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen?
- [SF-M2](fragen/SF-M2/README.de.md): Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise?
- [SF-M3](fragen/SF-M3/README.de.md): Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken?
- [SF-M4](fragen/SF-M4/README.de.md): Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg?
- [SF-M5](fragen/SF-M5/README.de.md): Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen?
- [SF-F1](fragen/SF-F1/README.de.md): Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen?
- [SF-F2](fragen/SF-F2/README.de.md): Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar?
- [SF-F3](fragen/SF-F3/README.de.md): Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik?
- [SF-F4](fragen/SF-F4/README.de.md): Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden?
- [SF-F5](fragen/SF-F5/README.de.md): Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern?
- [SF-P1](fragen/SF-P1/README.de.md): Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen?
- [SF-P2](fragen/SF-P2/README.de.md): Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig?
- [SF-P3](fragen/SF-P3/README.de.md): Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind?
- [SF-P4](fragen/SF-P4/README.de.md): Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen?
- [SF-P5](fragen/SF-P5/README.de.md): Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg?
- [SF-T1](fragen/SF-T1/README.de.md): Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie?
- [SF-T2](fragen/SF-T2/README.de.md): Woran erkennen andere, dass ein Labor wirklich bremst?
- [SF-T3](fragen/SF-T3/README.de.md): Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben?
- [SF-V1](fragen/SF-V1/README.de.md): Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen?
- [SF-V3](fragen/SF-V3/README.de.md): Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist?
- [SF-V4](fragen/SF-V4/README.de.md): Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins?
- [SF-V5](fragen/SF-V5/README.de.md): Was soll heute für das Verhalten und den Betrieb von Modellen gelten?
- [SF-A1](fragen/SF-A1/README.de.md): Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt?
- [SF-A2](fragen/SF-A2/README.de.md): Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen?
- [SF-A3](fragen/SF-A3/README.de.md): Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen?
- [SF-H1](fragen/SF-H1/README.de.md): Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben?
- [SF-H2](fragen/SF-H2/README.de.md): Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet?
- [SF-H3](fragen/SF-H3/README.de.md): Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt?
- [SF-H4](fragen/SF-H4/README.de.md): Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird?
- [SF-H5](fragen/SF-H5/README.de.md): Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil?
- [SF-H6](fragen/SF-H6/README.de.md): Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten?
- [SF-K1](fragen/SF-K1/README.de.md): Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben?
- [SF-K2](fragen/SF-K2/README.de.md): Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen?
- [SF-O1](fragen/SF-O1/README.de.md): Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren?
- [SF-O2](fragen/SF-O2/README.de.md): Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen?
- [SF-O3](fragen/SF-O3/README.de.md): Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde?
- [SF-E1](fragen/SF-E1/README.de.md): Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI?
- [SF-E2](fragen/SF-E2/README.de.md): In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze?
- [SF-E3](fragen/SF-E3/README.de.md): Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon?
- [SF-E4](fragen/SF-E4/README.de.md): Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen?
- [SF-E5](fragen/SF-E5/README.de.md): Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben?
- [SF-W2](fragen/SF-W2/README.de.md): Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus?
- [SF-W3](fragen/SF-W3/README.de.md): Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden?
- [SF-I1](fragen/SF-I1/README.de.md): Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden?
