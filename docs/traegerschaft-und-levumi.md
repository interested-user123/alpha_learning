# Trägerschaft, Community-Modell und Levumi

Stand: Oktober 2026. Ergänzt `bestandsaufnahme.md`.

---

## Teil 1: Was man über Levumi wissen sollte

### Steckbrief

| | |
|---|---|
| **Name** | Levumi (Lern-Verlaufs-Monitoring) |
| **Gegründet** | 2015 von Markus Gebhardt (Sonderpädagogik) und Andreas Mühling (Informatikdidaktik) |
| **Kernteam** | Gebhardt (zuletzt LMU München, vorher Regensburg und TU Dortmund), Mühling (Uni Kiel / IPN), Kirsten Diehl (Europa-Universität Flensburg); Susanne Giering beantwortet 2025 Praxisfragen; Jana Jungjohann war lange Mitautorin (2026 bei der DKJS) |
| **Betrieb** | Server der Christian-Albrechts-Universität Kiel, nichtkommerzielles Wissenschaftsteam |
| **Kosten** | kostenlos für Lehrkräfte, Schulen und Forschung |
| **Quellcode** | github.com/muehling/levumi, öffentlich; Lizenz im Repo nicht eindeutig belegt, vor Nutzung klären |
| **Inhalte** | Fördermaterial als OER, aber unter CC BY-NC-SA 3.0 (nicht-kommerziell), nicht CC BY-SA |
| **Fächer** | Lesen, Rechtschreiben, Mathematik (Zahlen und Operationen), Verhalten und Empfinden |
| **Zielgruppe** | Lehrkräfte an Grund-, Förder- und inklusiven Schulen; Kinder sind Testpersonen, nicht Nutzer |

### Wie es funktioniert

Levumi setzt das Konzept der **Lernverlaufsdiagnostik** um (englisch Curriculum-Based Measurement, seit den 1970ern in den USA). Die Lehrkraft lässt ein Kind regelmäßig, etwa wöchentlich, einen kurzen Test machen, immer zum gleichen Konstrukt (zum Beispiel Leseflüssigkeit). Die Plattform zeichnet die Ergebnisse als Verlaufskurve. Die Lehrkraft sieht, ob die Förderung wirkt, und passt sie an. Die Tests sind an Entwicklungsmodelle angelehnt, deshalb lassen sich aus den Ergebnissen Förderideen ableiten, die Levumi als Material mitliefert.

Wichtig für Alpha: **Levumi misst, Levumi übt nicht.** Es ist ein Instrument für die Lehrkraft, kein Lernprogramm für das Kind. Die Lehrkraft führt die Tests durch, verwaltet die Konten und liest die Kurven. Es gibt keine kindgerechte Oberfläche, keine Gamification, keine tägliche Routine.

### Nutzung in Zahlen (Blog der Uni Kiel, Mai 2026)

- 33.288 Messungen zwischen September 2019 und Juli 2024, nur aus Lehrkraftkonten
- Aktive Lehrkräfte: unter 50 im Schuljahr 2019/20, knapp 400 im Schuljahr 2023/24
- Getestete Kinder: von rund 200 auf über 2.000
- 75 Prozent der Lehrkräfte messen höchstens 12 Kinder pro Jahr, die Hälfte vier oder weniger
- Über 4.000 registrierte Konten insgesamt (Lehrkräfte, Forschende, Private)

Einordnung: Das ist für ein Universitätsprojekt beachtlich, aber klein im Vergleich zu ANTON. Die meisten Lehrkräfte nutzen es punktuell für einzelne Förderkinder, nicht für die ganze Klasse. Das passt zu Alphas Zielgruppe.

### Finanzierung und Stabilität

Das ist der kritische Punkt. Levumi hat **keine dauerhafte Finanzierung**. Ein BMBF-Antrag von 2016 wurde abgelehnt. Die Vergleichsstudie von Blumenthal, Gebhardt, Förster und Souvignier (2022) nennt als Hindernis ausdrücklich das Wissenschaftszeitvertragsgesetz: Mitarbeitende haben befristete Stellen, deshalb konnten bis dahin keine Wirksamkeitsstudien durchgeführt werden. Die Plattform lebt von Lehrstuhlressourcen, Qualifikationsarbeiten und Projektförderung.

Ein solches Projekt war **DaF-L** (Digitale alltagsintegrierte Förderdiagnostik Lesen), BMBF-gefördert, September 2021 bis August 2024, Verbund aus Flensburg (Koordination), Leipzig, München und Kiel. Ergebnis: das adaptive Lesescreening **LES-IN-CAT** und das Förderpaket **LesePfad** für inklusive dritte Klassen, beides als OER auf Levumi. Das ist inhaltlich das, was Alpha am nächsten kommt: ein adaptiver Test plus passendes Fördermaterial, wissenschaftlich geprüft, offen.

