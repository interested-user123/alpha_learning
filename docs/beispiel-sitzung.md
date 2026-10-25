# Beispiel: Eine Alpha-Sitzung im Detail

Stand: Oktober 2026. Konkretisiert `cbm-und-alpha.md`. Zahlen sind Arbeitsannahmen, keine validierten Werte.

---

## 0. Zwei Sorten Aufgaben, zwei Sorten Wiederholung

Bevor der Ablauf Sinn ergibt, muss eine Unterscheidung stehen, die das Inhaltsformat kennen muss:

| | **Fakt-Item** | **Fertigkeits-Item** |
|---|---|---|
| Beispiel | Sichtwort "und", Buchstabe "Sch", Artikel von "Tisch" | einen neuen Satz lesen und verstehen, eine Lücke im Text füllen |
| Lernziel | abrufen, automatisieren | anwenden auf Unbekanntes |
| Wiederholung desselben Items | **erwünscht** (Spaced Repetition, FSRS) | **verboten** als Messung; erlaubt nur als explizites Flüssigkeitstraining (wiederholtes Lautlesen) |
| Was zählt | richtig oder falsch, Reaktionszeit | richtig oder falsch, Reaktionszeit, **auf einem nie gesehenen Item** |
| Fortschrittsmaß | Anzahl stabil abrufbarer Fakten | Elo-Fähigkeitswert im Konstrukt |

Der Fehler im ursprünglichen Gedanken (zehn Texte, Text 1 an Tag 1, Tag 2, Tag 4 wieder) ist, dass ein Text als Fertigkeits-Item behandelt wird, als wäre er ein Fakt. Beim dritten Mal misst man Gedächtnis, nicht Lesen. Die Lösung ist nicht, Wiederholung zu streichen, sondern sie an die richtige Stelle zu setzen: Wörter wiederholen sich, Texte nicht.

Ausnahme, die man kennen sollte: **Wiederholtes Lautlesen** desselben Textes ist ein gut belegtes Verfahren für Leseflüssigkeit. Das ist aber Training, nicht Messung, und wird im Format als eigener Aufgabentyp geführt ("Flüssigkeitstraining: Text dreimal lesen, Zeit stoppen"), getrennt von Verständnisaufgaben.

---

## 1. Das Konstrukt-Modell für Lesen

Alpha misst nicht "Lesen", sondern einzelne Konstrukte, die aufeinander aufbauen. Die Einteilung folgt den Levumi-Tests, damit die Werte anschlussfähig sind:

| Stufe | Konstrukt | Fakt oder Fertigkeit | Beispiel-Item |
|---|---|---|---|
| L0 | Buchstabe-Laut | Fakt | "Welcher Buchstabe macht /m/?" (Audio, drei Bilder) |
| L1 | Silben lesen | Fertigkeit | Silbe "ma" erscheint, Kind spricht oder wählt passendes Audio |
| L2 | Wörter lesen | gemischt: Sichtwörter Fakt, neue Wörter Fertigkeit | "Hund" lesen, Bild aus drei wählen |
| L3 | Sätze sinnentnehmend | Fertigkeit | "Der Hund ___ im Garten." (Maze: schläft / Tisch / blau) |
| L4 | Kurztext verstehen | Fertigkeit | 3 bis 5 Sätze, zwei Fragen mit Bildantwort |

Jedes Kind hat **pro Konstrukt** einen Fähigkeitswert (Elo). Jedes Item hat **pro Konstrukt** einen Schwierigkeitswert. Beides startet mit einer Schätzung aus dem Screening beziehungsweise von der Autorin und wird mit jeder Antwort angepasst.

---

## 2. Ablauf einer Sitzung (Dienstag, Woche 6, Kind #4829)

Kind: Amir, 8 Jahre, Klasse 2, Deutsch als Zweitsprache (Türkisch), Lesen auf Stufe L2/L3. Gerät: Schul-iPad, geteilt, Kopfhörer.

### Anmeldung (20 Sekunden)
Bild-Login: Amir tippt sein Avatar-Bild aus der Klassenübersicht, dann sein geheimes Symbol (kein Passwort, kein Name auf dem Bildschirm). Intern wird daraus die ID #4829. Kopfhörer-Symbol blinkt, bis Audio bestätigt ist (ein Ton, Kind tippt "gehört").

