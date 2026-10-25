# Offene Punkte für das Konzept

Stand: Oktober 2026. Lebendes Dokument. Jeder Punkt hat einen Status: **offen**, **Vorschlag liegt vor**, **entschieden**. Entscheidungen wandern in ein eigenes Verzeichnis (ADR), sobald sie fallen.

Reihenfolge innerhalb der Abschnitte: was andere Punkte blockiert, steht oben.

---

## A. Begriffe, die bisher unscharf waren

| Begriff | Was gemeint ist | Status |
|---|---|---|
| **Messprobe** (bisher "Ankerprobe") | Der standardisierte, wöchentliche Kurztest ohne Hilfe, in gleich schweren Parallelformen, wie bei Levumi. Liefert den Messpunkt, der nicht von Übungshilfen oder Anpassung verzerrt ist. "Anker" war meine Wortwahl, weil er die Übungsdaten an eine feste Skala bindet. Besser: Messprobe, für das Kind "Lese-Minute". | Begriff entschieden |
| **Bild-Login** | Anmeldung ohne Tippen und ohne Namen: Das Kind wählt sein Avatar-Bild aus dem Klassenraster und tippt dann sein geheimes Bild (eines aus neun, von ihm selbst gewählt). Alternativ ein QR-Kärtchen. Vorbild: Bild-Passwörter in US-Grundschulsystemen. Zweck: Kinder ohne Lesefähigkeit, geteilte Geräte, kein Name auf dem Bildschirm. | Vorschlag liegt vor |
| **Mikro- und Makro-Anpassung** | Mikro: die Engine ändert innerhalb einer Sitzung Schwierigkeit und Hilfen, automatisch. Makro: der Förderplan eines Kindes (Stufe, Schwerpunkt, Fallback-Bausteine) für die nächsten Wochen. Die Regel "nur über Bestätigen" betrifft **automatische** Makro-Änderungen. Die Lehrkraft selbst kann jederzeit sofort ändern, auch für die ganze Klasse auf einmal, etwa direkt nach dem Screening. Es ist ein Spektrum, keine harte Grenze: Hilfen werden mit steigender Fähigkeit stufenlos ausgeblendet, die Stufe ist nur der Punkt, an dem eine Änderung groß genug ist, dass ein Mensch sie sehen sollte. | Begriff entschieden, Schwelle offen |
| **Übungsformat** | Eine Vorlage, die festlegt, wie ein Aufgabentyp aufgebaut, dargestellt, ausgewertet und lernlogisch behandelt wird (siehe C2). | Vorschlag liegt vor |

---

## B. Daten und Messung (blockiert fast alles andere)

| Nr. | Punkt | Status |
|---|---|---|
| B1 | **Welche Konstrukte** für Lesen, mit welchen Stufen, nach welchem Entwicklungsmodell? Abgleich mit Levumi-Tests und Lehrplan. Ohne das kann weder Format noch Messung gebaut werden. | offen, Kandidat: Levumi-Konstrukte |
| B2 | **Was ist ein Datenpunkt?** Festlegen, welche Felder pro Antwort gespeichert werden (Item, Konstrukt, richtig, Zeit, Hilfen, Modus, Block). Minimal, aber vollständig genug für spätere Modelle. | Vorschlag in beispiel-sitzung.md |
| B3 | **Fähigkeitsschätzung**: Welches Modell berechnet aus Datenpunkten einen Fähigkeitswert? Elo (Math Garden) ist ein Kandidat, nicht die Entscheidung. Alternativen: einfache Trefferquote pro Stufe, gleitender Mittelwert, IRT. Entscheidung erst, wenn B1 und B2 stehen und erste Daten da sind. Antwortzeit soll einfließen, Gewichtung offen. | offen |
| B4 | **Ein Modell pro Konstrukt?** Vorschlag: ja, ein Fähigkeitswert pro Kind und Konstrukt, jedes Item primär einem Konstrukt zugeordnet. Mehrdimensionale Modelle später. | Vorschlag liegt vor |
| B5 | **Messprobe oder nicht?** Math Garden hat nie Messproben in der App gehabt, sondern seine Werte in Studien gegen externe Tests validiert. Alpha kann denselben Weg gehen (Validierungsstudie, zum Beispiel Köln oder Levumi) oder die Messprobe dauerhaft behalten. Für das MVP: Messprobe behalten, weil sie ohne Modell funktioniert und für Lehrkräfte verständlich ist. | Vorschlag liegt vor |
| B6 | **Startschwierigkeit neuer Items**: Autorinnen-Schätzung? Abgeleitet aus Wortlänge, Satzlänge, Frequenz? Kalibrierung über erste Antworten? | offen |
| B7 | **Externe Daten**: Math-Garden-Daten sind nicht offen; Prowise nutzt sie intern mit der Uni Amsterdam. Anfrage möglich, aber niederländische Items helfen für deutsche Lesekonstrukte wenig. Übertragbar ist die Methode, nicht die Daten. Deutsche Normdaten gibt es bei Levumi und quop. | geklärt: nicht verfügbar |
| B8 | **Entscheidungsregeln** für das Dashboard: Vier-Punkte-Regel, Trendlinie, oder beides? Schwellenwerte? | offen, Vorschlag: Vier-Punkte-Regel für MVP |
| B9 | **Screening**: eigenes adaptives Screening oder LES-IN-CAT von Levumi? | offen |