Die Lehre für Alpha: Eine Universität als alleiniger Träger ist kein sicherer Hafen. Sie gibt Glaubwürdigkeit und Forschungsgeld, aber keine Kontinuität.

### Was das Team selbst als Hindernis sieht (Interview November 2025)

Nicht mehr die Hardware, sondern zwei Dinge: die IT-Vernetzung an Schulen und ein fehlendes Verständnis für pädagogische Diagnostik bei Lehrkräften. Beides sind Argumente für Alpha: Eine App, die ohne Netz läuft und die Diagnostik in eine tägliche Routine einbaut, statt sie als Extra-Aufgabe zu erfordern, adressiert genau diese Hürden.

### Datenschutz

Levumi läuft zentral auf Uniservern mit Lehrkraftkonten. Das Team hat 2019 einen Blogbeitrag zu Datenschutz und IT-Sicherheit veröffentlicht und arbeitet nach eigener Aussage mit Ministerien zusammen. Für Schulen bedeutet es trotzdem: externer Dienst, Auftragsverarbeitung, Pseudonymisierung in Verantwortung der Schule. Alpha mit lokalen Daten wäre hier einfacher. Das ist ein Angebot an Levumi, kein Widerspruch.

### Wie Alpha und Levumi zusammenpassen

| Levumi | Alpha |
|---|---|
| Misst wöchentlich, für die Lehrkraft | Übt täglich, für das Kind |
| Lehrkraft führt durch | Kind arbeitet selbstständig |
| Entwicklungsmodelle für Lesen, Rechtschreiben, Mathe | braucht genau diese Modelle als Stufenlogik |
| Fördermaterial als PDF/OER | könnte dieses Material als Übungen ausliefern |
| Zentrale Server | lokal, Export auf Wunsch |

Drei konkrete Andockpunkte:

1. **Entwicklungsmodelle übernehmen.** Alphas Stufen für Lesen sollten denselben Konstrukten folgen wie Levumis Tests (etwa Silben lesen, Wörter lesen, Sätze sinnentnehmend lesen). Dann sind Alphas interne Messungen mit Levumis Kurven vergleichbar.
2. **Export im Levumi-Format.** Wenn Alpha seine Fortschrittsdaten so exportiert, dass eine Lehrkraft sie in Levumi einspielen kann, wird Alpha zur Datenquelle für ein etabliertes Instrument. Das ist das stärkste Kooperationsargument.
3. **LesePfad und LES-IN-CAT als erste Inhalte.** Das Material existiert, ist geprüft und offen. Lizenzfrage (NC) klären, dann als Pilotinhalt für Klasse 3 Lesen nutzen.

### Wen ansprechen und wie

- **Andreas Mühling (Kiel)** verantwortet die Technik und das GitHub-Repo. Für Fragen zu Code, Lizenz, Schnittstellen.
- **Markus Gebhardt (LMU)** verantwortet Testentwicklung und Forschung. Für die Frage, ob Alpha als Übungsfrontend für Levumi-Konstrukte in Frage kommt.
- **Kirsten Diehl (Flensburg)** koordinierte DaF-L. Für LesePfad und Inklusion.

Empfohlener Einstieg: eine kurze Mail mit dem Einseiter (Vision), dem Venn-Diagramm und einer klaren Frage: "Wäre eine Kinder-App, die lokal übt und Ergebnisse in Levumi-kompatiblem Format exportiert, für Sie interessant, und unter welchen Bedingungen würden Sie Entwicklungsmodelle und Material dafür freigeben?" Universitätsprojekte freuen sich über Praxispartner und über Qualifikationsarbeiten, die ihr Material nutzen. Als Pädagogikstudent kann Alpha selbst Gegenstand einer Abschlussarbeit sein, möglicherweise am Lehrstuhl eines der drei.

Risiken: Das Team ist klein und befristet finanziert, Antworten können dauern. Die Lizenz des Codes ist unklar. Das Servermodell ist nicht Alphas Modell, deshalb Zusammenarbeit über Formate und Inhalte, nicht über gemeinsamen Code.

---

## Teil 2: Ein Community-Modell für die Trägerschaft

### Das Problem in einem Satz

Alle offenen Vorbilder haben einen institutionellen Anker: GCompris in der KDE-Community, Serlo im eigenen Verein mit Stiftungsgeld, Levumi an Lehrstühlen, Kolibri in einer US-Nonprofit, dBildungscloud bei drei Ländern. Keines lebt von "Community" allein. Community trägt die Arbeit, aber irgendjemand muss Server, Lizenzen, Verträge und Kontinuität verantworten.

### Grundsatz: Erst Menschen, dann Rechtsform