### Block A: Aufwärmen mit Fakten (2 Minuten)
Acht Sichtwörter aus Amirs FSRS-Warteschlange, also Wörter, die laut Wiederholungsalgorithmus heute fällig sind: "ist", "haben", "dann", "Schule", "weil", "nicht", "immer", "Freund".
- Wort erscheint groß, Amir tippt auf eines von drei Bildern oder auf den Lautsprecher und spricht nach (je nach eingestelltem Modus).
- Richtig und schnell (unter 3 Sekunden): Intervall verlängert sich.
- Richtig, aber langsam: Intervall bleibt.
- Falsch: Wort wird vorgelesen, Silbenbögen erscheinen, Wort kommt in dieser Sitzung noch einmal.
- Fortschritt für Amir sichtbar: acht kleine Sterne füllen sich.

Was hier gemessen wird: Automatisierung des Sichtwortschatzes. Jedes Item ist bekannt, Wiederholung ist der Zweck.

### Block B: Kern, neue Fertigkeits-Items (6 bis 7 Minuten)
Die Engine wählt Items aus Konstrukt L3 (Sätze), deren Schwierigkeit so liegt, dass Amir sie mit etwa 75 Prozent Wahrscheinlichkeit löst. Das ist der Math-Garden-Wert: fordernd, nicht frustrierend. Jedes Item ist für Amir neu.

Item 1 (L3, Maze): "Amir geht in die ___." Auswahl: Schule / Hund / grün. Satz wird auf Wunsch vorgelesen, das Lückenwort nicht.
Amir wählt "Schule", 4 Sekunden. Richtig. Sein L3-Wert steigt leicht, die Schwierigkeit des Items sinkt minimal.

Item 2 (L3, etwas schwerer): "Weil es regnet, nimmt Lea einen ___ mit." Auswahl: Schirm / Apfel / schnell.
Amir wählt "Apfel", 2 Sekunden. Falsch, schnell. Rückmeldung ohne Fehlerton: Der Satz wird vorgelesen, "Schirm" wird eingesetzt, ein Bild erscheint. L3-Wert sinkt leicht.

Item 3 (L3, leichter, weil die Engine nach einem Fehler einen Schritt zurückgeht): "Der Ball ist ___." Auswahl: rot / isst / Haus. Richtig.

Items 4 bis 9 folgen demselben Muster. Nach Item 9 hat Amir sechs von neun richtig, der L3-Wert ist netto leicht gestiegen.

**Was die Engine nebenbei prüft (Fallback-Regeln):**
- Drei Fehler in Folge **mit Antwortzeit unter 2 Sekunden**: Raten-Muster. Reaktion: Audio-Pflicht einschalten, nächstes Item erst nach vollständigem Vorlesen anwählbar.
- Drei Fehler in Folge **mit langer Antwortzeit**: Überforderung im Konstrukt. Reaktion: Wechsel auf L2-Items (Wörter) für den Rest des Blocks. Für die Lehrkraft wird ein Hinweis gesetzt.
- Wiederholt daneben getippt bei Drag-Aufgaben (Ziel knapp verfehlt): Motorik-Hinweis, Aufgabentyp wechselt auf große Tipp-Flächen. Nach drei Sitzungen mit diesem Muster: Vorschlag "Motorik-Baustein" an die Lehrkraft.
- Sprach-Items ohne erkennbare Antwort (wenn Spracheingabe aktiv): zwei Versuche, dann Bildauswahl als Ersatz. Kein Fehler für das Kind, Markierung für die Lehrkraft.

### Block C: Anker-Probe (nur montags, 1 Minute)
Heute ist Dienstag, Block C entfällt. Am Montag sah er so aus:
- "Lese-Minute": Eine Liste von Wörtern erscheint, Amir liest so viele wie möglich in 60 Sekunden laut vor (Lehrkraft hört zu und tippt Fehler, oder Spracherkennung zählt, wenn aktiv), oder im Stillmodus: Wort-Bild-Zuordnung so viele wie möglich in 60 Sekunden.
- Die Wortliste ist eine von zwölf geprüften **Parallelformen gleicher Schwierigkeit**. Keine Hilfe, kein Audio, keine Anpassung. Ergebnis: 23 richtige Wörter.
- Dieses Ergebnis geht nicht in den Elo-Wert, sondern in die **Ankerkurve** für die Lehrkraft. Es ist der standardisierte Messpunkt, mit dem die Elo-Schätzung kalibriert und gegen Drift geprüft wird.
- Für Amir ist es eine ruhige Minute mit anschließend einem Stern, nicht mehr. Kein Vergleich mit anderen, keine Zahl.

