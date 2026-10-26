# Bestandsaufnahme: Was es schon gibt, was es kostet, und wo Alpha hineinpasst

Stand: Oktober 2026. Grundlage sind öffentlich auffindbare Quellen (Anbieterseiten, Landtagsdrucksachen, Fachartikel, Projektseiten). Preise ändern sich jährlich und sind teils aus Drittquellen; vor einer Entscheidung beim Anbieter prüfen. Quellen stehen am Ende.

---

## 1. Die Vision als Prüfraster

Damit der Vergleich nicht beliebig wird, ist die Vision aus der README in sechs prüfbare Kriterien zerlegt. Jedes bestehende Projekt wird daran gemessen.

| Nr. | Kriterium | Was es konkret heißt |
|---|---|---|
| K1 | **Offen und dauerhaft kostenlos** | Quellcode unter freier Lizenz, Inhalte als OER, keine Jahreslizenz, kein Anbieter, der abschalten kann |
| K2 | **Datensparsam und lokal** | Kein Konto, kein zentraler Server, Daten bleiben auf dem Gerät, Weitergabe nur aktiv |
| K3 | **Adaptiv und förderdiagnostisch** | Diagnose, Stufenlogik, automatische Anpassung, Fallbacks bei Überforderung |
| K4 | **Kindgerecht und flüssig** | Für Kinder mit Förderbedarf bedienbar, Audio überall, keine Textwüsten, keine Ladezeiten |
| K5 | **Inhalte durch Pädagogen erweiterbar** | Neue Übungsreihen ohne Programmieren, mit Review-Prozess |
| K6 | **Geräteunabhängig** | iPad, Android (Samsung), Windows, idealerweise auch alte Geräte |

---

## 2. Steckbriefe der relevanten Projekte

### 2.1 Übungs-Apps für Kinder (kommerziell oder gefördert)

**ANTON (Solocode GmbH, Berlin)**
Die meistgenutzte Lern-App an deutschen Schulen. Inhalte kostenlos, finanziert durch EU- und Senatsförderung sowie Schullizenzen. Schullizenz Plus: 450 € pro Jahr (bis 500 Schüler) bzw. 700 € (darüber). Schullizenz Komplett: 6 € pro Schüler und Jahr, enthält ab Schuljahr 2026/27 "Testen & Fördern" mit Diagnosetests und adaptivem Förderprogramm. Offline-Nutzung nur in der Bezahlvariante. Zentraler Server mit Schülerkonten; 2023 wurde eine Sicherheitslücke bekannt, über die Namen, Klassen und Lernstände abrufbar waren. Proprietär.
Erfüllt: K4 (gut), K6 (iOS, Android, Web), K3 (ab 2026/27, kostenpflichtig). Nicht: K1, K2, K5.

**Oriolus Lernprogramme (OHG, seit 1994)**
Klassische Lernsoftware mit DaZ-Modulen, für Windows, Android, macOS, iOS. Schullizenz "GS+SEK+DaZ gesamt" 299 € pro Jahr, Grundschule gesamt 199 € pro Jahr, Dauerlizenz 800 €. Läuft lokal, Anbieter gibt an, keine Daten zu erheben. Oberfläche wirkt veraltet. Proprietär.
Erfüllt: K2, K6, teilweise K4. Nicht: K1, K3, K5.

**Lernwerkstatt (Medienwerkstatt Mühlacker)**
Seit den 1990ern an Grund- und Förderschulen verbreitet. Schullizenz, Elternlizenz um 20 €. Lokal installierbar, viele Übungstypen, keine Adaptivität im heutigen Sinn. Proprietär.
Erfüllt: K2, teilweise K4. Nicht: K1, K3, K5, K6 (primär Windows).

**Leseludi, Schreibsusi, Lernrudi (im "Samsung Chancentablet")**
Werden als Paket mit Samsung-Tablets über das Startchancen-Programm verkauft, inklusive Jahreslizenzen. Preise nicht öffentlich. Beispiel dafür, wie Hardware und Software gebündelt und an Fördermittel gekoppelt werden: Läuft die Lizenz aus, bleibt das Tablet ohne Inhalt.
Erfüllt: K4 (vermutlich). Nicht: K1, K5, K6 (Samsung-gebunden).