---

## C. Inhalte und Formate

| Nr. | Punkt | Status |
|---|---|---|
| C1 | **Item-Klassen**: Fakt (wiederholen), Fertigkeit (nie wiederholen, Transfer), Training (gezielte Wiederholung, zum Beispiel wiederholtes Lautlesen). Gibt es weitere Klassen? Strategie-Items (Lesestrategie anwenden)? Metakognitive Items? | Vorschlag liegt vor, Liste offen |
| C2 | **Offenes Formatsystem**: Ein Übungsformat besteht aus fünf Teilen: (1) Schema, welche Felder ein Item hat; (2) Darstellung, wie es auf dem Bildschirm aussieht; (3) Auswertung, was richtig heißt und wie Zeit zählt; (4) Lernlogik-Klasse aus C1; (5) Messtauglichkeit, ob es als Messprobe zulässig ist. Neue Formate werden als Definition eingereicht und reviewt wie Inhalte. Die Engine behandelt jedes Format nach seiner Klasse, ohne das Format selbst zu kennen. So bleiben zukünftige Erkenntnisse einbaubar, ohne die Engine zu ändern. Vorbild: H5P-Inhaltstypen, aber mit pädagogischen Metadaten. | Vorschlag liegt vor |
| C3 | **Mindestumfang** pro Reihe und Konstrukt, damit nichts wiederholt werden muss. | offen |
| C4 | **Audio**: menschliche Sprecher (teuer, konsistent, gut) oder Sprachsynthese (billig, skalierbar, Qualität für Kinder prüfen)? Mehrsprachigkeit: welche Sprachen zuerst? | offen |
| C5 | **Autorenwerkzeug**: Tabelle plus Übertragung durch Kernteam (MVP) oder eigener Editor (später)? | Vorschlag: Tabelle für MVP |
| C6 | **Lehrplanbezug**: welches Bundesland als Referenz für das MVP? Kompetenzerwartungen als Metadatum, nicht als Struktur. | offen |
| C7 | **Lizenz Inhalte**: CC BY-SA 4.0. | Vorschlag liegt vor |

---

## D. Das Kind: Erleben und Motivation

Hier fehlte bisher am meisten.