Warum nicht jeden Tag: weil Parallelformen knapp sind (zwölf im Jahr reichen für wöchentlich) und weil die tägliche Elo-Messung die Entwicklung schon abbildet. Die Ankerprobe ist die Kontrolle, nicht die Hauptmessung. Wenn sich nach einem Jahr Daten zeigt, dass Elo und Anker übereinstimmen, kann der Anker seltener werden.

### Block D: Behalten und Abschluss (1 bis 2 Minuten)
- Ein Fertigkeits-Item aus dem Konstrukt, das Amir vor drei Wochen geübt hat (L2, Wörter lesen), neu, nie gesehen. Prüft, ob die Fertigkeit stabil bleibt, ohne ein altes Item zu wiederholen. Richtig.
- Avatar-Moment: Amir hat heute die Sterne für ein neues Accessoire voll. Kurze Animation, Auswahl, fertig.
- Kein Hinweis auf Fehler, kein Vergleich, kein "Du bist auf Stufe 3".

Gesamtdauer: knapp 11 Minuten.

---

## 3. Was auf dem Gerät gespeichert wird

Pro Antwort ein Ereignis (xAPI-nah):

```
{ "kind": "#4829", "zeit": "2026-10-27T09:14:03", "item": "L3-0412",
  "konstrukt": "L3", "block": "B", "richtig": false, "ms": 2100,
  "hilfe": ["vorlesen"], "modus": "tipp" }
```

Daraus berechnet die Engine lokal: Elo pro Konstrukt, FSRS-Zustand pro Fakt-Item, Ankerwerte, Fallback-Zähler. Es gibt keinen Namen in den Daten. Die Zuordnung #4829 = Amir liegt nur bei der Lehrkraft (Papier oder Lehrkraftgerät), nicht auf dem Kindergerät, nicht im Export.

---

## 4. Was die Lehrkraft sieht (nach dem QR-Sync, Freitag)

Keine Rohkurven auf der Startseite. Pro Kind eine Zeile:

| ID | Konstrukt | Trend 4 Wochen | Anker | Status | Vorschlag |
|---|---|---|---|---|---|
| #4829 | L3 Sätze | steigend | 19 → 23 Wörter/Min | im Ziel | weiter wie bisher |
| #3310 | L3 Sätze | flach | 14 → 14 → 13 → 14 | **4 Punkte unter Ziellinie** | Wechsel auf L2-Schwerpunkt, Silbentraining |
| #5127 | L2 Wörter | steigend | – | Motorik-Hinweis 3× | Motorik-Baustein anbieten |

Beim Vorschlag für #3310 drei Schaltflächen: **Bestätigen**, **Ändern** (öffnet die Stufenliste und das Fallback-Menü), **Später** (Kind bleibt, Hinweis bleibt sichtbar). Ohne eine dieser Aktionen ändert die App die Förderstufe des Kindes **nicht**. Innerhalb einer Sitzung passt die Engine die Item-Schwierigkeit an, das ist Mikro-Anpassung und läuft automatisch. Die Stufe, also der Förderschwerpunkt für die nächsten Wochen, ist eine Makro-Entscheidung und bleibt beim Menschen. Das ist die strukturelle Trennung, die der Rechtslage und der Fuchs-Warnung entspricht.

Wer die Kurve sehen will, tippt auf die Zeile: Ankerpunkte, Ziellinie, Trendlinie (einfache lineare Regression über die letzten sechs Punkte), ein grau hinterlegtes Band für die übliche Schwankung. Darunter in einem Satz, was die Vier-Punkte-Regel sagt. Nicht mehr.

Die Gruppierungsansicht sortiert Kinder nach ausgelöster Regel und Konstrukt: "L2-Schwerpunkt: #3310, #2208, #4471" wird zur Fördergruppe für Montag.