**Meister Cody (Talasia, Namagi; mit LMU-Klinikum)**
Adaptive Lerntherapie-Apps für Rechnen, Lesen, Rechtschreiben, wissenschaftlich begleitet. Für Lehrkräfte zeitweise kostenfrei über Schulcodes, sonst Abo (früher 9,99 € pro Monat). Zentrale Konten. Proprietär.
Erfüllt: K3 (am stärksten von allen), K4. Nicht: K1, K2, K5.

**bettermarks (Mathematik, Sek I)**
Das bekannteste adaptive System an deutschen Schulen, nur Mathematik. Finanziert über Landeslizenzen: Berlin 1,1 Mio. € für ein Schuljahr, Rheinland-Pfalz verlängert bis 2027/28, Niedersachsen lief über "Startklar" bis 2025/26. Zeigt, was Adaptivität in der Praxis kostet und wie abhängig Schulen von Landesentscheidungen sind.
Erfüllt: K3, K4. Nicht: K1, K2, K5, falsches Fach.

**Khan Academy Kids, Duolingo ABC**
Kostenlos, sehr gut gemacht, aber englischsprachig, US-Server, nicht DSGVO-konform ohne Umwege. Vor allem als Maßstab für K4 interessant.

### 2.2 Diagnose-Werkzeuge für Lehrkräfte

**Levumi (Uni Kiel/IPN, Regensburg, München)**
Lernverlaufsdiagnostik für Lesen, Rechtschreiben, Mathematik, Verhalten. Kostenfrei, Fördermaterial als OER, Quellcode liegt auf GitHub (Lizenz dort prüfen). Für Regel- und Förderschulen, wöchentliche Kurztests, Graphen für Lehrkräfte. Kein Übungsprogramm für Kinder, sondern Messinstrument. Das wissenschaftlich fundierteste offene Projekt in diesem Feld und der natürliche Partner für die Diagnoseseite von Alpha.
Erfüllt: K1, K3 (Diagnose), teilweise K5. Nicht: K2 (Serverkonten), K4 (nicht für Kinder gebaut).

**quop (Uni Münster)**
Ebenfalls Lernverlaufsdiagnostik, Lesen und Mathe Klasse 1 bis 6, für Hessen kostenlos über Landesvertrag. Nicht Open Source.

**Lernserver (Münster, Institut)**
Rechtschreibdiagnose plus Fördermaterial, Landeslizenz in Bremen, Preise nicht öffentlich, wirbt gezielt für Startchancen-Budgets. Proprietär.

**ILeA plus (LISUM Berlin-Brandenburg)**
Digitale Lernausgangslagen, Zugang über Bildungsserver, Lizenz unklar.

### 2.3 Offene Werkzeuge und Plattformen

**LearningApps.org (Verein, Schweiz)**
Kostenloser Baukasten für einzelne interaktive Übungen ("Apps"), spendenfinanziert, werbefrei, ohne Anmeldung nutzbar. Nicht Open Source. Schülerkonten und Lernstandsanzeige wurden 2021 aus Datenschutzgründen abgeschaltet. Keine Lernpfade, keine Diagnose, keine Adaptivität, kein Audio-Konzept für Nichtleser. Jede Übung steht für sich.
Erfüllt: K5 (Lehrkräfte bauen selbst), K6 (Browser), kostenlos aber nicht K1 (kein Quellcode, keine Garantie). Nicht: K2 (Serverdienst), K3, K4 (für Förderkinder zu textlastig).

**H5P und Lumi**
Open-Source-Framework für interaktive Inhaltstypen, Lumi als Offline-Editor. Gleiche Grundidee wie LearningApps, technisch offen, aber dieselben Grenzen: Einzelübungen, keine Pfadlogik, generische Oberfläche, Hosting nötig.

**GCompris (KDE, seit über 20 Jahren)**
Rund 200 Lernaktivitäten für Kinder von 2 bis 10, AGPL, kostenlos, läuft auf Linux, Windows, macOS, Android, iOS, Raspberry Pi. Vollständig lokal, keine Konten. Kein Fördermodell, keine Diagnose, kein DaZ, Inhalte nur über Programmierung erweiterbar. Beweist, dass ein offenes Kinder-Lernprogramm über Jahrzehnte lebendig bleiben kann, wenn es an eine Community (hier KDE) angedockt ist.
Erfüllt: K1, K2, K6, teilweise K4. Nicht: K3, K5.