Ein Verein mit zwei Mitgliedern ist Papier. Die Rechtsform sollte erst kommen, wenn es mindestens fünf aktive Personen gibt, die seit einem halben Jahr mitarbeiten. Bis dahin reicht ein öffentliches Repo mit klaren Regeln und ein Ankerpunkt an einer Hochschule.

### Vier Phasen

**Phase 0: Kern bilden (jetzt bis erstes lauffähiges Thema)**
- Träger: niemand formal. Das Repo ist die Organisation.
- Anker: eine Hochschule über eine Abschlussarbeit, ein Seminar oder einen Lehrstuhl (Kandidaten: die Levumi-Lehrstühle, oder die eigene Hochschule).
- Ziel: 3 bis 5 Personen, davon mindestens eine mit Sonderpädagogik, eine mit Softwareentwicklung, eine Praxislehrkraft.
- Regeln schon jetzt schriftlich: Lizenz, Entscheidungsweg, Review-Pflicht, Verhaltenskodex. Nichts, das nur eine Person kann.

**Phase 1: Erste Förderung (6 bis 12 Monate)**
- Prototype Fund (BMBF, über Open Knowledge Foundation Deutschland): fördert Einzelpersonen und kleine Teams für Open-Source-Software, bis 158.000 € für zehn Monate (Stand 2024, aktuelle Runde prüfen). Passt genau auf Phase 1, weil kein Verein nötig ist.
- Parallel: Stiftungen mit Bildungsschwerpunkt, die Projekte ohne eigene Rechtsform über einen Partner fördern (Hans Sauer Stiftung hat Serlo gefördert; Deutsche Kinder- und Jugendstiftung, Wübben Stiftung Bildung, Deutsche Telekom Stiftung sind im Grundschulbereich aktiv).
- Ziel: Prototyp an zwei oder drei Pilotschulen.

**Phase 2: Rechtsform und Fachbeirat (ab etwa fünf aktiven Personen)**
- Gemeinnütziger Verein. Günstig, allen Schulträgern vertraut, kann Spenden und Fördermittel annehmen, kann Verträge mit Ländern schließen.
- Alternative, falls ein Verein zu viel Verwaltung ist: Andocken an einen bestehenden Verein als Projekt (Serlo Education e.V., Open Knowledge Foundation, KDE e.V. für Infrastruktur). Das nennt sich "fiscal hosting" und erspart die eigene Buchhaltung.
- Fachbeirat: je eine Person aus Sonderpädagogik-Forschung (idealerweise Levumi), aus einem Landesinstitut, aus der Praxis, aus Schul-IT. Trifft sich zweimal im Jahr, entscheidet über den Kanon, nicht über den Code.

**Phase 3: Dauerbetrieb (wenn Länder einsteigen)**
- Länder zahlen nicht für Lizenzen, sondern für Pflege: ein Wartungsvertrag mit dem Verein, der Updates, Sicherheitsprüfung, Barrierefreiheit und Support garantiert. Das ist ein Bruchteil dessen, was eine Landeslizenz kostet, weil kein Server und keine Konten zu betreiben sind.
- Ein Land, das einsteigt, bekommt einen Sitz im Beirat.
- Die Inhalte bleiben OER, der Code bleibt offen; kein Land kann das Projekt übernehmen oder abschalten.

### Rollen (ab Phase 0 schriftlich)

| Rolle | Aufgabe | Wer entscheidet was |
|---|---|---|
| **Maintainer Pädagogik** | Fördermodell, Stufenlogik, Kanon | Was in den Kanon kommt |
| **Maintainer Technik** | Architektur, Releases, Sicherheit | Was in den Code kommt |
| **Reviewer Inhalte** | prüfen Übungsreihen fachlich | Freigabe mit Vier-Augen-Prinzip, mindestens eine Person mit sonderpädagogischem Hintergrund |
| **Pilotschulen** | testen, melden zurück, schreiben Inhalte | Vetorecht bei Bedienbarkeit |
| **Beitragende** | Inhalte, Übersetzungen, Audio, Code | keine; ihre Beiträge gehen durch Review |

### Entscheidungsregeln

- Jede Entscheidung mit Tragweite wird als kurzes Dokument im Repo festgehalten (Architecture Decision Record, eine Seite: Frage, Optionen, Entscheidung, Begründung). So versteht auch jemand, der in zwei Jahren dazukommt, warum etwas so ist.
- Konsent statt Konsens: Ein Vorschlag gilt, wenn niemand einen begründeten schwerwiegenden Einwand hat. Nicht, wenn alle begeistert sind.
- Inhalte: zwei Freigaben, eine davon sonderpädagogisch. Code: eine Freigabe plus automatische Prüfung.
- Kein Alleingang bei: Lizenzänderung, Datenmodell, Aufnahme eines Partners mit Geld.

### Was Pädagogen zum Mitmachen braucht