---

## 5. Wie Inhalte entstehen (vom Lehrplan zur Aufgabe)

Die Kette, die du beschreibst, stimmt und ist genau die Kette, die das Format abbildet:

1. **Lehrplan**: Kompetenzerwartung, zum Beispiel NRW Deutsch Ende Klasse 2: "lesen kurze altersgemäße Texte und beantworten Fragen dazu".
2. **Konstrukt**: Alpha übersetzt die Kompetenz in messbare Konstrukte (L3, L4). Das ist der Schritt, den der Lehrplan nicht macht und der mit Fachdidaktik und Diagnostik (Levumi, Köln) abgestimmt sein muss.
3. **Reihe**: eine Autorin schreibt eine Übungsreihe für L3, zum Beispiel "Sätze mit Nebensatz (weil, wenn)". Metadaten: Konstrukt, geschätzte Schwierigkeit pro Item, Lehrplanbezug, Lizenz, Audio.
4. **Items**: mindestens 40 Fertigkeits-Items pro Reihe (damit nichts wiederholt werden muss), Fakt-Items beliebig. Jedes Item hat Lösung, Distraktoren, Audio, Bild, optional Fallback-Variante (große Flächen, Bildantwort).
5. **Review**: Schema prüft Vollständigkeit automatisch. Zwei Menschen prüfen fachlich. Erst dann im Kanon.

Was dabei "richtig" heißt: Ein Kind, das alle Items einer Reihe löst, hat die Reihe gemeistert (Mastery). Ob es die **Kompetenz** hat, zeigt sich daran, dass es neue Items desselben Konstrukts aus einer anderen Reihe löst (Transfer) und dass die Ankerkurve steigt. Das Format sorgt dafür, dass beides passiert: Die Engine zieht Items für Block B aus allen freigegebenen Reihen des Konstrukts, nicht nur aus einer.

### Wo pädagogische Regeln leben

Deine Sorge, dass Lehrkräfte das Format schlecht einsetzen könnten (etwa Texte als Wiederholung einplanen), wird an drei Stellen abgefangen:

- **Im Schema**: Ein Item hat ein Pflichtfeld "Typ: Fakt oder Fertigkeit". Ein Fertigkeits-Item kann gar nicht in eine Wiederholungswarteschlange gelegt werden, das Format sieht es nicht vor.
- **In der Engine**: Fertigkeits-Items werden pro Kind höchstens einmal in 90 Tagen gezeigt. Eine Reihe mit zu wenigen Items wird nicht freigegeben. Messproben sind unveränderlich.
- **Im Autorenleitfaden und Review**: Erklärt warum, mit genau diesem Beispiel.

Die Lehrkraft entscheidet, **welche** Reihe ein Kind bekommt und **wann** die Stufe wechselt. **Wie** geübt und gemessen wird, entscheidet das System nach Regeln, die einmal fachlich festgelegt und dokumentiert sind. Das ist die Arbeitsteilung, die Fehlanwendung strukturell ausschließt, ohne die Lehrkraft zu entmündigen.

---

## 6. Elo als fachübergreifendes Framework

Das Elo-Verfahren (ursprünglich Schach) kennt keine Fächer. Es braucht nur: ein Kind mit einem Fähigkeitswert, ein Item mit einem Schwierigkeitswert, ein Ergebnis. Math Garden hat es für Rechnen gezeigt, dieselbe Firma betreibt es für Sprache und Wortschatz. Die Formel ist überall gleich:

- Erwartete Lösungswahrscheinlichkeit = Funktion von (Fähigkeit minus Schwierigkeit).
- Nach der Antwort: Fähigkeit steigt oder sinkt um K mal (Ergebnis minus Erwartung). Item-Schwierigkeit bewegt sich entgegengesetzt.
- Math Garden rechnet die Antwortzeit ein: schnell und richtig gibt mehr als langsam und richtig, schnell und falsch kostet mehr als langsam und falsch. Das bremst Raten.
- Items werden so gewählt, dass die erwartete Lösungswahrscheinlichkeit bei etwa 0,75 liegt.