**Kolibri (Learning Equality, MIT-Lizenz)**
Offline-first-Lernplattform für Regionen ohne Internet, lokaler Klassenserver, Peer-to-Peer-Sync, Fortschrittsverfolgung, über 200 Länder. Für die Architekturfrage "lokal synchronisieren ohne Cloud" das beste Vorbild. Inhalte vor allem englischsprachig, keine Förderdiagnostik, eher Sek-Niveau.

**Serlo (Serlo Education e.V., München)**
Freie Lernplattform nach Wikipedia-Prinzip, Inhalte unter freien Lizenzen, Editor unter Apache-2.0. Zeigt, wie ein Verein mit Stiftungsmitteln und Ehrenamt eine offene Inhaltsplattform trägt. Zielgruppe Sek I/II, Text- und Aufgabenbasis, nicht für Förderkinder.

**dBildungscloud (ehemals HPI Schul-Cloud; Niedersachsen, Brandenburg, Thüringen)**
Open-Source-Lernplattform, von drei Ländern über Dataport betrieben. Thüringen veranschlagt rund 3,7 Mio. € pro Jahr. Relevant als Beleg, dass Länder offene Software betreiben, und als Maßstab, was Betrieb auf Landesebene kostet.

### 2.4 Infrastruktur und Standards der Länder

- **VIDIS** (FWU, alle 16 Länder): Anmeldedienst, über den Schülerinnen aus dem Landesportal mit einem Login in Lern-Apps kommen. Eine App, die auf Landesebene eingeführt werden soll, wird früher oder später danach gefragt. Für Alpha optional, da lokal ohne Konto, aber als späteres Modul mitzudenken.
- **mundo / SODIX** (DigitalPakt, FWU) und **WirLernenOnline**: OER-Verzeichnisse der Länder, über 50.000 geprüfte Materialien. Inhalte von Alpha könnten dort gelistet werden, wenn sie Metadaten nach **AMB** (Allgemeines Metadatenprofil für Bildungsressourcen, schema.org als JSON-LD) liefern.
- **xAPI**: Standard für Lernereignisse ("Kind X hat Aufgabe Y mit Ergebnis Z gelöst"). Für die lokale Fortschrittsspeicherung und für Export an Dashboards sinnvoll.
- **QTI 3.0**: Standard für Testaufgaben, XML-basiert, schwergewichtig. Als Vorlage für die Item-Struktur nützlich, nicht zur Übernahme.
- **FSRS**: Offener Algorithmus für Wiederholung mit Abstand (BSD/MIT, in Anki). Für die Wiederholungslogik direkt nutzbar.

---

## 3. Das Venn-Diagramm

Drei Kreise: **offen und kostenlos** (K1), **adaptiv und förderdiagnostisch** (K3), **kindgerechte Übungs-App** (K4). Siehe auch `docs/venn.svg`.

```
                 OFFEN & KOSTENLOS
                 ─────────────────
                 Serlo · Kolibri · H5P/Lumi
                 (LearningApps: kostenlos, aber nicht offen)
                 dBildungscloud (Infrastruktur)
                        │
          Levumi ───────┼─────── GCompris
      (Diagnose als     │      (offen, kindgerecht,
       OER, Code auf    │       lokal, aber nicht
       GitHub, aber     │       adaptiv, kein DaZ)
       keine Kinder-App)│
                        │
                 ┌──────┴──────┐
                 │  ∅  (hier   │
                 │  steht noch │
                 │  niemand)   │
                 └──────┬──────┘
                        │
  ADAPTIV & ────────────┼──────────── KINDGERECHTE
  FÖRDERDIAGNOSTISCH    │             ÜBUNGS-APP
  quop · Lernserver     │             ANTON · Oriolus
  ILeA plus             │             Lernwerkstatt
  Westermann Diagnose   │             Leseludi · Khan Kids
                        │             Duolingo ABC
           Meister Cody / Namagi
           bettermarks (nur Mathe)
           ANTON Komplett (ab 2026/27, 6 €/Kind/Jahr)
```