Nicht GitHub. Die meisten Lehrkräfte werden nie ein Repo öffnen. Drei Einstiege, von leicht zu schwer:

1. **Rückmeldung aus dem Unterricht** über ein einfaches Formular oder eine Mailadresse. Niedrigste Hürde, wertvollste Daten.
2. **Inhalte schreiben** in einer Vorlage (Tabelle oder Formular), die jemand aus dem Kernteam in das technische Format überträgt. Später ein Web-Editor, der das Format direkt erzeugt.
3. **Reviewer werden** nach einer kurzen Einarbeitung. Das sind die Leute, die aus Community eine Qualitätssicherung machen.

Dazu ein fester Rhythmus: eine offene Online-Werkstatt alle vier bis sechs Wochen, in der Inhalte besprochen und freigegeben werden. Regelmäßigkeit bindet mehr als jede Plattform.

### Lizenzentscheidung (jetzt treffen)

- **Code: AGPL-3.0.** Verhindert, dass ein Anbieter Alpha nimmt, einen Server davor setzt und als Dienst verkauft, ohne den Code zu teilen. GCompris hat dieselbe Wahl getroffen.
- **Inhalte: CC BY-SA 4.0.** Offen, weitergabepflichtig, aber ohne das NC-Problem von Levumi. Nicht-kommerziell klingt gut, verhindert in der Praxis aber, dass ein Verlag oder ein Land Material drucken darf, und erzeugt endlose Abgrenzungsfragen.
- Beitragende unterschreiben keine Verträge, aber jede Einreichung enthält den Satz, dass der Beitrag unter dieser Lizenz steht.

### Die eine Regel, die alles andere trägt

**Nichts darf von einer Person abhängen.** Kein Zugang, kein Wissen, kein Server, kein Konto. Das ist die Lehre aus allen Projekten, die still gestorben sind, und aus Levumi, das trotz 400 aktiver Lehrkräfte an befristeten Stellen hängt.

---

## Quellen

- Levumi Team und Geschichte: https://www.levumi-blog.uni-kiel.de/index.php/2019/10/26/das-levumi-team-stellt-sich-vor/
- Levumi Nutzungsstudie 2026: https://www.levumi-blog.uni-kiel.de/index.php/2026/05/21/33-000-messungen-spaeter-was-wir-ueber-die-nutzung-von-levumi-wissen/
- 10 Fragen an Levumi (2025): https://empirische-inklusionsforschung.de/2025/11/17/10-fragen-an-levumi/
- Levumi Datenschutz: https://www.levumi-blog.uni-kiel.de/index.php/2019/10/03/datenschutz-und-it-sicherheit-in-levumi/
- Levumi Quellcode: https://github.com/muehling/LeVuMi
- Levumi Handbuch 2.0: https://epub.ub.uni-muenchen.de/107880/1/Levumi_Handbuch.pdf
- Flensburg Projektseite (Finanzierung, BMBF-Anträge): https://www.uni-flensburg.de/ipe/projekte-netzwerke-publikationen-tagungen/aktuelle-projekte/prof-dr-diehl/levumi-lernverlaufsmonitoring
- Blumenthal, Gebhardt, Förster, Souvignier (2022), Vergleich Lernlinie, Levumi, quop: https://epub.uni-regensburg.de/52069/1/Blumenthal_2022_Internetplattformen%20zur%20Diagnostik%20von%20Lernverl%C3%A4ufen.pdf
- DaF-L Projekt: https://www.erzwiss.uni-leipzig.de/institut-fuer-paedagogik-und-didaktik-im-elementar-und-primarbereich/professuren/professur-fuer-schulpaedagogik-des-primarbereichs/forschung/daf-l und https://forschung-inklusive-bildung.de/schulische-bildung/daf-l/
- Gebhardt, Ebenbeck (2025), Lernen rückmelden: https://www.pedocs.de/volltexte/2025/33232/pdf/Gebhardt_Ebenbeck_2025_Lernen_rueckmelden.pdf
- Levumi Material unter CC BY-NC-SA: https://epub.uni-regensburg.de/47880/1/20210818_Lutz_Jungjohann_Materialien%20f%C3%BCr%20Verst%C3%A4rker-%20und%20Belohnungssysteme%20mit%20Levumi.pdf
- Prototype Fund Konditionen 2024: https://netzpolitik.org/2024/millionen-foerderung-fuer-open-source-prototype-fund-startet-in-die-naechste-runde/
- Serlo Finanzierung (Hans Sauer Stiftung): https://www.hanssauerstiftung.de/?p=789
- CBM Grundlagen: https://www.rim.uni-rostock.de/en/the-rim-framework-and-its-implementation/relevance-of-pedagogical-diagnostics-in-rim/curriculum-based-measurements-in-rim/