Für Alpha heißt das: Das Konstrukt-Modell (Abschnitt 1) ist der einzige fachspezifische Teil. Für Mathematik wären es Konstrukte wie Mengen erfassen, Zahlzerlegung, Addition im Zehnerraum. Engine, Elo, FSRS, Anker-Logik, Dashboard und Format bleiben identisch. Genau das macht Alpha zum Framework statt zur Lese-App.

Bekannte Grenzen, die man einplanen sollte: Neue Items haben unsichere Schwierigkeit, bis sie oft genug beantwortet wurden (Lösung: Autorinnen-Schätzung als Start, Items anfangs mit höherem K). Ein fester K-Wert ist ein Kompromiss zwischen Beweglichkeit und Stabilität (aktuelle Forschung aus Amsterdam und Tilburg 2025 arbeitet an dynamischem K). Und die Elo-Skala ist relativ, nicht absolut; der Anker-Test gibt ihr den Bezug zur realen Lesefähigkeit.

---

## 7. Die Analogie zum Krafttraining

Die passt besser, als man denkt, und hilft beim Erklären:

| Krafttraining | Alpha |
|---|---|
| Progressive Überlastung: Gewicht steigt, wenn die Wiederholungen sauber sind | Elo-Zielwert 0,75: Items werden schwerer, sobald das Kind sicher löst |
| Doppelte Progression: erst Wiederholungen hoch, dann Gewicht hoch | erst mehr Items einer Stufe sicher, dann nächste Stufe |
| Autoregulation (RPE): Tagesform bestimmt die Last | Antwortzeit und Fehlerquote in der Sitzung steuern die nächste Aufgabe |
| Deload-Woche nach Plateau | Fallback auf leichteres Konstrukt nach Überforderungsmuster |
| 1RM-Test: selten, standardisiert, ohne Hilfe | Ankerprobe: wöchentlich, Parallelform, ohne Hilfe |
| Trainingslog | Ereignisprotokoll auf dem Gerät |

Was nicht passt: Muskeln reagieren auf Reize gesetzmäßig, Kinder nicht. Ein Plateau beim Lesen kann Motorik, Sprache, Konzentration, Hunger oder ein schlechter Morgen sein. Deshalb schlägt die App vor und die Lehrkraft entscheidet.

---

## Quellen

- Math Garden Grundlagen: https://dare.uva.nl/id/67ab8977-5e36-4f9f-962d-be294f2b8c09
- Elo mit Antwortzeit, Validierung (Straatemeier 2014): https://www.iops.nl/concluded-iops-projects/straatemeier-marthe/
- Dynamischer K-Wert (2025): https://research.tilburguniversity.edu/en/publications/balancing-stability-and-flexibility-investigating-a-dynamic-k-val/
- Graphen-Interpretation, Experiment mit Verlaufsmustern (ZfE 2018): https://link.springer.com/article/10.1007/s11618-018-0836-9
- Jungjohann et al. (2018), Graphen lesen mit Levumi: https://epub.uni-regensburg.de/43557/1/2018_Jungjohann_Diehl__Muehling__Gebhardt_GraphenderLernverlaufsdiagnostik.pdf
- Entscheidungsregeln: https://iris.peabody.vanderbilt.edu/module/pmm/cresource/q2/p07/
- Pseudonymisierung bleibt personenbezogen (Hessen): https://kultus.hessen.de/presse/kontakt-presse-und-oeffentlichkeitsarbeit/datenschutzrechtliche-begriffe
- NRW VO-DV I, private Geräte: https://bass.schule.nrw/pdf/7055.pdf
- Uni Köln, Lehrstuhl Grünke: https://www.hf.uni-koeln.de/30085 und Lernambulanz GaRFIELd: https://www.hf.uni-koeln.de/40411
- Grünke, Review CBM Leseflüssigkeit: https://econtent.hogrefe.com/doi/abs/10.1026/0049-8637/a000011
- Rügener Inklusionsmodell, Evaluation 2015: https://www.rim.uni-rostock.de/storages/uni-rostock/Alle_PHF/RIM/Downloads/RIM-Evaluationsbericht-MZP5_Internet.pdf
- Voß et al. (2014), RIM Effekte: https://www.pedocs.de/volltexte/2014/9248/pdf/ESP_2014_2_Voss_ua_Ruegener_Inklusionsmodell.pdf