Der Schnitt aller drei Kreise ist leer. Es gibt offene Diagnostik (Levumi), offene Kinder-Software (GCompris) und adaptive Kinder-Apps (Meister Cody, bald ANTON), aber nichts, das alle drei verbindet. Nimmt man **K2 (lokal, ohne Konto)** als vierte Dimension dazu, bleiben von den adaptiven Angeboten gar keine übrig: Alle adaptiven Systeme laufen über zentrale Server mit Schülerkonten.

---

## 4. Ist das nicht einfach LearningApps mit schönerer Oberfläche?

Nein. Die Überschneidung ist kleiner, als es auf den ersten Blick wirkt.

**Was sich überschneidet:** Die einzelnen Übungstypen. Zuordnen, Lückentext, Paare finden, Reihenfolge: Das haben LearningApps, H5P, ANTON und Alpha gemeinsam, und das ist der am wenigsten originelle Teil. Hier sollte Alpha nichts neu erfinden, sondern bewusst von den bewährten Typen abschauen.

**Was LearningApps nicht hat und nicht haben will:**

1. **Einen Lernpfad.** LearningApps kennt nur Einzelübungen. Es gibt kein "danach kommt Stufe 3" und kein "zurück auf Stufe 1, weil dreimal daneben".
2. **Diagnose.** Es misst nicht, wo ein Kind steht. Es weiß nach der Übung nicht mehr als vorher.
3. **Fallbacks.** Die Idee, bei Scheitern auf Motorik- oder Sprachtraining umzuschalten, hat keines der untersuchten Produkte.
4. **Lokale Daten.** LearningApps hat Schülerkonten aus Datenschutzgründen gestrichen und kann deshalb gar keinen Lernstand mehr führen. Alpha löst dasselbe Problem andersherum: Lernstand ja, aber nur auf dem Gerät.
5. **Audio zuerst.** LearningApps setzt Lesefähigkeit voraus. Für DaZ- und Förderkinder ist das die Eintrittsbarriere.
6. **Offenheit.** LearningApps ist kostenlos, aber ein geschlossener Dienst eines kleinen Vereins. Stellt der Verein den Betrieb ein, ist alles weg.

**Fazit:** Wer einen Übungs-Baukasten baut, erfindet LearningApps und H5P neu. Wer einen adaptiven Förderkreislauf mit lokalen Daten baut, der offene Übungstypen *verwendet*, baut etwas, das es nicht gibt. Der Unterschied liegt nicht in der Oberfläche, sondern in der Logik darunter.

---

## 5. Kosten und das Wechselproblem der Schulen

Die Recherche bestätigt das Muster, das du beschreibst, und erklärt es:

- **Fast alles ist eine Jahreslizenz.** ANTON 450 bis 700 € pro Schule und Jahr, Oriolus 199 bis 299 €, Marktplatz-Modelle 26 € pro Kind und Jahr, bettermarks auf Landesebene im Millionenbereich. Der Bayerische Landtag hält fest, dass "viele Lernapps abonnementbasiert" sind und Schulen eigene Budgets dafür brauchen.
- **Landeslizenzen laufen aus.** Niedersachsen (bettermarks bis 2025/26), Rheinland-Pfalz (bis 2027/28), Bremen (Lernserver, verlängert nach Testphase). Wenn ein Land nicht verlängert, verlieren alle Schulen das Werkzeug gleichzeitig, inklusive der eingearbeiteten Lehrkräfte und der Kinderdaten.
- **Fördertöpfe wechseln.** DigitalPakt ausgelaufen, Startchancen-Programm bis 2034 mit rund 150.000 € pro Schule und Jahr in NRW (Säule II), aber nur für ausgewählte Schulen. Anbieter richten ihre Pakete gezielt auf diese Töpfe aus (Samsung Chancentablet, Lernserver).
- **Hardware und Software werden gebündelt.** Tablets mit vorinstallierten Jahreslizenzen koppeln das Gerät an einen Anbieter.

Daraus folgt für Alpha ein klares Kostenargument, aber auch eine Pflicht:

**Das Argument:** Eine offene, lokal laufende App hat für die Schule null Lizenzkosten, null Betriebskosten (kein Server), null Wechselrisiko (Inhalte und Daten bleiben, auch wenn das Projekt stirbt) und null Datenschutzvertrag (keine Auftragsverarbeitung, weil keine Daten fließen).

**Die Pflicht:** Entwicklung und Pflege kosten trotzdem Geld. Levumi lebt von Universitäten, Serlo von Verein und Stiftungen, GCompris von der KDE-Community, dBildungscloud von Landesmitteln. Alpha braucht von Anfang an eine Vorstellung, wer das trägt: ein Verein, eine Hochschule, ein Landesinstitut, eine Stiftung. "Open Source" allein ist kein Finanzierungsmodell. Das ist die ehrliche Antwort auf die Frage, warum es den leeren Schnitt im Venn-Diagramm noch gibt: Adaptivität ist teuer zu entwickeln, und wer sie bezahlt hat, verkauft sie.

---

## 6. Was sich aus den bestehenden Projekten lernen lässt

| Projekt | Lehre für Alpha |
|---|---|
| LearningApps schaltet Schülerkonten ab | Zentraler Lernstand und Datenschutz vertragen sich in der Praxis nicht. Lokal ist der einzige ruhige Weg. |
| ANTON-Datenpanne 2023 | Ein Server mit Kinderdaten ist ein Haftungsrisiko, auch für seriöse Anbieter. |
| GCompris lebt seit über 20 Jahren | Offene Kindersoftware überlebt, wenn sie an eine bestehende Community angedockt ist. Alpha sollte nicht allein stehen. |
| Levumi | Wissenschaftliche Anbindung schafft Vertrauen bei Lehrkräften und Ländern. Diagnostik nicht neu erfinden, sondern mit Levumi sprechen. |
| Kolibri | Offline-first mit Peer-Sync ist gelöst und dokumentiert. Architektur abschauen. |
| H5P / LearningApps | Übungstypen sind Commodity. Nicht der Kern. |
| bettermarks, Meister Cody | Echte Adaptivität braucht Fachdidaktik plus Daten. Regelbasiert starten, nicht mit KI. |
| dBildungscloud | Länder betreiben offene Software, aber der Betrieb kostet Millionen. Deshalb: keine Serverpflicht. |
| Samsung Chancentablet | Gerätebindung ist eine Falle für Schulen. Deshalb: K6 ist nicht verhandelbar. |

---

## 7. Standards: übernehmen, adaptieren, ignorieren

| Standard | Empfehlung | Begründung |
|---|---|---|
| Markdown | übernehmen | Für alle Erklär- und Handbuchtexte |
| YAML/JSON mit Schema | übernehmen | Für Übungsreihen und Lernpfade, von Pädagogen lesbar, maschinell prüfbar |
| SVG, WebP, Opus | übernehmen | Grafik und Audio, klein, offen, skalierbar |
| xAPI | adaptieren | Ereignisformat für lokale Fortschrittsdaten; vereinfachtes Profil, volle Kompatibilität nur beim Export |
| AMB (schema.org JSON-LD) | übernehmen für Metadaten | Damit Inhalte in mundo und WirLernenOnline gelistet werden können |
| FSRS | übernehmen | Wiederholungslogik, permissiv lizenziert |
| QTI 3.0 | nur als Vorlage | Zu schwer für den Zweck, aber gute Item-Taxonomie |
| H5P | ignorieren | Eigene Übungstypen sind für Förderkinder nötig; H5P-Export allenfalls später |
| VIDIS, LTI | später, optional | Nur relevant, wenn ein Land ein Dashboard mit Login betreiben will |
| ODF | ignorieren | Dokumentformat, kein Übungsformat |
| CC BY-SA (Inhalte), AGPL oder MIT (Code) | entscheiden | Copyleft schützt die Offenheit, MIT erleichtert Übernahme durch Länder. Empfehlung: AGPL für die App, CC BY-SA für Inhalte. |

---

## 8. Technik: Web oder nativ

Die Recherche gibt keine eindeutige Antwort, aber zwei harte Fakten:

- **Web-Apps lassen sich über MDM nur als "Web Clip" verteilen.** Auf geteilten iPads (Shared iPad, der Normalfall an Grundschulen) berichten Schul-Admins von Problemen: Web Clips erscheinen nicht, lassen sich nicht ins Dock legen, verhalten sich je nach MDM anders. Native Apps haben dieses Problem nicht.
- **Native Apps brauchen App-Store-Konten** (Apple Developer Program 99 $ pro Jahr, Google Play einmalig) und Review-Prozesse, dafür saubere MDM-Verteilung, Offline-Garantie und Zugriff auf Handschrift und Sprache.

Empfehlung: Kern als plattformneutrale Engine, erste Auslieferung als native App über ein Cross-Platform-Framework (Flutter oder Web-Kern in Capacitor-Hülle), Web-Variante als Zusatz für Browser und alte Geräte. Die Entscheidung Flutter gegen Web-Kern sollte an einem Prototyp mit echten Animationen auf einem alten iPad und einem günstigen Samsung-Tablet getroffen werden, nicht auf dem Papier.

---

## 9. Positionierung in einem Satz

Alpha ist nicht "LearningApps, aber schöner" und nicht "ANTON, aber kostenlos". Alpha ist der fehlende Schnitt: **ein offener, lokal laufender Förderkreislauf (Diagnose, Übung, Wiederholung, Fallback) für Kinder, die lesen erst lernen, mit Inhalten, die Pädagogen selbst schreiben und prüfen.** Die Übungstypen sind geliehen, die Diagnostik ist bei Levumi abzustimmen, die Offline-Architektur bei Kolibri abzuschauen. Neu ist die Verbindung.

---

## 10. Offene Fragen für die nächste Runde

1. Trägerschaft: Verein, Hochschule, Landesinstitut? Ohne Antwort kein Vertrauen bei Schul-IT.
2. Kontakt zu Levumi: Diagnostik gemeinsam statt parallel?
3. Welches erste Thema: Silbenlesen, Grundwortschatz (die 500 häufigsten Wörter), Artikel?
4. Prototyp-Test Web gegen nativ auf zwei Altgeräten.
5. Lizenzentscheidung Code und Inhalte.

---

## Quellen

Preise und Lizenzen
- ANTON Schullizenz, Bestellunterlagen: https://files.anton.app/files/ANTON-Schullizenz-Bestellunterlagen-DE.pdf
- ANTON Marktplatz-FAQ: https://anton.app/de/faq/43v8wd/marktplatz/
- Oriolus Preisübersicht: https://www.oriolus.de/preise/preisuebersicht.html und https://www.oriolus.de/oriolus_fuer_schulen/oriolus_fuer_schulen.php
- Lernwerkstatt Sammelbestellung (2020): https://grundschule.muenchberg.de/wp-content/uploads/2020/03/Sammelbestellung-Lernwerkstatt-10-18.03.2020.pdf
- bettermarks Landeslizenz Berlin (1,1 Mio. €): https://pardok.parlament-berlin.de/starweb/adis/citat/VT/18/SchrAnfr/S18-27464.pdf
- bettermarks Rheinland-Pfalz: https://bildung.rlp.de/fileadmin/user_upload/mint.bildung.rlp.de/2026/Unterstuetzunsmassnahmen/bettermarks.pdf
- bettermarks Niedersachsen: https://www.landtag-niedersachsen.de/Drucksachen/Drucksachen_19_02500/00001-00500/19-00467.pdf
- Marktplatz Lernapps Österreich (26 € pro Kind): https://oead.at/de/bildung-digital/marktplatz-lernapps/fuer-schulen-1
- Bayerischer Landtag zu abonnementbasierten Lern-Apps: https://www.bayern.landtag.de/www/ElanTextAblage_WP19/Drucksachen/Basisdrucksachen/0000000500/0000000708.pdf
- Startchancen NRW Budget: https://www.news4teachers.de/2025/02/ministerium-gibt-startchancen-katalog-heraus-aus-dem-sich-schulen-bedienen-duerfen/
- Samsung Chancentablet: https://www.news4teachers.de/2025/02/guter-start-dank-individueller-foerderung-samsung-unterstuetzt-das-startchancen-programm-mit-dem-chancentablet-fuer-grundschulen/
- Lernserver und Startchancen: https://www.news4teachers.de/2024/08/lernserver-rundum-angebot-fuer-die-lese-rechtschreibfoerderung-passgenau-auch-zum-startchancen-programm/
- Lernserver Bremen Landeslizenz: https://www.news4teachers.de/2023/10/gute-resultate-in-der-rechtschreibfoerderung-erzielt-bremen-arbeitet-mit-dem-lernserver-tool-fuer-schulen/
- Meister Cody für Lehrkräfte: https://files.meistercody.com/ferdi/Info_Foerderung_fuer_Lehrkraefte.pdf
- Namagi (LMU): https://lmu-klinikum.de/kinder-und-jugendpsychiatrie/forschung/projekte/namagi/ed5ed14ff73e2324
- dBildungscloud Kosten Thüringen: https://parldok.thueringer-landtag.de/ParlDok/dokument/97836