| Nr. | Punkt | Status |
|---|---|---|
| D1 | **Motivationsmodell**: Die Selbstbestimmungstheorie (Deci und Ryan) nennt drei Bedürfnisse: Kompetenz erleben, Autonomie, soziale Eingebundenheit. Alpha hat bisher nur Kompetenz (Sterne, Avatar). Fehlt: Autonomie (Kind wählt Reihenfolge der Blöcke? Thema des Textes? Avatar-Gestaltung?) und Eingebundenheit (Klassenziel? Lehrkraft-Nachricht? Vorlesen für jemanden?). Befunde: Punkte und Abzeichen allein wirken wenig, Kritik an ANTONs Münzsystem kommt aus genau dieser Richtung. | offen |
| D2 | **Belohnungslogik**: Was wird belohnt? Vorschlag: Anwesenheit und Anstrengung, nicht Richtigkeit. Sonst werden schwache Kinder bestraft. Keine Ranglisten. | Vorschlag liegt vor |
| D3 | **Fehlererleben**: Wie sieht ein Fehler aus und an? Kein Ton, keine Farbe rot, Lösung zeigen, weiter. Wie oft darf ein Kind hintereinander scheitern, bevor die Sitzung etwas anderes anbietet? | Vorschlag liegt vor, Schwelle offen |
| D4 | **Abbruch und Pause**: Kind hört mitten in der Sitzung auf. Was wird gespeichert, wie geht es weiter, wird die Sitzung gewertet? | offen |
| D5 | **Sitzungslänge**: 10 bis 15 Minuten fest, oder endet die Sitzung nach Erreichen eines Tagesziels? Was, wenn ein Kind weitermachen will? | offen |
| D6 | **Kinder ohne jede Lesefähigkeit**: Ist die App ab Buchstabe-Laut-Stufe vollständig ohne Schrift bedienbar? Alle Anweisungen als Audio und Bild. | offen, muss ja sein |
| D7 | **Barrierefreiheit**: Kontrastmodus, Schriftgröße, Vorlesen der Oberfläche, Bedienung mit einer Hand, Farbfehlsichtigkeit. | offen |
| D8 | **Avatar-System**: minimalistisch (README). Was genau ist freischaltbar, wie viel Zeit darf es kosten, ist es Autonomie-Quelle (D1)? | offen |
| D9 | **Rahmung der Messprobe**: Wie wird die Lese-Minute dem Kind erklärt, damit sie keine Prüfungsangst erzeugt? | offen |
| D10 | **Eigenes Feedback für das Kind**: Sieht das Kind seinen Fortschritt über Wochen (Gebhardt und Ebenbeck 2025 argumentieren für Rückmeldung an Lernende)? In welcher Form, ohne Vergleich? | offen |

---

## E. Die Lehrkraft

| Nr. | Punkt | Status |
|---|---|---|
| E1 | **Onboarding einer Klasse**: Kinder anlegen, Zuordnungsliste erzeugen, Screening durchführen, Stufen in einem Durchgang zuweisen. Muss in einer Freistunde machbar sein. | offen |
| E2 | **Eingriff während der Sitzung**: Braucht die Lehrkraft einen Modus, in dem sie am Kindergerät etwas ändern kann (Stufe, Hilfen, Sitzung beenden)? | offen |
| E3 | **Sync**: QR-Code vom Kindergerät zum Lehrkraftgerät. Wie oft, wie lange dauert es bei 25 Geräten, was bei verpasstem Sync? | offen |
| E4 | **Dashboard-Umfang MVP**: Statuszeile pro Kind, Vorschlag mit Bestätigen/Ändern/Später, Gruppierung. Nicht mehr. | Vorschlag liegt vor |
| E5 | **Fortbildung**: Wer erklärt Lehrkräften Lernverlaufsdiagnostik? Eine Stunde Einführung als Teil des Pakets? | offen |
| E6 | **Schuljahreswechsel**: Kind wechselt Klasse oder Schule. Daten mitnehmen, übergeben, löschen? | offen |

---

## F. Technik

| Nr. | Punkt | Status |
|---|---|---|
| F1 | **Web oder nativ**: Prototyp auf altem iPad und günstigem Samsung-Tablet entscheidet. | offen |
| F2 | **Geteilte Geräte**: mehrere Kinder pro Tablet, Daten getrennt, Bild-Login. | Vorschlag liegt vor |
| F3 | **Inhaltsverteilung ohne Internet**: Wie kommen neue Reihen und Updates auf Geräte, die nie online sind? Über das Lehrkraftgerät? USB? | offen |
| F4 | **Datenverlust**: Gerät kaputt oder zurückgesetzt. Backup über den Sync? | offen |
| F5 | **Spracherkennung und Handschrift**: welche Technik auf welchem Gerät, Qualität bei Kinderstimmen, Datenschutz (nur auf dem Gerät). | offen, nicht MVP |
| F6 | **Lizenz Code**: AGPL-3.0. | Vorschlag liegt vor |