Datenschutz
- ANTON Sicherheitslücke: https://www.it-daily.net/shortnews/keine-probleme-bei-lern-app-anton-bekannt und https://www.familie.de/schulkind/anton-app-hatte-sicherheitsluecken-was-ihr-jetzt-tun-koennt/
- LearningApps Rechtliches: https://learningapps.org/rechtliches.php
- LearningApps Schülerkonten abgeschaltet: https://datenschutz-schule.info/tag/learningapps/
- Khan Academy Kids DSGVO-Hinweise (KA Deutsch e.V.): https://docs.google.com/document/d/11oUZsF66-gPIQMCKVEz_o1cP37xjY4zO/export?format=pdf

Offene Projekte
- Levumi Handbuch: https://epub.ub.uni-muenchen.de/107880/1/Levumi_Handbuch.pdf
- Levumi Quellcode: https://github.com/muehling/LeVuMi
- Levumi OER-Lesepaket (Junger et al. 2023): https://www.pedocs.de/volltexte/2023/27746/pdf/Junger_et_al_2023_Digitale_alltagsintegrierte_Foerderdiagnostik.pdf
- quop Hessen: https://starweb.hessen.de/cache/DRS/19/6/05116.pdf
- GCompris: https://github.com/kde/gcompris und https://www.computerbase.de/2023-01/kinder-lernsoftware-gcompris-3-0/
- Kolibri: https://www.learningequality.org/kolibri/ und https://github.com/learningequality/kolibri
- Serlo: https://www.bildungsserver.de/bildung+innovation/eine-lernplattform-die-allen-gehoert-und-bei-der-alle-mitmachen-koennen-966.html
- H5P offline mit Lumi: https://lumi.education/en/lumi-h5p-offline-desktop-editor/
- Schulcloud-Verbund: https://www.mk.niedersachsen.de/startseite/aktuelles/presseinformationen/niedersachsen-brandenburg-und-thuringen-vereinbaren-weiterentwicklung-der-schulcloud-verbund-software-215207.html

Standards und Infrastruktur
- VIDIS: https://fwu.de/wp-content/uploads/2023/09/230918_FWU_PM_VIDIS_Inbetriebnahmephase_final.pdf und https://tu-dresden.de/zlsb/die-einrichtung/news/vidis-workshop-mit-dem-schullogin-team-am-zlsb
- mundo / SODIX: https://www.friedrich-verlag.de/friedrich-plus/schule-paedagogik/digitale-schule/digitalisierung-gesellschaft/open-educational-resources-14293
- AMB Metadatenprofil (Serlo API): https://github.com/serlo/documentation/wiki/Metadata-API-development
- QTI Versionen: https://www.1edtech.org/standards/qti/versions
- xAPI und adaptive Systeme: https://www.academia.edu/161255513/Implementing_an_Adaptive_Learning_System_with_the_Use_of_Experience_API
- FSRS: https://pypi.org/project/fsrs und https://pub.dev/packages/fsrs/example
- Jamf: Web Clips auf Shared iPads: https://support.jamf.com/en/articles/11020888-deploying-web-clips-to-shared-ipad-in-jamf-school und https://community.jamf.com/general-discussions-2/install-a-pwa-via-jamf-school-48236