---

## G. Datenschutz und Recht

| Nr. | Punkt | Status |
|---|---|---|
| G1 | **Begriff korrigieren**: pseudonym, nicht anonym, überall in der Dokumentation. | entschieden |
| G2 | **Zuordnungsliste**: nie auf dem Kindergerät, nie im Export. Papier oder Lehrkraftgerät. | entschieden |
| G3 | **Verfahrensbeschreibung** als Vorlage für Schulen mitliefern. | offen |
| G4 | **Privatgeräte von Lehrkräften**: Hinweis auf Genehmigungspflicht (NRW VO-DV I) im Betriebshandbuch. | offen |
| G5 | **Löschfristen**: Wann werden Daten auf Kindergerät und Lehrkraftgerät gelöscht? | offen |
| G6 | **Forschung mit Kinderdaten** (Validierung, Pilotschulen): Einwilligung der Eltern, Ethikvotum der Hochschule. | offen |

---

## H. Organisation

| Nr. | Punkt | Status |
|---|---|---|
| H1 | **Erstes Thema und erste Klassenstufe** für das MVP. | offen, Kandidat: Lesen Klasse 2, Stufen L0 bis L3 |
| H2 | **Kontakt Levumi** (Formate, Konstrukte, LesePfad-Lizenz). | offen |
| H3 | **Kontakt Köln** (Validierung, Lernambulanz als Testfeld, Abschlussarbeit). | offen |
| H4 | **Einseiter** für diese Kontakte. | offen, nächster Schritt |
| H5 | **Pilotschulen**: zwei bis drei, davon eine Förderschule. | offen |
| H6 | Trägerschaft, Verein, Beirat, Pflege: siehe traegerschaft-und-levumi.md. | später |

---

## Was bisher ganz gefehlt hat

Komponenten, die in keinem der bisherigen Dokumente vorkamen und die ein vollständiges Konzept braucht:

1. **Motivation** als eigenes Modell, nicht als Avatar-Anhängsel (D1 bis D3, D8, D10).
2. **Abbruch, Pause, Wiederaufnahme** (D4, D5).
3. **Barrierefreiheit** über Audio hinaus (D7).
4. **Inhaltsverteilung und Updates** ohne Internet (F3).
5. **Datenverlust und Backup** (F4).
6. **Schuljahreswechsel und Übergabe** (E6).
7. **Löschfristen** (G5).
8. **Lehrkraft-Fortbildung** als Teil des Produkts (E5).
9. **Forschungsethik** für Pilotierung (G6).
10. **Kinder-Feedback über Wochen**, nicht nur pro Sitzung (D10).

Bewusst nicht aufgenommen, weil außerhalb des Kerns: Elternkomponente, Hausaufgabenmodus, Chat oder Nachrichten, soziale Funktionen zwischen Kindern. Falls gewünscht, als spätere Phase.

---

## Quellen

- Selbstbestimmungstheorie in digitalen Lernumgebungen (Bonanati, Buhl, Eickelmann): https://www.hogrefe.com/de/thema/wie-lernen-in-digitalen-lernumgebungen-motivieren-kann
- Gamification in der Grundschule, Masterarbeit mit Viertklässlern: https://www.nna.niedersachsen.de/download/219161
- Gamification ohne messbaren Effekt (Dissertation Münster): https://www.uni-muenster.de/Ebooks/index.php/series/catalog/book/167
- Prowise Learn Forschung mit Uni Amsterdam: https://www.prowise.com/en/product/prowise-learn/prowise-learn-research/
- Math Garden als Datensatz (Hofman 2018): https://www.iops.nl/concluded-iops-projects/hofman-abe/
- Gebhardt und Ebenbeck (2025), Rückmeldung an Lernende: https://www.pedocs.de/volltexte/2025/33232/pdf/Gebhardt_Ebenbeck_2025_Lernen_rueckmelden.pdf
