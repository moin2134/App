# GGAF Quizzes! – Going green and Fair

//App oder Inhalte sind teilweise mithilfe KIs gemacht. Dies ist nur ein projekt für Freizeit, Spaß und unsere AG.

Die Lern-App der **AG „Going green und fair“ am MMG**. Mit kurzen Quiz-Lektionen im Stil von Duolingo lernen Schüler*innen alles über Klima, fairen Handel, Umwelt und Nachhaltigkeit. Begleitet werden sie von **Sprossi**, dem Pflanzen-Maskottchen.

- **Web-App:** https://moin2134.github.io/App/
- **Android-App herunterladen (immer die neueste Version):** https://github.com/moin2134/App/raw/main/GGAF-Quizzes.apk
- **iPhone:** als Web-App über „Zum Home-Bildschirm“
- **Feedback an die AG:** https://ggaf-2.jimdosite.com/feedback/

---

## Inhalt

- [Funktionen](#funktionen)
- [Versteckte Überraschungen](#versteckte-überraschungen-easter-eggs)
- [Lerninhalte](#lerninhalte)
- [Installation](#installation)
- [Daten und Fortschritt sichern](#daten-und-fortschritt-sichern)
- [App teilen](#app-teilen)
- [Projektordner](#projektordner)
- [App bearbeiten und neu bauen](#app-bearbeiten-und-neu-bauen)
- [Fakten aktuell halten](#fakten-aktuell-halten)
- [Technik](#technik)
- [Lizenzen und Quellen](#lizenzen-und-quellen)
- [Alle Fragen](#alle-fragen)

---

## Funktionen

### Lernen
- **Lernpfad:** 15 Einheiten mit je 3 Lektionen und einem Einheitstest, dazu das **MMG-Special** zur AG. Die Stationen werden nacheinander freigeschaltet.
- **Infotexte:** Vor jeweils zwei Lektionen steht ein Infotext mit allem, was man für die nächsten Aufgaben wissen muss. Gelesene Texte bekommen einen Haken.
- **Fünf Aufgabentypen:** Antwort wählen, Stimmt/Stimmt nicht, Lücke füllen, Reihenfolge sortieren, Paare finden.
- **„Wusstest du?“:** Nach jeder Antwort gibt es eine kurze Erklärung mit einem zusätzlichen Fakt.
- **Wiederholung:** Falsche Aufgaben kommen am Ende der Lektion im **rot-orangen Wiederholungs-Look** zurück.
- **Einführung:** Beim ersten Start erklären 8 Schritte die App. Sie lässt sich unter Einstellungen (Zahnrad) erneut ansehen.

### Üben
Ganz oben steht der **Tipp des Tages** (ein Alltagstipp für mehr Nachhaltigkeit). Darunter ist „Üben“ in vier Bereiche sortiert:

| Bereich | Modus | Beschreibung |
|---|---|---|
| **Trainieren** | **Gemischtes Training** | 8 Fragen aus den freigeschalteten Einheiten, bringt +1 Herz |
| | **Wiederholen mit Abstand** | Gelernte Fragen kommen nach 1, 3, 7, 14 und 30 Tagen wieder |
| | **Fehler wiederholen** | Alle bisher falsch beantworteten Fragen |
| | **Blitzrunde** | 60 Sekunden, so viele richtige Antworten wie möglich, mit Rekord |
| **Wissen & Spaß** | **Schätzen & Mythen** | 4 Schätzfragen mit Schieberegler (je näher, desto mehr XP, bis 3 pro Frage) und 6 Aussagen „Wahr oder Mythos?“ zu verbreiteten Umwelt-Irrtümern, gemischt |
| | **Klima-Check** | 6 Alltagsfragen mit persönlichen Tipps (grobe Einschätzung, keine genaue CO₂-Rechnung) |
| | **Lexikon** | 45 Fachbegriffe von „Agenda 2030“ bis „Zero Waste“, mit Suche |
| **Prüfung & Klasse** | **Abschlussprüfung** | 30 zufällige Fragen aus allen Einheiten, ohne Herzen und ohne Wiederholung. Ergebnis als Schulnote (1 ab 92 %, 2 ab 81 %, 3 ab 67 %, 4 ab 50 %, 5 ab 30 %). Ab Note 4 gibt es eine eigene Urkunde im Profil; die beste Note wird gespeichert |
| | **Klassen-Modus (Beamer)** | Eine ganze Einheit gemeinsam am Beamer: große Schrift, ohne Herzen, zählt nicht für den eigenen Fortschritt |
| **Mitmachen** | **Frage vorschlagen** | siehe „Feedback“ |

### Bilderrätsel in den Einheiten
18 selbst gezeichnete Bilderfragen (SVG, ohne fremde Fotos oder Marken-Logos) stecken direkt in den passenden Einheiten – höchstens 2 pro Lektion, der Rest im Einheitstest:
- **Klima & Energie:** Windrad, Solaranlage, LED-Lampe
- **Müll & Recycling:** Joghurtbecher, Zeitung, Bananenschale, Batterie, Glasflasche, kaputte Tasse, Kassenbon
- **Wasser & Ozeane:** Wasserkreislauf, tropfender Hahn, Schildkröte mit Plastiktüte
- **Artenvielfalt:** Biene · **Mode & Konsum:** Energielabel, Baumwoll-T-Shirt · **Mobilität:** Fahrrad · **Wald & Moore:** Moor

### Barrierearm lernen
- **Vorlesen:** Ein Lautsprecher-Button liest Frage und Antworten bzw. Infotexte in der gewählten Sprache vor. Im Browser über die Sprachausgabe des Geräts, in der Android-App über die Handy-Sprachausgabe (Latein mit italienischer Stimme, Bairisch mit deutscher, Schweizerdeutsch mit Schweizer Stimme, falls vorhanden).
- **Einfacher Modus (Unterstufe):** Unter **Einstellungen** (Zahnrad oben rechts). Dann gibt es nur 3 statt 4 Antworten und einen **Tipp-Button**, der eine falsche Antwort durchstreicht. Die Fragen selbst bleiben gleich – es ist keine „Leichte Sprache“ im engen Sinn.

### Arbeitsblätter
Im Ordner `Arbeitsblaetter/` liegt für jede Einheit und das MMG-Special ein **PDF zum Ausdrucken** (z. B. für Vertretungsstunden): Infotexte, alle 18 Aufgaben (Ankreuzen, Lückentext mit Wortliste, Nummerieren, Zuordnen) und eine **Lösungsseite** für die Lehrkraft. Neu erzeugen: `jwebserver` im Ordner `web/` starten, `android/arbeitsblatt-vorlage.html` nach `web/` kopieren und `blatt.html?u=0` … `?u=14` (MMG-Special: `?u=-1`) mit Edge als PDF drucken.

### Sprachen
Die komplette App gibt es in **18 Sprachen**: Fragen, Infotexte, Lexikon, Tipps, Einführung und alle Bedienelemente. In der Auswahl stehen die wichtigsten Sprachen oben, Dialekte, alte Sprachen und Schriften unten.

| Sprache | Code | Hinweis |
|---|---|---|
| Deutsch | `de` | Original |
| English | `en` | britisches Englisch |
| Français | `fr` | |
| Español | `es` | Spanisch (Spanien) |
| Italiano | `it` | |
| Polski | `pl` | |
| Русский | `ru` | kyrillische Schrift |
| Українська | `uk` | kyrillische Schrift |
| Português | `pt` | europäisches Portugiesisch |
| Nederlands | `nl` | |
| Čeština | `cs` | |
| עברית (Hebräisch) | `he` | wird von rechts nach links angezeigt |
| Boarisch | `bar` | gemäßigtes Oberbairisch |
| Schwiizerdütsch | `gsw` | Zürichdeutsch als Basis |
| Latina | `la` | Schullatein, moderne Begriffe teils in Anführungszeichen |
| Ἑλληνική (Altgriechisch) | `grc` | Schul-Altgriechisch mit Akzenten; moderne Begriffe umschrieben, Zahlen als normale Ziffern |
| Hieroglyphen | `egy` | Spaß-Sprache wie die Keilschrift: der deutsche Text wird mit den ägyptischen **Einkonsonantenzeichen** („Hieroglyphen-Alphabet“) umgeschrieben – keine Übersetzung ins Altägyptische. Schrift: Noto Sans Egyptian Hieroglyphs (nur die 23 benötigten Zeichen, 10 KB). Vorlesen ist hier aus. |
| Keilschrift | `cun` | Spaß-Sprache: der deutsche Text wird Buchstabe für Buchstabe ins **ugaritische Keilschrift-Alphabet** (um 1400 v. Chr.) umgeschrieben – keine echte Übersetzung ins Sumerische/Akkadische. Schrift: Noto Sans Ugaritic. Vorlesen ist hier aus. |

- **Auswahl:** Die Sprache wählt man gleich im **ersten Schritt der Einführung** oder später unter **Einstellungen** (Zahnrad oben rechts). Der Fortschritt bleibt beim Wechsel erhalten.
- **Ansicht (PC & Tafel):** Im ersten Schritt der Einführung (unter der Sprache) und in den Einstellungen: **Automatisch** (ab 1000 Pixel Breite breites Layout), **Handy** (immer schmal) oder **PC & Tafel** (immer breit: bis 1100 Pixel, größere Schrift, Karten zweispaltig, Antworten nebeneinander – gut für Beamer und digitale Tafeln).
- **Mehrzahlformen:** Polnisch, Tschechisch, Russisch und Ukrainisch nutzen die richtigen drei Mehrzahlformen (z. B. 1 den / 2 dny / 5 dní).

- **Übersetzungen:** Sie stecken in `index.html` in `CONTENT_PACKS` (Inhalte) und `I18N` (Bedienelemente).
- **Neue deutsche Fragen:** Werden deutsche Fragen geändert oder ergänzt, müssen die Übersetzungen nachgezogen werden. Fehlt eine Übersetzung, zeigt die App automatisch den deutschen Text.

### Feedback
- **Frage melden:** Unter jeder Rückmeldung steht „Frage falsch oder unklar? Melden“. Die App zeigt die Angaben zur Frage zum Kopieren an und öffnet das Feedback-Formular der AG.
- **Feedback geben:** Im Profil führt ein Button direkt zum Formular.
- **Frage vorschlagen:** Unter Üben und im Profil. Schüler*innen tragen Thema, Frage, richtige und falsche Antworten, Quelle und (freiwillig) Name/Klasse ein. Die App kopiert alles und öffnet das Feedback-Formular. Gute Vorschläge kann die AG mit Namen in die App aufnehmen.

### Datenschutz
- Kein Konto, keine Werbung, kein Tracking. Alle Daten bleiben auf dem Gerät.
- **Browserdaten löschen:** Einstellungen → App & Daten → „Browserdaten löschen“ entfernt nach einer Rückfrage alles, was die App im Browser gespeichert hat (Fortschritt, Einstellungen, Sitzungsdaten, Offline-Speicher und Service Worker) und startet die App neu wie beim ersten Mal. „Fortschritt zurücksetzen“ setzt dagegen nur den Spielstand zurück.
- Die Web-Version lädt **keine Google-Schriften** mehr: Baloo 2 und Nunito liegen im Ordner `web/fonts/`.
- **Einstellungen → App & Daten → Datenschutz & Impressum** zeigt die Hinweise. Die Kontaktdaten fürs Impressum stehen in `index.html` in der Konstante `LEGAL` (Name, verantwortliche Person, Anschrift, E-Mail) und müssen noch eingetragen werden.

### Motivation
- **XP** für jede Lektion (Lektion 10 XP, Einheitstest 20 XP, +5 bei fehlerfreien Runden)
- **Tagesziel** (10, 20, 30 oder 50 XP) mit Fortschrittsbalken in Sprossis Sprechblase
- **Serie:** Wer jeden Tag lernt, baut seine Serie aus, die Flamme flackert.
- **Herzen:** Jeder Fehler in einer Lektion kostet ein Herz. Alle 30 Minuten kommt eins zurück.
- **14 Abzeichen**, z. B. „Erster Spross“, „Wochenfeuer“, „Fair-Profi“, „AG-Profi“, „Going green and Fair“
- **Wochenrückblick:** XP, Lektionen, aktive Tage, stärkstes Thema und „Übe mehr“, im Profil und zu Beginn jeder Woche
- **Garten:** Im Profil hat jede Einheit (und das MMG-Special) ein Beet. Erdhügel = noch nicht begonnen, Keimling = begonnen, Blume in der Farbe der Einheit = Einheitstest bestanden. Sprossi selbst bleibt immer gleich groß.
- **Urkunden:** für alle Einheiten und für das MMG-Special, als Bild mit Namen, Datum und XP. In der Web-App herunterladen, in der Android-App teilen oder speichern.

### Shop
Verdiente XP lassen sich ausgeben. Abzeichen zählen trotzdem alle jemals verdienten XP.

| Kategorie | Artikel |
|---|---|
| Hilfen | Ein Herz (10 XP), Herzen auffüllen (30 XP), Serienschutz (50 XP, max. 2), Doppel-XP (40 XP) |
| Outfits für Sprossi | Fliege (50), Sonnenbrille (60), Sonnenhut (70), Wollmütze (80), Kopfhörer (90), Blumenkranz (100), MMG-Cap (120), Krone (200) |
| Hintergründe | Tupfen (40), Streifen (50), Blätterregen (70) |

### Gestaltung
- Farbschema der AG: Dunkelgrün `#2E6417`, Grün `#00BF63`, Hellgrün `#7ED957`, Limette `#C1FF72`, Mint `#D9F2CA`
- **Einstellungen (Zahnrad oben rechts):** Sprache, Design, Soundeffekte, einfacher Modus, Einführung, Fortschritt sichern, Datenschutz, Zurücksetzen und App-Infos an einem Ort.
- **Heller und dunkler Modus:** unter Einstellungen → Design wählbar: Automatisch (wie das Gerät), Hell oder Dunkel
- **Link-Vorschau:** Beim Teilen des Links (WhatsApp, Signal …) erscheint ein Vorschaubild mit Sprossi
- **Animationen:** Sprossi winkt, blinzelt und wiegt seine Blätter, richtige Antworten „ploppen“, Zahlen hüpfen. Bei „Bewegung reduzieren“ in den Systemeinstellungen sind die Animationen aus.
- **Hinweise:** Ohne Internet erscheint „Du bist offline – die App funktioniert trotzdem“. Liegt eine neue Version auf GitHub, zeigt die Web-App „Neue Version geladen – Neu laden“.
- Unten rechts: **MMG · GGAF Quizzes! App · Going green and Fair**

---

## Versteckte Überraschungen (Easter Eggs)

> Spoiler! Nicht an alle verraten 😉. Alle Überraschungen funktionieren offline und speichern keine zusätzlichen Daten (nur, ob man sie schon gefunden hat).

| # | Überraschung | So findet man sie |
|---|---|---|
| 1 | **Sprossi kitzeln** | 7-mal schnell hintereinander auf das kleine Sprossi-Logo oben links tippen. Sprossi dreht sich, kichert und sagt einen Spruch. |
| 2 | **Geheime Namen** | Im Profil (oder in der Einführung) als Namen **„Sprossi“** eingeben → Sprossi wundert sich über seinen Doppelgänger. Name **„MMG“** → Konfetti in den AG-Farben. Das Feld muss danach verlassen werden (woanders hintippen). |
| 3 | **Konami-Code** | Auf einer Tastatur (PC) **↑ ↑ ↓ ↓ ← → ← → B A** drücken → Blätterregen. |
| 4 | **Nachteule 🦉** | Eine Lektion zwischen Mitternacht und 5 Uhr beenden → geheimes Abzeichen. |
| 5 | **Besondere Tage** | **22. April (Earth Day):** Sprossi hält eine kleine Weltkugel. **24.–26. Dezember:** Sprossi trägt eine rote Mütze. **31. Dezember und 1. Januar:** Konfetti beim Start. Jeweils mit Gruß; das Outfit erscheint nur, wenn Sprossi gerade nichts anderes trägt. |
| 6 | **Blitzableiter ⚡** | In der Blitzrunde 25 oder mehr richtige Antworten → geheimes Abzeichen. |
| 7 | **Schmetterlinge** | Wenn im Garten (Profil) alle 16 Blumen blühen, fliegen Schmetterlinge darüber. |
| 8 | **Spaßfrage** | Ganz selten (etwa jede 200. Lektion, Training oder Wiederholung) taucht eine Spaßfrage über Sprossi auf. Richtig beantwortet: +5 Bonus-XP. Falsch kostet kein Herz. |
| 9 | **Rückwärts-Sprossi** | In der Einführung lange (knapp 1 Sekunde) auf Sprossi drücken → er steht kurz auf dem Kopf: „Huch!“ |
| 10 | **Geheimes Outfit** | Wer **„fair“** irgendwo im Namen hat (z. B. „Fairy“), bekommt das **Fair-Stirnband** gratis. Es erscheint danach im Shop unter Outfits. Ohne echtes Fairtrade-Logo. |
| 11 | **Herzen-Trick** | Unter „Erfolge“ 3-mal schnell auf das Abzeichen **„Sprossi-Stylist“** tippen → alle 5 Herzen sind wieder voll. Einmal pro Tag. |
| 12 | **XP-Trick** | Unter „Erfolge“ 3-mal schnell auf das Abzeichen **„Erster Einkauf“** tippen → +100 XP. Einmal pro Tag. |

Geheime Abzeichen stehen erst nach dem Freischalten in der Liste; oben steht nur „🔒 2 × ???“ – so viele sind noch versteckt. Im Code steht alles im Abschnitt `Easter Eggs` sowie in `EGG_DE` (Texte) und `EGG_TR` (Übersetzungen).

---

## Lerninhalte

**288 Fragen** in 16 Bereichen. Jede Einheit hat 18 Fragen: 6 pro Lektion, der Test mischt aus allen.

| # | Einheit | Thema |
|---|---|---|
| ★ | **MMG-Special: AG „Going green und fair“** | Die AG & BNE · Change Fashion & Weltladen · Handys & MMG-Hefte |
| 1 | Klima & Energie | Treibhausgase, Strom und warum jedes Grad zählt |
| 2 | Fairer Handel | Wer verdient an deiner Schokolade – und was Siegel bedeuten |
| 3 | Müll & Recycling | Vermeiden, trennen, wiederverwenden |
| 4 | Umweltpolitik in Deutschland | Ministerien, Gesetze und der CO₂-Preis |
| 5 | Die neue Bundesregierung & die Umwelt | Was sich seit Mai 2025 in der Klimapolitik tut |
| 6 | Wasser & Ozeane | Virtuelles Wasser, Plastik im Meer und Korallen |
| 7 | Essen & Klima | Saisonal, regional und nichts verschwenden |
| 8 | Artenvielfalt | Bienen, Moore und warum Totholz lebt |
| 9 | Mode & Konsum | Fast Fashion, Smartphones und Reparieren |
| 10 | Globale Gerechtigkeit | Die 17 Ziele, Klimagerechtigkeit und faire Chancen |
| 11 | Mobilität & Verkehr | Auto, Rad, Bahn und die Verkehrswende |
| 12 | Digitales & Klima | Streaming, Rechenzentren, KI und E-Schrott |
| 13 | Kinderrechte | Deine Rechte – in der Schule, online und weltweit |
| 14 | Wald & Moore in Bayern | Wälder im Klimawandel und Moore als Klimaschützer |
| 15 | Deutschland: Energie & Klima in Zahlen | Emissionen, Ökostrom und Bayerns Solarboom |

Alle Fakten wurden mit Quellen geprüft, u. a. Umweltbundesamt, Destatis, Bundesregierung, ILO/UNICEF, IPBES, Weltbank, Fraunhofer ISE. Die politischen Einheiten sind **neutral** formuliert und fragen Fakten ab, keine Meinungen. **Faktenstand: September 2026.**

---

## Installation

Es gibt drei Wege, GGAF Quizzes! zu nutzen. Alle drei sind **kostenlos**, brauchen **kein Konto** und funktionieren nach dem ersten Laden auch **ohne Internet**.

| Gerät | Empfohlener Weg | Dauer |
|---|---|---|
| Android-Handy/-Tablet (ab Android 7) | [A) Android-App (APK)](#a-android-app-apk-installieren) | ca. 2 Minuten |
| iPhone / iPad | [B) Web-App auf den Home-Bildschirm](#b-iphone-und-ipad-web-app) | ca. 1 Minute |
| Windows-PC / -Laptop (Windows 10/11) | [E) Windows-App](#e-windows-app) oder Browser | ca. 1 Minute |
| PC, Laptop, Chromebook, digitale Tafel | [C) Im Browser öffnen oder installieren](#c-pc-laptop-und-digitale-tafel) | sofort |

> **Tipp für alle:** Vor einem Gerätewechsel unter **Einstellungen (Zahnrad) → Fortschritt sichern** einen Sicherungscode erstellen. Damit zieht der Fortschritt aufs neue Gerät um – auch zwischen Android-App und Web-App.

### A) Android-App (APK) installieren

**Was du brauchst:** ein Android-Handy oder -Tablet ab Android 7 (2016), gut 2 MB freien Speicher und einmal Internet zum Herunterladen.

**1. App-Datei herunterladen** – eine der drei Möglichkeiten:
- **Direkt:** Auf dem Handy diesen Link öffnen: **https://github.com/moin2134/App/raw/main/GGAF-Quizzes.apk**. Chrome zeigt eventuell „Datei kann schädlich sein“ – das kommt bei allen App-Dateien außerhalb des Play Stores; auf **„Trotzdem herunterladen“** tippen.
- **Von Freund*innen:** Wer die App schon hat, tippt unter **Profil → Freunde einladen → App teilen** und schickt die Datei per WhatsApp, Signal, Bluetooth, E-Mail …
- **Per QR-Code im selben WLAN:** Wer die App hat, tippt auf **„QR-Code im selben WLAN“**. Du scannst den Code mit der Kamera und lädst die Datei direkt vom anderen Handy – ganz ohne Internet.

**2. Datei öffnen:** Nach dem Download oben die Benachrichtigung antippen – oder die App **„Dateien“ / „Eigene Dateien“** öffnen → **Downloads** → **GGAF-Quizzes.apk** antippen.

**3. Installation erlauben (nur beim ersten Mal):** Android fragt, ob die App, mit der du die Datei öffnest (z. B. Chrome, WhatsApp oder „Dateien“), Apps installieren darf.
- Auf **„Einstellungen“** tippen → Schalter **„Von dieser Quelle zulassen“** einschalten → zurück.
- **Android 7:** unter **Einstellungen → Sicherheit → „Unbekannte Herkunft“** einschalten.
- **Samsung:** Einstellungen → Biometrie und Sicherheit → Unbekannte Apps installieren. **Xiaomi:** Einstellungen → Datenschutz → Spezielle Berechtigungen → Unbekannte Apps installieren.

**4. Installieren:** Auf **„Installieren“** tippen. Falls **Google Play Protect** warnt („App nicht bekannt“): **„Details“ → „Trotzdem installieren“**. Die App ist nicht im Play Store, deshalb kennt Google sie nicht. Sie hat keinen Zugriff auf Kontakte, Fotos, Standort oder Kamera – nur Internet für Links und das Teilen im WLAN.

**5. Starten:** Auf **„Öffnen“** tippen oder das grüne Sprossi-Symbol auf dem Startbildschirm suchen. Beim ersten Start führt die Einführung durch Sprache, Ansicht, Name und Tagesziel.

**Updates kommen automatisch:** Ab Version 3.9 schaut die App bei jedem Start im Hintergrund auf https://moin2134.github.io/App/, ob es neue Inhalte gibt (Versionsnummer `APP_VERSION`). Wenn ja, lädt sie die neue Version (und fehlende Schriften) in den App-Speicher und zeigt „Neue Version geladen – Neu laden“; spätestens beim nächsten Start ist sie aktiv. Ohne Internet läuft die zuletzt geladene Version weiter, der Fortschritt bleibt erhalten. Für die AG heißt das: `web/index.html` auf GitHub hochladen genügt. Eine **neue APK** ist nur nötig, wenn sich der Java-Teil der App ändert (z. B. Teilen, Vorlesen, Update-Funktion) – dann die neue APK genauso herunterladen und **über die alte drüber** installieren, nicht vorher deinstallieren. Die Version des App-Rahmens steht unter **Einstellungen → ganz unten**.

**Deinstallieren:** Sprossi-Symbol lange drücken → **„Deinstallieren“**. Dabei wird auch der Fortschritt gelöscht – vorher einen Sicherungscode erstellen!

### B) iPhone und iPad (Web-App)

Für iPhone und iPad gibt es keine App-Datei: Eine echte iOS-App bräuchte einen Mac, ein kostenpflichtiges Apple-Entwicklerkonto und den App Store. Die **Web-App** fühlt sich aber genauso an – eigenes Symbol, Vollbild, offline nutzbar.

1. **Safari** öffnen (wichtig: Safari – andere Browser können das unter iOS erst ab iOS 16.4 und nicht zuverlässig).
2. **https://moin2134.github.io/App/** eingeben und warten, bis die App geladen ist.
3. Unten (iPhone) bzw. oben rechts (iPad) auf **Teilen** tippen – das Quadrat mit dem Pfeil nach oben.
4. In der Liste nach unten wischen und **„Zum Home-Bildschirm“** wählen. Fehlt der Eintrag: ganz unten **„Aktionen bearbeiten“** → „Zum Home-Bildschirm“ hinzufügen.
5. Den Namen „GGAF Quizzes!“ lassen und oben rechts **„Hinzufügen“** tippen.
6. Ab jetzt die App immer über das neue **Sprossi-Symbol** starten – nicht über Safari. Nur so bleibt der Fortschritt zuverlässig gespeichert.

**Wichtig bei iPhones:** Safari löscht Daten von Webseiten, die mehrere Wochen nicht geöffnet wurden. Am sichersten: die App regelmäßig öffnen und ab und zu einen **Sicherungscode** erstellen. Im **privaten Modus** speichert Safari gar nichts – die App zeigt dann einen Hinweis.

**Updates** passieren automatisch: Liegt eine neue Version auf GitHub, erscheint beim nächsten Öffnen „Neue Version geladen – Neu laden“.

### C) PC, Laptop und digitale Tafel

1. Im Browser (Chrome, Edge, Firefox, Safari) **https://moin2134.github.io/App/** öffnen – fertig.
2. **Optional als App installieren** (eigenes Fenster, Symbol im Startmenü bzw. Dock, offline):
   - **Chrome / Edge:** rechts in der Adressleiste auf das Symbol **„App installieren“** (Bildschirm mit Pfeil) klicken – oder im Menü ⋮ unter **„Streamen, speichern und teilen“ → „Seite als App installieren“** (Edge: **Apps → „Diese Website als App installieren“**).
   - **Safari (Mac, ab macOS 14):** Menü **Ablage → „Zum Dock hinzufügen“**.
   - **Firefox:** kann Web-Apps nicht installieren – einfach als Lesezeichen speichern.
3. **Für Beamer und digitale Tafeln:** unter **Einstellungen → Ansicht → „PC & Tafel“** wählen (große Schrift, Antworten nebeneinander). Mit **F11** wird der Browser zum Vollbild. Für eine gemeinsame Runde mit der Klasse: **Üben → Klassen-Modus (Beamer)**.
4. **Schul-PCs mit gemeinsamen Konten:** Der Fortschritt hängt am Browser-Profil. Wird das Profil beim Abmelden gelöscht, ist der Fortschritt weg – dann am Stundenende einen Sicherungscode erstellen oder am Handy weiterlernen.

### E) Windows-App

Für Windows 10 und 11 (64 Bit) gibt es eine eigene App mit Fenster, Sprossi-Symbol und ohne Browserleiste. Sie funktioniert komplett **offline**.

1. **GGAF-Quizzes-Windows.zip** herunterladen: **https://github.com/moin2134/App/raw/main/GGAF-Quizzes-Windows.zip**
2. Die ZIP-Datei mit Rechtsklick → **„Alle extrahieren …“** entpacken, z. B. nach *Dokumente* oder *Programme*. (Nicht direkt aus der ZIP starten – dann fehlen die anderen Dateien.)
3. Im entpackten Ordner **GGAF-Quizzes** die Datei **GGAF-Quizzes.exe** doppelklicken.
4. Windows zeigt eventuell **„Der Computer wurde durch Windows geschützt“** (SmartScreen), weil die App nicht bei Microsoft signiert ist: auf **„Weitere Informationen“ → „Trotzdem ausführen“** klicken. Das ist nur beim ersten Start nötig.
5. **Verknüpfung anlegen:** Rechtsklick auf *GGAF-Quizzes.exe* → **„Weitere Optionen anzeigen“ → „Senden an“ → „Desktop (Verknüpfung erstellen)“**. Oder die gestartete App in der Taskleiste mit Rechtsklick **„An Taskleiste anheften“**.

**Gut zu wissen:**
- **F11** schaltet Vollbild an und aus – ideal für Beamer und digitale Tafeln (dazu *Einstellungen → Ansicht → „PC & Tafel“*).
- Links (Feedback-Formular, GitHub) öffnen sich im normalen Browser.
- Der Fortschritt liegt unter `%LOCALAPPDATA%\GGAF-Quizzes` und bleibt bei Updates erhalten. Er ist getrennt von der Web-App im Browser – zum Umziehen einen **Sicherungscode** nutzen.
- **Automatische Updates:** Bei jedem Start schaut die App im Hintergrund auf https://moin2134.github.io/App/, ob dort eine neuere Version liegt (Versionsnummer `APP_VERSION`, kommt aus `versionName` in `android/AndroidManifest.xml`). Wenn ja, lädt sie die neue `index.html` (und fehlende Schriften) nach `%LOCALAPPDATA%\GGAF-Quizzes\app` und zeigt „Neue Version geladen – Neu laden“. Ohne Internet läuft die zuletzt geladene Version weiter. Für Updates reicht es also, `web/index.html` auf GitHub hochzuladen; eine neue ZIP braucht es nur, wenn sich das Windows-Programm selbst ändert.
- **Smart App Control (Windows 11):** Ist auf einem PC „Intelligente App-Steuerung“ eingeschaltet (Windows-Sicherheit → App- & Browsersteuerung), blockiert Windows unsignierte Programme wie dieses ohne „Trotzdem ausführen“-Knopf. Auf solchen PCs die App stattdessen **über Edge installieren** (siehe C: „Diese Website als App installieren“) – das sieht fast genauso aus und aktualisiert sich ebenfalls selbst. Dauerhaft lösen ließe sich das nur mit einer Code-Signatur oder über den Microsoft Store.
- **Deinstallieren:** den Ordner löschen; wer auch den Fortschritt löschen will, zusätzlich `%LOCALAPPDATA%\GGAF-Quizzes`.
- Benötigt die **Microsoft Edge WebView2 Runtime**. Die ist bei Windows 10/11 normalerweise schon installiert. Falls nicht, bietet die App beim Start die Download-Seite von Microsoft an.
- **Neu bauen:** erst `android/build.ps1`, dann `powershell -ExecutionPolicy Bypass -File windows/build.ps1`. Das nutzt den in Windows eingebauten C#-Compiler (.NET Framework 4) und die WebView2-Dateien in `windows/lib`.

### D) Probleme und Lösungen

| Problem | Lösung |
|---|---|
| „App nicht installiert“ (Android) | Meist ist eine ältere Version mit anderer Signatur installiert oder der Speicher ist voll. Sicherungscode erstellen, alte Version deinstallieren, neu installieren. Oder der Download ist unvollständig – erneut laden. |
| „Parse-Fehler“ / „Paket ungültig“ | Android-Version zu alt (unter 7) oder Download abgebrochen. Datei erneut herunterladen. |
| Knopf „Installieren“ reagiert nicht | Ein Bildschirmfilter (Blaulichtfilter, Chat-Bubbles) liegt darüber – kurz ausschalten. |
| Leere weiße Seite in der Web-App | Seite neu laden. Hilft das nicht: **Einstellungen → App & Daten → „Browserdaten löschen“** (vorher Sicherungscode!) oder im Browser die Website-Daten löschen. |
| Fortschritt ist weg | Im privaten Modus gespielt oder Browserdaten gelöscht? Mit einem Sicherungscode unter **Einstellungen → Fortschritt sichern → „Sicherungscode einfügen“** zurückholen. |
| Kein Ton | **Einstellungen → Soundeffekte** einschalten und das Gerät nicht auf lautlos stellen (iPhone: Stummschalter). |
| Vorlesen geht nicht oder klingt falsch | Das Gerät braucht eine Stimme für die Sprache: Android unter *Einstellungen → Bedienungshilfen → Text-in-Sprache*, iPhone unter *Einstellungen → Bedienungshilfen → Gesprochene Inhalte → Stimmen*. |
| Schrift sehr klein oder abgeschnitten | **Einstellungen → Ansicht** prüfen („Handy“ am Handy, „PC & Tafel“ am großen Bildschirm). Eine sehr große Systemschrift am Handy etwas verkleinern. |
| Windows: „Der Computer wurde durch Windows geschützt“ | „Weitere Informationen“ → „Trotzdem ausführen“ (die App ist nicht bei Microsoft signiert). |
| Windows: App startet nicht / Meldung zu WebView2 | Die angebotene Microsoft-Seite öffnen und die „Evergreen Bootstrapper“-Version der WebView2 Runtime installieren. Außerdem prüfen, ob die ZIP wirklich entpackt wurde. |
| Hebräisch, Altgriechisch, Hieroglyphen oder Keilschrift als Kästchen | Die Seite einmal mit Internet neu laden, damit die Schriften geladen werden. Für die Web-Version muss der Ordner `fonts` auf GitHub liegen. |

---

## Daten und Fortschritt sichern

Der Fortschritt wird **automatisch auf dem Gerät** gespeichert: XP, Serie, Lektionen, Abzeichen, Shop-Käufe und Einstellungen. Es gibt **kein Konto und keinen Server**. Es werden keine Daten verschickt.

**Der Fortschritt geht verloren**, wenn
- die Browserdaten bzw. App-Daten gelöscht werden,
- im privaten bzw. Inkognito-Modus gelernt wird,
- man ein neues Gerät oder einen anderen Browser nutzt.

**Absichern:** Unter **Einstellungen (Zahnrad) → Fortschritt sichern → Sicherungscode erstellen** den Code kopieren und aufbewahren. Mit **„Sicherungscode einfügen“** kommt alles zurück, auch zwischen Web-App und Android-App.

Kann ein Gerät nicht speichern, zeigt die App automatisch einen Hinweis mit Button zum Sicherungscode.

---

## App teilen

In der **Android-App** unter **Profil → Freunde einladen**:
- **App teilen:** schickt die APK mit kurzer Installationsanleitung über WhatsApp, Bluetooth, Quick Share usw.
- **QR-Code im selben WLAN:** Das Handy wird zum kleinen Download-Server. Freund*innen scannen den Code und bekommen eine Seite mit Anleitung und Download-Button.
  - Funktioniert nur, solange die App offen ist.
  - Manche Schul-WLANs blockieren Verbindungen zwischen Geräten. Dann hilft der Handy-Hotspot.

Für die Web-App genügt der Link bzw. ein QR-Code zu https://moin2134.github.io/App/.

---

## Projektordner

```
ProjektGGAF_App/
├── index.html            ← die komplette App (Quelle, hier wird bearbeitet)
├── GGAF-Quizzes.apk      ← fertige Android-App
├── README.md             ← diese Datei
├── FAKTEN-STAND.md       ← Liste aller Zahlen, die jährlich geprüft werden müssen
├── web/                  ← fertige Web-App für GitHub Pages (diese Dateien hochladen!)
│   ├── index.html
│   ├── manifest.json     ← macht die Seite installierbar
│   ├── sw.js             ← Offline-Speicher
│   ├── apple-touch-icon.png, icon-192.png, icon-512.png
│   └── og-image.png      ← Vorschaubild beim Teilen des Links
├── android/              ← Android-Hülle und Build-Skript
│   ├── build.ps1         ← baut APK und web/index.html
│   ├── AndroidManifest.xml
│   ├── src/…             ← Java: WebView, Teilen, QR-Server
│   ├── res/…             ← App-Symbol, Farben, Themes
│   └── assets-extra/     ← Offline-Schriften und QR-Bibliothek
└── Grafiken/             ← alle Grafiken der App (Sprossi, Outfits, Symbole, Hintergründe, App-Symbole)
```

**Wichtig für GitHub:**
- Immer die Dateien aus dem Ordner **`web`** hochladen, nicht die `index.html` aus dem Hauptordner. Die richtige Datei beginnt mit `<!doctype html>`.
- Die aktuelle `GGAF-Quizzes.apk` ebenfalls ins Repository hochladen, **mit genau diesem Dateinamen**. Dann zeigt der Download-Link immer auf die neueste Version.

---

## App bearbeiten und neu bauen

### Inhalte ändern
Alles steht in **`index.html`**:
- Fragen: `UNITS`, `PROFI`, `NEW_UNITS`, `DE_UNITS`, `AG`
- Infotexte: `INFOS`, `INFOS_PROFI`, `NEW_INFOS`, `DE_INFOS`, `INFOS_AG`
- Tipps: `TIPS`
- Einführung: `INTRO`
- Shop: `SHOP`, `OUTFITS`, `BGS`

Aufbau einer Frage:
```js
mc('Frage?', ['richtige Antwort', 'falsch', 'falsch', 'falsch'], 'Erklärung')   // Antwort wählen – die ERSTE ist richtig
tf('Aussage.', true, 'Erklärung')                                            // Stimmt / Stimmt nicht
fill('Satz mit ___ Lücke.', ['richtig', 'falsch', 'falsch', 'falsch'], 'Erklärung')
ord('Sortiere …', ['erstes', 'zweites', 'drittes'], 'Erklärung')             // in richtiger Reihenfolge
pair('Was gehört zusammen?', [['A','1'], ['B','2'], ['C','3'], ['D','4']], 'Erklärung')
```
Jede Einheit braucht **genau 18 Fragen**: 1–6 Lektion 1, 7–12 Lektion 2, 13–18 Lektion 3.

### Neu bauen
Voraussetzungen: Windows, Android SDK (Android Studio) und JDK.

```
powershell -File android/build.ps1
```

Das Skript erzeugt:
- `GGAF-Quizzes.apk` (signiert, installierbar)
- `web/index.html` (für GitHub)
- `web/fonts/` mit den Schriften (einmalig mit auf GitHub hochladen, als Ordner `fonts`)

Vor einer neuen Version:
- In `android/AndroidManifest.xml` den `versionCode` um 1 erhöhen und `versionName` anpassen.
- In `web/sw.js` die Zahl bei `CACHE = 'ggaf-v…'` erhöhen, damit Handys das Update laden.

**Signaturschlüssel:** `android/ggaf-quizzes.jks`, das Passwort steht in `build.ps1`. **Nicht löschen!** Nur mit diesem Schlüssel lassen sich Updates über die installierte App spielen.

---

## Fakten aktuell halten

Zahlen wie Ökostrom-Anteil, Gender Pay Gap, CO₂-Preis oder Erdüberlastungstag ändern sich jedes Jahr, politische Angaben oft noch schneller. In **`FAKTEN-STAND.md`** steht zu jeder betroffenen Frage der Suchtext, der aktuelle Wert und die Quelle.

Einmal pro Schuljahr (am besten im September) und nach Regierungs- oder Gesetzesänderungen prüfen:
1. Werte in `index.html` anpassen.
2. `FACT_STAND` ändern.
3. Neu bauen.

AG-spezifische Angaben (Weltladen, Handysammlung, MMG-Hefte) bitte mit der AG abstimmen.

---

## Technik

- **Eine einzige HTML-Datei** mit CSS und JavaScript, ohne Frameworks und ohne Server
- **Android:** schlanke WebView-Hülle in Java, ohne Gradle gebaut, ca. 170 KB, ab Android 7 (API 24)
- **Web-App (PWA):** Manifest und Service Worker für Offline-Betrieb und „Zum Home-Bildschirm“
- **Speicherung:** `localStorage` auf dem Gerät, Sicherungscode zum Übertragen
- **Kompatibilität:** Ersatzlösungen für ältere Android-WebViews (Abstände, Raster, Polyfills)
- **Barrierearmut:** Tastaturbedienung (Ziffern und Enter), Fokusrahmen, Rücksicht auf „Bewegung reduzieren“, große Systemschriften

---

## Lizenzen und Quellen

- **Schriften:** Baloo 2 und Nunito, SIL Open Font License 1.1 (Google Fonts)
- **QR-Code-Bibliothek:** qrcode-generator von Kazuhiko Arase, MIT-Lizenz
- **Sprossi, Grafiken und Inhalte:** erstellt für die AG „Going green und fair“ am MMG
- **Quellen der Fakten:** als Kommentare in `index.html` und in `FAKTEN-STAND.md`

---

*MMG · GGAF Quizzes! App · Going green and Fair*

---

## Alle Fragen

Alle Fragen der App auf Deutsch mit der richtigen Antwort (Faktenstand: September 2026). In der App werden die Antworten gemischt; bei Auswahl- und Bildfragen gibt es zusätzlich 3 falsche Antworten, bei Lückentexten 3 falsche Wörter.

### Einheit 1: Klima & Energie

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Welches Gas trägt durch menschliche Aktivitäten am stärksten zur Erderwärmung bei? | Kohlendioxid (CO₂) |
| 2 | Lücke | Im ___ Klimaabkommen von 2015 haben sich fast alle Staaten verpflichtet, die Erwärmung auf deutlich unter 2 °C zu begrenzen. | Pariser |
| 3 | Stimmt? | Geräte im Standby-Modus verbrauchen keinen Strom. | stimmt nicht |
| 4 | Reihenfolge | Sortiere nach CO₂-Ausstoß pro Person und Kilometer – vom geringsten zum höchsten. | Fahrrad → Fernzug → Auto (Benziner) → Inlandsflug |
| 5 | Paare | Welche Energiequelle gehört zu welcher Technik? | Sonne – Photovoltaik; Wind – Windrad; Fließendes Wasser – Wasserkraftwerk; Erdwärme – Geothermie |
| 6 | Auswahl | Wie viel Heizenergie spart man ungefähr, wenn man die Raumtemperatur um 1 °C senkt? | rund 6 % |
| 7 | Stimmt? | Stoßlüften (Fenster kurz weit öffnen) spart mehr Energie als ein dauerhaft gekipptes Fenster. | stimmt |
| 8 | Auswahl | Wie viel Treibhausgas verursacht eine Person in Deutschland durchschnittlich pro Jahr? | rund 10 Tonnen |
| 9 | Auswahl | Welches Treibhausgas entsteht unter anderem im Magen von Rindern? | Methan |
| 10 | Stimmt? | 2024 stammte mehr als die Hälfte des Stroms in Deutschland aus erneuerbaren Energien. | stimmt |
| 11 | Lücke | Eine ___ nutzt Wärme aus Luft, Erdreich oder Grundwasser zum Heizen. | Wärmepumpe |
| 12 | Auswahl | Was bedeutet „klimaneutral“? | Unterm Strich werden keine zusätzlichen Treibhausgase ausgestoßen |
| 13 | Auswahl | Um wie viel hat sich die Erde seit Beginn der Industrialisierung ungefähr erwärmt? | rund 1,4 °C |
| 14 | Stimmt? | Wetter und Klima sind dasselbe. | stimmt nicht |
| 15 | Lücke | Der natürliche ___ sorgt dafür, dass es auf der Erde im Schnitt etwa 15 °C statt –18 °C warm ist. | Treibhauseffekt |
| 16 | Paare | Welche Folge des Klimawandels passt zu welchem Beispiel? | Meeresspiegelanstieg – Überflutete Küsten; Hitzewellen – Mehr Hitzetote; Dürre – Ernteausfälle; Gletscherschmelze – Weniger Wasser in Bergregionen |
| 17 | Auswahl | Welches Land stößt derzeit insgesamt am meisten CO₂ aus? | China |
| 18 | Reihenfolge | Sortiere nach CO₂ pro Kilowattstunde Strom – von wenig nach viel. | Windkraft → Erdgas → Braunkohle |

**Bilderrätsel in dieser Einheit:**

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Bild | Welche Energie wird hier gewonnen? | Windenergie |
| 2 | Bild | Was siehst du auf dem Bild? | Eine Solaranlage (Photovoltaik) |
| 3 | Bild | Diese LED-Lampe ersetzt eine alte Glühbirne. Wie viel Strom spart sie ungefähr? | Rund 80–90 % |

### Einheit 2: Fairer Handel

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Was garantiert das Fairtrade-Siegel den Produzent*innen unter anderem? | Einen Mindestpreis und eine Prämie für Gemeinschaftsprojekte |
| 2 | Auswahl | Welches Land ist der größte Kakaoproduzent der Welt? | Elfenbeinküste |
| 3 | Stimmt? | Fair gehandelte Produkte gibt es nur im Weltladen. | stimmt nicht |
| 4 | Paare | Welches Siegel steht wofür? | Fairtrade – Faire Handelsbedingungen; Blauer Engel – Umweltfreundliche Produkte; FSC – Nachhaltige Forstwirtschaft; MSC – Nachhaltiger Fischfang |
| 5 | Auswahl | Wie viele Kinder weltweit sind laut ILO und UNICEF von Kinderarbeit betroffen? | rund 140 Millionen |
| 6 | Lücke | Das deutsche ___ verpflichtet große Unternehmen seit 2023, auf Menschenrechte in ihren Lieferketten zu achten. | Lieferkettengesetz |
| 7 | Stimmt? | Bei Fairtrade entscheiden die Kooperativen gemeinsam, wofür die Fairtrade-Prämie ausgegeben wird. | stimmt |
| 8 | Reihenfolge | Bringe den Weg einer Tafel Schokolade in die richtige Reihenfolge. | Kakaofrüchte ernten → Bohnen fermentieren und trocknen → Transport per Schiff → Verarbeitung in der Fabrik → Verkauf im Supermarkt |
| 9 | Auswahl | Welche Produkte gehören zu den bekanntesten Fairtrade-Produkten? | Kaffee, Bananen und Kakao |
| 10 | Auswahl | Was ist ein Weltladen? | Ein Fachgeschäft für fair gehandelte Produkte |
| 11 | Stimmt? | Kleinbauernfamilien erhalten im konventionellen Kaffeehandel oft nur einen kleinen Bruchteil des Ladenpreises. | stimmt |
| 12 | Lücke | Fairer Handel soll Produzent*innen ein existenzsicherndes ___ ermöglichen. | Einkommen |
| 13 | Auswahl | Was ist eine Kooperative? | Ein Zusammenschluss von Produzent*innen, die gemeinsam wirtschaften |
| 14 | Stimmt? | Die Fairtrade-Standards verbieten ausbeuterische Kinderarbeit. | stimmt |
| 15 | Paare | Welches Produkt kommt besonders oft aus welchem Land? | Kaffee – Brasilien; Bananen – Ecuador; Kakao – Elfenbeinküste; Baumwolle – Indien |
| 16 | Lücke | Die Internationale ___ (ILO) ist die UN-Organisation für Arbeitsrechte. | Arbeitsorganisation |
| 17 | Auswahl | Welches Siegel steht NICHT für fairen Handel? | Blauer Engel |
| 18 | Stimmt? | Auch Blumen wie Rosen gibt es mit Fairtrade-Siegel. | stimmt |

### Einheit 3: Müll & Recycling

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Reihenfolge | Sortiere nach Zerfallsdauer in der Natur – von kurz nach lang. | Bananenschale → Zigarettenfilter → Getränkedose (Alu) → Plastikflasche |
| 2 | Paare | Was gehört in welche Tonne? | Joghurtbecher – Gelbe Tonne; Zeitung – Papiertonne; Kartoffelschalen – Biotonne; Kassenbon – Restmüll |
| 3 | Stimmt? | Trinkgläser und Keramik gehören in den Altglascontainer. | stimmt nicht |
| 4 | Reihenfolge | Die Abfallhierarchie: Was ist am besten? Sortiere vom besten zum schlechtesten Weg. | Vermeiden → Wiederverwenden → Recyceln → Verbrennen (Energie gewinnen) → Deponieren |
| 5 | Auswahl | Wie viel Pfand gibt es in Deutschland auf eine Einweg-Plastikflasche? | 25 Cent |
| 6 | Lücke | Winzige Plastikteilchen, kleiner als 5 Millimeter, nennt man ___. | Mikroplastik |
| 7 | Stimmt? | Glas-Mehrwegflaschen können bis zu 50-mal wiederbefüllt werden. | stimmt |
| 8 | Auswahl | Wohin mit alten Batterien? | In eine Sammelbox im Handel oder zum Wertstoffhof |
| 9 | Auswahl | Was bedeutet „Upcycling“? | Aus Altem etwas Neues, Wertvolleres machen |
| 10 | Stimmt? | Den Aludeckel vom Joghurtbecher sollte man vor dem Wegwerfen abtrennen. | stimmt |
| 11 | Auswahl | Warum sind Coffee-to-go-Becher ein Problem? | Sie sind meist mit Kunststoff beschichtet und schwer zu recyceln |
| 12 | Lücke | Ein Lebensstil mit möglichst wenig Abfall heißt „Zero ___“. | Waste |
| 13 | Auswahl | Was ist Kreislaufwirtschaft? | Produkte und Rohstoffe möglichst lange im Kreislauf halten |
| 14 | Stimmt? | Deutschland verursacht im EU-Vergleich besonders viel Verpackungsmüll pro Kopf. | stimmt |
| 15 | Lücke | Wegwerfprodukte aus Plastik wie Strohhalme und Einweg-Besteck sind in der EU seit ___ verboten. | 2021 |
| 16 | Paare | Was wird aus dem Abfall? | Altpapier – Recyclingpapier; PET-Flaschen – Fleecestoff und neue Flaschen; Altglas – Neue Glasflaschen; Bioabfall – Kompost und Biogas |
| 17 | Auswahl | In welchen Altglascontainer gehört eine blaue Glasflasche? | Grünglas |
| 18 | Stimmt? | Recyceln ist immer besser als Wiederverwenden. | stimmt nicht |

**Bilderrätsel in dieser Einheit:**

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Bild | Wohin gehört der leere Joghurtbecher? | In die Gelbe Tonne / den Gelben Sack |
| 2 | Bild | Wohin kommt die alte Zeitung? | In die Papiertonne |
| 3 | Bild | Wohin gehört die Bananenschale? | In die Biotonne |
| 4 | Bild | Wohin mit der leeren Batterie? | In eine Batterie-Sammelbox, z. B. im Supermarkt |
| 5 | Bild | Wohin gehört die grüne Einweg-Glasflasche ohne Pfand? | In den Grünglas-Container |
| 6 | Bild | Die Keramiktasse ist kaputt. Wohin damit? | In den Restmüll |
| 7 | Bild | Wohin gehört der Kassenbon? | In den Restmüll |

### Einheit 4: Umweltpolitik in Deutschland

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Welches Bundesministerium ist seit 2025 für den Klimaschutz zuständig? | Das Bundesministerium für Umwelt, Klimaschutz, Naturschutz und nukleare Sicherheit |
| 2 | Stimmt? | Das Umweltbundesamt hat seinen Hauptsitz in Dessau-Roßlau (Sachsen-Anhalt). | stimmt |
| 3 | Lücke | Der Schutz der natürlichen Lebensgrundlagen steht seit 1994 als Staatsziel in Artikel ___ des Grundgesetzes. | 20a |
| 4 | Auswahl | Über welches Verfassungsorgan wirken die 16 Bundesländer bei der Gesetzgebung des Bundes mit? | Bundesrat |
| 5 | Paare | Welches Bundesministerium ist wofür zuständig? | Umweltministerium (BMUKN) – Klima-, Natur- und Umweltschutz; Wirtschaftsministerium (BMWE) – Energie und Strommarkt; Verkehrsministerium – Straßen und Schienen; Landwirtschaftsministerium (BMLEH) – Landwirtschaft, Ernährung und Wald |
| 6 | Reihenfolge | Wie entsteht ein Bundesgesetz? Sortiere die Schritte. | Ein Gesetzentwurf wird eingebracht, oft von der Bundesregierung → Der Bundestag berät und beschließt das Gesetz → Der Bundesrat berät über das Gesetz → Der Bundespräsident unterzeichnet, das Gesetz wird verkündet |
| 7 | Auswahl | Bis wann soll Deutschland laut Klimaschutzgesetz treibhausgasneutral sein? | 2045 |
| 8 | Lücke | Bis 2030 sollen die Treibhausgas-Emissionen in Deutschland um mindestens ___ % gegenüber 1990 sinken. | 65 |
| 9 | Stimmt? | Im April 2023 wurden die letzten drei Atomkraftwerke in Deutschland abgeschaltet. | stimmt |
| 10 | Auswahl | Bis spätestens wann soll in Deutschland laut Gesetz kein Kohlestrom mehr erzeugt werden? | 2038 |
| 11 | Auswahl | Was regelt das Erneuerbare-Energien-Gesetz (EEG)? | Den Ausbau und die Förderung von Strom aus Sonne, Wind und anderen erneuerbaren Quellen |
| 12 | Reihenfolge | Bringe diese Meilensteine der Umweltpolitik in die zeitliche Reihenfolge. | Umweltschutz wird Staatsziel im Grundgesetz → Das Erneuerbare-Energien-Gesetz tritt in Kraft → Der EU-Emissionshandel startet → Das Bundes-Klimaschutzgesetz wird beschlossen |
| 13 | Auswahl | Worauf wird der nationale CO₂-Preis nach dem Brennstoffemissionshandelsgesetz (BEHG) erhoben? | Auf Brennstoffe wie Heizöl, Erdgas, Benzin und Diesel |
| 14 | Lücke | Den nationalen CO₂-Preis für Heizen und Tanken gibt es in Deutschland seit ___. | 2021 |
| 15 | Stimmt? | 2026 und 2027 liegt der CO₂-Preis nach dem BEHG in einem Korridor von 55 bis 65 Euro pro Tonne. | stimmt |
| 16 | Auswahl | Wer muss beim EU-Emissionshandel (EU-ETS) seit 2005 für seinen CO₂-Ausstoß Zertifikate haben? | Kraftwerke und große Industrieanlagen |
| 17 | Paare | CO₂-Preise: Was gehört zusammen? | EU-ETS – Kraftwerke und Industrie, seit 2005; ETS2 – EU-weiter CO₂-Preis für Gebäude und Verkehr, ab 2028; BEHG – Nationaler CO₂-Preis auf Brennstoffe, seit 2021; Klima- und Transformationsfonds – Sondertopf des Bundes für Klimaschutz und Energiewende |
| 18 | Stimmt? | Der neue EU-Emissionshandel für Gebäude und Verkehr (ETS2) startet wie ursprünglich geplant 2027. | stimmt nicht |

### Einheit 5: Die neue Bundesregierung & die Umwelt

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Seit wann regiert in Deutschland die Koalition aus CDU/CSU und SPD unter Bundeskanzler Friedrich Merz? | Seit Mai 2025 |
| 2 | Stimmt? | Mit der neuen Bundesregierung wechselte die Zuständigkeit für den Klimaschutz vom Wirtschaftsministerium ins Umweltministerium. | stimmt |
| 3 | Auswahl | Wie viele Milliarden Euro aus dem Sondervermögen Infrastruktur sollen in den Klima- und Transformationsfonds fließen? | 100 Milliarden Euro |
| 4 | Lücke | Im März 2025 änderte der Bundestag das Grundgesetz für ein Sondervermögen für Infrastruktur und Klimaneutralität von ___ Milliarden Euro. | 500 |
| 5 | Paare | Wer leitet welches Amt in der Bundesregierung? | Bundeskanzler – Friedrich Merz (CDU); Umweltministerium (BMUKN) – Carsten Schneider (SPD); Wirtschafts- und Energieministerium (BMWE) – Katherina Reiche (CDU); Verkehrsministerium – Patrick Schnieder (CDU) |
| 6 | Stimmt? | Seit der Grundgesetzänderung von 2025 steht das Ziel „Klimaneutralität bis 2045“ auch im Grundgesetz. | stimmt |
| 7 | Auswahl | Mit wie viel Geld aus dem Klima- und Transformationsfonds bezuschusst der Bund 2026 die Stromnetzentgelte? | 6,5 Milliarden Euro |
| 8 | Lücke | Für das produzierende Gewerbe sowie die Land- und Forstwirtschaft wurde die Stromsteuer dauerhaft auf den EU-___ gesenkt. | Mindestsatz |
| 9 | Stimmt? | Die Gasspeicherumlage auf den Gaspreis wurde zum Jahr 2026 abgeschafft. | stimmt |
| 10 | Auswahl | Welche Bedingung gilt für neue Gaskraftwerke nach der Kraftwerksstrategie der Bundesregierung? | Sie müssen später auf Wasserstoff umgestellt werden können („H₂-ready“) |
| 11 | Auswahl | Wie hoch ist die neue staatliche Förderung beim Kauf eines Elektroautos seit 2026 höchstens? | 6.000 Euro |
| 12 | Paare | Welche Maßnahme gehört zu welchem Inhalt? | Gebäudemodernisierungsgesetz – Ersetzt das bisherige „Heizungsgesetz“; Kraftwerksstrategie – Neue, wasserstofffähige Gaskraftwerke; E-Auto-Förderung – Prämie von bis zu 6.000 Euro; KTF-Zuschuss – Niedrigere Netzentgelte beim Strom |
| 13 | Auswahl | Wie heißt das Gesetz, das 2026 das Gebäudeenergiegesetz (das sogenannte „Heizungsgesetz“) ersetzt hat? | Gebäudemodernisierungsgesetz |
| 14 | Stimmt? | Nach dem neuen Gebäudemodernisierungsgesetz müssen neue Heizungen nicht mehr zu 65 % mit erneuerbaren Energien betrieben werden. | stimmt |
| 15 | Lücke | Das Gebäudemodernisierungsgesetz ist seit ___ 2026 in Kraft. | Juli |
| 16 | Reihenfolge | Bringe die Schritte zum Gebäudemodernisierungsgesetz in die richtige Reihenfolge. | Das Bundeskabinett beschließt den Gesetzentwurf → Bundestag und Bundesrat stimmen zu → Das Gesetz tritt in Kraft |
| 17 | Auswahl | Welches Klimaziel für 2040 haben sich EU-Parlament und EU-Staaten gesetzt? | 90 % weniger Treibhausgase als 1990 |
| 18 | Reihenfolge | Wie hat sich der Monatspreis des Deutschlandtickets entwickelt? Sortiere vom ersten zum aktuellen Preis. | 49 Euro (Start 2023) → 58 Euro (2025) → 63 Euro (2026) |

### Einheit 6: Wasser & Ozeane

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Wie viel des Wassers auf der Erde ist Süßwasser? | rund 2,5 % |
| 2 | Reihenfolge | Sortiere nach „virtuellem Wasser“ in der Herstellung – von wenig nach viel. | 1 Tomate → 1 Tasse Kaffee → 1 Baumwoll-T-Shirt → 1 kg Rindfleisch |
| 3 | Stimmt? | In Deutschland verbraucht eine Person durchschnittlich rund 122 Liter Trinkwasser pro Tag. | stimmt |
| 4 | Auswahl | Was nimmt das Meer in großen Mengen auf, sodass es versauert? | CO₂ aus der Luft |
| 5 | Lücke | Wenn Korallen durch zu warmes Wasser ihre Farbe verlieren, spricht man von Korallen___. | bleiche |
| 6 | Stimmt? | Duschen verbraucht meist weniger Wasser als ein Vollbad. | stimmt |
| 7 | Paare | Welche Bedrohung hat welche Ursache? | Überfischung – Zu viele Fangschiffe; Plastikmüll – Weggeworfene Verpackungen; Versauerung – CO₂-Aufnahme; Korallenbleiche – Wärmeres Wasser |
| 8 | Auswahl | Was ist der „Great Pacific Garbage Patch“? | Ein riesiger Müllstrudel im Pazifik |
| 9 | Stimmt? | Sauberes Trinkwasser ist weltweit für alle Menschen sicher verfügbar. | stimmt nicht |
| 10 | Auswahl | Warum gehören Feuchttücher nicht in die Toilette? | Sie zersetzen sich kaum und verstopfen Pumpen und Kläranlagen |
| 11 | Lücke | Die Meere produzieren etwa ___ des Sauerstoffs, den wir atmen. | die Hälfte |
| 12 | Auswahl | Welches Siegel kennzeichnet Fisch aus nachhaltigerer Fischerei? | MSC |
| 13 | Auswahl | Wofür wird in deutschen Haushalten das meiste Trinkwasser verwendet? | Baden, Duschen und Körperpflege |
| 14 | Stimmt? | Die Landwirtschaft ist weltweit der größte Wasserverbraucher. | stimmt |
| 15 | Lücke | Wasser, das wir indirekt über Produkte verbrauchen, nennt man ___ Wasser. | virtuelles |
| 16 | Auswahl | Welcher See in Zentralasien ist durch übermäßige Bewässerung größtenteils ausgetrocknet? | Aralsee |
| 17 | Paare | Welches Meerestier ist wodurch bedroht? | Meeresschildkröte – Verwechselt Plastiktüten mit Quallen; Kabeljau – Überfischung; Wal – Schiffslärm und Kollisionen; Korallenriff – Meereserwärmung |
| 18 | Stimmt? | In Deutschland ist es besonders wirksam, warmes Wasser zu sparen – wegen der Energie zum Erhitzen. | stimmt |

**Bilderrätsel in dieser Einheit:**

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Bild | Wie heißt der Vorgang, bei dem Wasser vom Meer in die Wolken aufsteigt? | Verdunstung |
| 2 | Bild | Der Wasserhahn tropft. Was stimmt? | Ein tropfender Hahn kann über 1.000 Liter Wasser im Jahr verschwenden |
| 3 | Bild | Warum ist die Plastiktüte im Meer für die Schildkröte gefährlich? | Sie hält die Tüte für eine Qualle und frisst sie |

### Einheit 7: Essen & Klima

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Reihenfolge | Sortiere nach Treibhausgasen pro Kilogramm – von wenig nach viel. | Kartoffeln → Tofu → Hähnchenfleisch → Rindfleisch |
| 2 | Paare | Wann haben diese Lebensmittel in Deutschland Saison? | Spargel – April bis Juni; Erdbeeren – Mai bis Juli; Kürbis – September bis November; Grünkohl – November bis Februar |
| 3 | Stimmt? | Nach Ablauf des Mindesthaltbarkeitsdatums (MHD) muss man Lebensmittel sofort wegwerfen. | stimmt nicht |
| 4 | Auswahl | Wie viele Lebensmittel werden in Deutschland pro Jahr weggeworfen? | rund 11 Millionen Tonnen |
| 5 | Auswahl | Warum sind Erdbeeren im Januar meist klimaschädlicher? | Lange Transportwege, teils per Flugzeug, oder beheizte Gewächshäuser |
| 6 | Lücke | Obst und Gemüse, das in der Nähe angebaut wird, nennt man ___. | regional |
| 7 | Stimmt? | Rindfleisch braucht viel mehr Fläche als Getreide oder Hülsenfrüchte mit gleichem Nährwert. | stimmt |
| 8 | Auswahl | Was ist „Foodsharing“? | Übrige Lebensmittel weitergeben statt wegwerfen |
| 9 | Auswahl | Wofür steht das EU-Bio-Siegel unter anderem? | Keine chemisch-synthetischen Pflanzenschutzmittel |
| 10 | Stimmt? | „Krumme“ Gurken oder kleine Kartoffeln sind genauso nahrhaft wie makellos aussehende. | stimmt |
| 11 | Auswahl | Welche Lebensmittel sind Hülsenfrüchte? | Linsen, Bohnen, Kichererbsen |
| 12 | Lücke | Die „Planetary Health Diet“ empfiehlt viel Gemüse, Obst, Vollkorn und Hülsenfrüchte – und nur wenig ___. | Fleisch |
| 13 | Auswahl | Was bedeutet „saisonal“ beim Essen? | Obst und Gemüse essen, wenn es bei uns natürlich reif wird |
| 14 | Stimmt? | Tiefkühlgemüse ist immer klimaschädlicher als frisches Gemüse. | stimmt nicht |
| 15 | Lücke | Wechselt man die angebauten Pflanzen auf einem Feld jedes Jahr, um den Boden zu schonen, nennt man das ___. | Fruchtfolge |
| 16 | Paare | Woraus wird das gemacht? | Tofu – Sojabohnen; Pommes – Kartoffeln; Hummus – Kichererbsen; Schokolade – Kakaobohnen |
| 17 | Auswahl | Wofür wird der größte Teil der weltweit angebauten Sojabohnen verwendet? | Als Tierfutter |
| 18 | Reihenfolge | Sortiere nach CO₂ pro Tonne Fracht und Kilometer – von wenig nach viel. | Güterzug → Lkw → Flugzeug |

### Einheit 8: Artenvielfalt

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Wie viele Tier- und Pflanzenarten sind laut Weltbiodiversitätsrat vom Aussterben bedroht? | rund 1 Million |
| 2 | Stimmt? | Moore speichern mehr Kohlenstoff als alle Wälder der Erde zusammen – obwohl sie nur rund 3 % der Landfläche bedecken. | stimmt |
| 3 | Paare | Welches Tier lebt wo? | Biber – Fluss und Bach; Seehund – Wattenmeer; Specht – Wald; Feldlerche – Feld und Wiese |
| 4 | Auswahl | Warum sind Bienen und andere Bestäuber so wichtig? | Rund drei Viertel der wichtigsten Nutzpflanzen profitieren von ihrer Bestäubung |
| 5 | Lücke | Wenn auf einer großen Fläche jahrelang nur eine einzige Pflanzenart wächst, nennt man das ___. | Monokultur |
| 6 | Stimmt? | Ein aufgeräumter Garten mit kurz gemähtem Rasen ist besonders gut für Insekten. | stimmt nicht |
| 7 | Auswahl | Wie stark ging laut der Krefelder Studie die Masse fliegender Insekten in Schutzgebieten zwischen 1989 und 2016 zurück? | um mehr als 75 % |
| 8 | Auswahl | Welcher Lebensraum ist besonders artenreich? | Tropischer Regenwald |
| 9 | Reihenfolge | Bringe diese Nahrungskette in die richtige Reihenfolge – vom Anfang bis zum Ende. | Plankton-Algen → Kleinkrebse → Hering → Seehund |
| 10 | Stimmt? | Tote Bäume (Totholz) sind wertlos für die Natur. | stimmt nicht |
| 11 | Auswahl | Was sind „invasive Arten“? | Eingeschleppte Arten, die heimische Arten verdrängen |
| 12 | Lücke | Ein Streifen mit Wildblumen am Ackerrand heißt ___ und bietet Insekten Nahrung. | Blühstreifen |
| 13 | Auswahl | Was ist ein Nationalpark? | Ein großes Schutzgebiet, in dem sich die Natur möglichst frei entwickeln darf |
| 14 | Lücke | Die Rote ___ zeigt, welche Tier- und Pflanzenarten gefährdet sind. | Liste |
| 15 | Stimmt? | In Deutschland leben wieder frei lebende Wölfe. | stimmt |
| 16 | Paare | Welcher Begriff bedeutet was? | Biotop – Lebensraum; Ökosystem – Lebewesen und Umwelt als Einheit; Artenvielfalt – Anzahl verschiedener Arten; Bestäubung – Übertragung von Pollen |
| 17 | Auswahl | Welcher Greifvogel war in Deutschland fast verschwunden und brütet heute wieder in vielen Regionen? | Seeadler |
| 18 | Stimmt? | Helle Beleuchtung in der Nacht schadet Insekten. | stimmt |

**Bilderrätsel in dieser Einheit:**

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Bild | Warum ist das, was die Biene hier macht, so wichtig? | Sie bestäubt die Blüte – so wachsen Obst und Gemüse |

### Einheit 9: Mode & Konsum

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Was versteht man unter „Fast Fashion“? | Billige Kleidung, die schnell produziert und schnell weggeworfen wird |
| 2 | Auswahl | 2013 stürzte in Bangladesch die Textilfabrik Rana Plaza ein. Wie viele Menschen starben? | über 1.100 |
| 3 | Stimmt? | Viele Kleidungsstücke in deutschen Schränken werden selten oder nie getragen. | stimmt |
| 4 | Paare | Welcher Begriff passt zu welcher Idee? | Secondhand – Gebraucht kaufen; Upcycling – Aufwerten statt wegwerfen; Repair-Café – Gemeinsam reparieren; Kleidertausch – Tauschen statt kaufen |
| 5 | Lücke | Wenn Unternehmen sich umweltfreundlicher darstellen, als sie sind, nennt man das ___. | Greenwashing |
| 6 | Auswahl | Welcher Rohstoff für Handy-Akkus wird oft in der Demokratischen Republik Kongo abgebaut – teils unter gefährlichen Bedingungen? | Kobalt |
| 7 | Stimmt? | Das Smartphone länger zu nutzen ist einer der wirksamsten Wege, seinen Handy-Fußabdruck zu senken. | stimmt |
| 8 | Reihenfolge | Bringe den Lebensweg eines T-Shirts in die richtige Reihenfolge. | Baumwolle anbauen → Garn spinnen → Stoff weben und färben → T-Shirt nähen → Im Laden verkaufen |
| 9 | Auswahl | Wie viele neue Kleidungsstücke kauft eine Person in Deutschland durchschnittlich pro Jahr? | rund 60 |
| 10 | Auswahl | Was ist das „Recht auf Reparatur“? | EU-Regeln, die Reparaturen und Ersatzteile leichter zugänglich machen |
| 11 | Stimmt? | Kleidung aus Polyester verliert beim Waschen Mikroplastikfasern. | stimmt |
| 12 | Lücke | Dinge zu leihen, zu tauschen oder gemeinsam zu nutzen, statt sie neu zu kaufen, nennt man ___. | Sharing |
| 13 | Auswahl | Was versteht man unter „geplanter Obsoleszenz“? | Den Vorwurf, dass Produkte absichtlich so gebaut werden, dass sie früh kaputtgehen |
| 14 | Lücke | Das staatliche Siegel für nachhaltig produzierte Textilien in Deutschland heißt „Grüner ___“. | Knopf |
| 15 | Stimmt? | Bio-Baumwolle wird ohne chemisch-synthetische Pestizide angebaut. | stimmt |
| 16 | Paare | Welches Siegel oder Label gehört zu welchem Bereich? | GOTS – Bio-Textilien; Grüner Knopf – Staatliches Textilsiegel; EU-Energielabel – Energieverbrauch von Geräten; Blauer Engel – Umweltfreundliche Produkte |
| 17 | Auswahl | Der Reißverschluss deiner Lieblingsjacke ist kaputt. Was ist am nachhaltigsten? | Reparieren lassen |
| 18 | Stimmt? | Online bestellte Kleidung wird häufig zurückgeschickt – das verursacht zusätzliche Transporte. | stimmt |

**Bilderrätsel in dieser Einheit:**

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Bild | Welche Klasse auf diesem Energielabel ist die sparsamste? | A (dunkelgrün) |
| 2 | Bild | Wie viel Wasser steckt ungefähr in der Herstellung eines Baumwoll-T-Shirts? | Etwa 2.700 Liter |

### Einheit 10: Globale Gerechtigkeit

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Wie viele Ziele für nachhaltige Entwicklung (SDGs) haben die Vereinten Nationen 2015 beschlossen? | 17 |
| 2 | Paare | Welches Nachhaltigkeitsziel hat welches Thema? | SDG 5 – Geschlechter­gleichheit; SDG 6 – Sauberes Wasser; SDG 12 – Nachhaltiger Konsum; SDG 13 – Klimaschutz |
| 3 | Lücke | Die Ziele für nachhaltige Entwicklung sollen bis zum Jahr ___ erreicht werden. | 2030 |
| 4 | Auswahl | Wenn alle Menschen so leben würden wie wir in Deutschland – wie viele Erden bräuchten wir etwa? | rund 3 |
| 5 | Stimmt? | Länder, die am wenigsten zur Klimakrise beigetragen haben, sind oft am stärksten von ihren Folgen betroffen. | stimmt |
| 6 | Auswahl | Was bedeutet der „Erdüberlastungstag“? | Ab diesem Tag hat die Menschheit mehr verbraucht, als die Erde im Jahr erneuern kann |
| 7 | Auswahl | Wie groß war 2025 in Deutschland der unbereinigte Gender Pay Gap (Stundenlohn Frauen gegenüber Männern)? | 16 % |
| 8 | Stimmt? | Die reichsten 10 % der Weltbevölkerung verursachen rund die Hälfte der weltweiten Konsum-Emissionen. | stimmt |
| 9 | Reihenfolge | Bringe diese Meilensteine der Klimapolitik in die zeitliche Reihenfolge. | Erdgipfel in Rio de Janeiro → Kyoto-Protokoll → Pariser Klimaabkommen |
| 10 | Auswahl | Wofür steht SDG 1? | Keine Armut |
| 11 | Lücke | Wer sich unbezahlt für eine gute Sache engagiert, arbeitet ___. | ehrenamtlich |
| 12 | Stimmt? | Nachhaltigkeit hat drei Dimensionen: Ökologie, Ökonomie und Soziales. | stimmt |
| 13 | Auswahl | In welchem Jahr wurde die Allgemeine Erklärung der Menschenrechte verabschiedet? | 1948 |
| 14 | Lücke | Die Klimabewegung „Fridays for ___“ wurde durch Schulstreiks bekannt. | Future |
| 15 | Stimmt? | Das Recht auf Bildung ist ein Menschenrecht. | stimmt |
| 16 | Paare | Noch mehr Ziele: Welches SDG hat welches Thema? | SDG 2 – Kein Hunger; SDG 4 – Hochwertige Bildung; SDG 7 – Saubere Energie; SDG 14 – Leben unter Wasser |
| 17 | Auswahl | Was bedeutet „Generationengerechtigkeit“? | Heute so leben, dass auch künftige Generationen gute Lebenschancen haben |
| 18 | Stimmt? | Auch Jugendliche unter 18 können sich politisch engagieren, z. B. in Jugendparlamenten. | stimmt |

### Einheit 11: Mobilität & Verkehr

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Welcher Anteil der Treibhausgas-Emissionen in Deutschland stammt aus dem Verkehr? | rund ein Fünftel |
| 2 | Stimmt? | Die Treibhausgas-Emissionen des Verkehrs in Deutschland sind seit 1990 nur wenig gesunken. | stimmt |
| 3 | Lücke | Mit dem ___ kann man für einen festen Monatspreis in ganz Deutschland Busse, Straßenbahnen und Regionalzüge nutzen. | Deutschlandticket |
| 4 | Auswahl | Wie viele Stunden steht ein Auto in Deutschland durchschnittlich pro Tag ungenutzt herum? | rund 23 Stunden |
| 5 | Paare | Welcher Begriff passt zu welcher Beschreibung? | Carsharing – Autos bei Bedarf stundenweise leihen; Pedelec – Fahrrad mit Elektro-Unterstützung; Park-and-Ride – Mit dem Auto zum Bahnhof, weiter mit der Bahn; Fahrgemeinschaft – Mehrere Personen fahren zusammen in einem Auto |
| 6 | Stimmt? | E-Scooter darf man in Deutschland ab 14 Jahren fahren. | stimmt |
| 7 | Auswahl | Wie viele Personen sitzen in Deutschland durchschnittlich in einem fahrenden Auto? | rund 1,4 |
| 8 | Auswahl | Wie viele Pkw sind in Deutschland ungefähr zugelassen? | knapp 50 Millionen |
| 9 | Stimmt? | Ein Elektroauto ist über sein ganzes Autoleben betrachtet meist klimafreundlicher als ein Benziner – obwohl die Herstellung des Akkus viel CO₂ verursacht. | stimmt |
| 10 | Lücke | Wenn Kinder mit dem Auto bis direkt vor das Schultor gebracht werden, spricht man vom „Eltern___“. | taxi |
| 11 | Reihenfolge | Bringe diese Meilensteine der Mobilität in die zeitliche Reihenfolge. | Erste deutsche Eisenbahn Nürnberg–Fürth → Carl Benz meldet sein Auto mit Benzinmotor zum Patent an → Erster ICE im Linienverkehr → Start des Deutschlandtickets |
| 12 | Paare | Welcher Antrieb gehört zu welchem Fahrzeug? | Elektroauto – Akku (Batterie); Brennstoffzellenauto – Wasserstoff; Straßenbahn – Strom aus der Oberleitung; Dieselbus – Kraftstoff aus Erdöl |
| 13 | Auswahl | Was gilt in einer Fahrradstraße? | Radfahrende dürfen nebeneinander fahren, Autos nur mit Zusatzschild |
| 14 | Stimmt? | Beim Fliegen schadet nur das ausgestoßene CO₂ dem Klima. | stimmt nicht |
| 15 | Auswahl | Wie viel Fläche braucht ein einzelner Auto-Stellplatz ungefähr? | rund 12 m² |
| 16 | Lücke | Die Idee, dass man Schule, Einkauf, Arztpraxis und Park in einer Viertelstunde zu Fuß oder mit dem Rad erreicht, heißt „___-Minuten-Stadt“. | 15 |
| 17 | Reihenfolge | Das Prinzip der Verkehrswende: Was hat Vorrang? Sortiere von der ersten zur letzten Stufe. | Verkehr vermeiden → Verkehr verlagern (z. B. auf Bahn und Rad) → Verkehr verbessern (z. B. saubere Antriebe) |
| 18 | Auswahl | Bis zu welcher Geschwindigkeit unterstützt der Motor eines normalen Pedelecs beim Treten? | 25 km/h |

**Bilderrätsel in dieser Einheit:**

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Bild | Wie viel CO₂ stößt dieses Fahrrad beim Fahren aus? | Keins – es fährt mit Muskelkraft |

### Einheit 12: Digitales & Klima

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Welcher Anteil der weltweiten Treibhausgas-Emissionen geht ungefähr auf digitale Technik zurück (Geräte, Netze und Rechenzentren)? | rund 2 bis 4 % |
| 2 | Auswahl | Welche Daten machen den größten Teil des weltweiten Internet-Datenverkehrs aus? | Videos, z. B. beim Streaming |
| 3 | Stimmt? | Eine Stunde Video auf einem großen Fernseher braucht mehr Strom als dieselbe Stunde auf dem Smartphone. | stimmt |
| 4 | Stimmt? | Beim Streaming ist die Datenübertragung über Glasfaser klimafreundlicher als über das Mobilfunknetz. | stimmt |
| 5 | Lücke | Das Symbol der durchgestrichenen ___ bedeutet: Dieses Gerät gehört nicht in den Hausmüll. | Mülltonne |
| 6 | Paare | Welcher Begriff passt zu welcher Erklärung? | Rechenzentrum – Gebäude voller Server; Cloud – Daten auf fremden Servern speichern; E-Schrott – Ausgediente Elektrogeräte; Refurbished – Generalüberholtes Gebrauchtgerät |
| 7 | Auswahl | Wie viel Elektroschrott ist weltweit im Jahr 2022 angefallen? | rund 62 Millionen Tonnen |
| 8 | Stimmt? | Große Elektrohändler und viele Supermärkte müssen kleine Elektro-Altgeräte kostenlos zurücknehmen – auch wenn man nichts Neues kauft. | stimmt |
| 9 | Auswahl | Wie viele alte, ungenutzte Handys liegen laut einer Bitkom-Umfrage in deutschen Haushalten herum? | rund 170 Millionen |
| 10 | Lücke | Seit Ende 2024 müssen neue Handys in der EU einen einheitlichen ___-Ladeanschluss haben. | USB-C |
| 11 | Reihenfolge | Sortiere nach Stromverbrauch beim Videoschauen – von wenig nach viel. | Smartphone → Laptop → Großer Fernseher |
| 12 | Auswahl | Was schreibt die EU seit Juni 2025 für neue Smartphones vor? | Wichtige Ersatzteile müssen noch 7 Jahre nach Verkaufsende lieferbar sein |
| 13 | Auswahl | Wie viel des weltweiten Stroms verbrauchten Rechenzentren im Jahr 2024 laut Internationaler Energieagentur (IEA)? | rund 1,5 % |
| 14 | Stimmt? | Rechenzentren brauchen nicht nur Strom, sondern oft auch viel Wasser zum Kühlen. | stimmt |
| 15 | Lücke | Wenn Technik sparsamer wird, wir sie dadurch aber viel mehr nutzen und am Ende kaum Energie sparen, nennt man das ___-Effekt. | Rebound |
| 16 | Paare | Rechenzentren: Was gehört zusammen? | Server – Computer, der Daten und Dienste für andere bereitstellt; KI-Training – Ein Modell lernt aus riesigen Datenmengen; Abwärme – Wärme aus Servern, die Wohnungen heizen kann; Ökostrom – Strom aus Sonne, Wind und Wasser |
| 17 | Reihenfolge | Sortiere diese Datenmengen – von klein nach groß. | Kilobyte → Megabyte → Gigabyte → Terabyte |
| 18 | Auswahl | Was treibt den Strombedarf von Rechenzentren derzeit besonders stark nach oben? | Künstliche Intelligenz (KI) |

### Einheit 13: Kinderrechte

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | In welchem Jahr haben die Vereinten Nationen die UN-Kinderrechtskonvention beschlossen? | 1989 |
| 2 | Stimmt? | Laut UN-Kinderrechtskonvention gilt jeder Mensch unter 18 Jahren als Kind. | stimmt |
| 3 | Lücke | Die UN-Kinderrechtskonvention besteht aus ___ Artikeln. | 54 |
| 4 | Auswahl | Welcher Staat hat die UN-Kinderrechtskonvention als einziger UN-Mitgliedstaat nicht ratifiziert? | die USA |
| 5 | Paare | Welches Kinderrecht ist hier betroffen? | Ein Mädchen darf nicht zur Schule gehen – Recht auf Bildung; Ein Kind hat nach der Schule nie Zeit zum Spielen – Recht auf Freizeit und Spiel; Ein Kind wird geschlagen – Recht auf Schutz vor Gewalt; Bei der Planung des Schulhofs werden die Kinder nicht gefragt – Recht auf Beteiligung |
| 6 | Stimmt? | In Deutschland haben Kinder ein gesetzliches Recht auf gewaltfreie Erziehung. | stimmt |
| 7 | Auswahl | Was bedeutet der Grundsatz „Vorrang des Kindeswohls“? | Bei allen Entscheidungen, die Kinder betreffen, muss ihr Wohl vorrangig berücksichtigt werden |
| 8 | Lücke | Bei der „Nummer gegen ___“ (116 111) finden Kinder und Jugendliche kostenlos und anonym ein offenes Ohr. | Kummer |
| 9 | Auswahl | Wie heißt das Kinderhilfswerk der Vereinten Nationen? | UNICEF |
| 10 | Reihenfolge | Bringe diese Ereignisse der Kinderrechte in die zeitliche Reihenfolge. | Genfer Erklärung der Rechte des Kindes → Gründung von UNICEF → Verabschiedung der UN-Kinderrechtskonvention → Die Konvention tritt in Deutschland in Kraft |
| 11 | Stimmt? | Kinderrechte stehen ausdrücklich im deutschen Grundgesetz. | stimmt nicht |
| 12 | Auswahl | Was garantiert Artikel 12 der UN-Kinderrechtskonvention? | Kinder dürfen in allen Angelegenheiten, die sie betreffen, ihre Meinung sagen – und sie muss berücksichtigt werden |
| 13 | Auswahl | Was hat der UN-Ausschuss für die Rechte des Kindes 2023 ausdrücklich bestätigt? | Kinder haben ein Recht auf eine saubere, gesunde und nachhaltige Umwelt |
| 14 | Stimmt? | Fotos von Mitschüler*innen darf man ohne deren Erlaubnis im Internet veröffentlichen. | stimmt nicht |
| 15 | Lücke | Wenn Eltern viele Fotos und Videos ihrer Kinder in sozialen Netzwerken teilen, nennt man das ___. | Sharenting |
| 16 | Auswahl | Was entschied das Bundesverfassungsgericht 2021 nach einer Klage junger Menschen? | Das Klimaschutzgesetz musste nachgebessert werden, um die Freiheit künftiger Generationen zu schützen |
| 17 | Reihenfolge | Wie wird ein UN-Vertrag wie die Kinderrechtskonvention in einem Land wirksam? Bringe die Schritte in die richtige Reihenfolge. | Die UN-Generalversammlung beschließt den Vertrag → Ein Staat unterzeichnet den Vertrag → Der Staat ratifiziert den Vertrag → Der Staat berichtet regelmäßig an den UN-Ausschuss in Genf |
| 18 | Paare | Welche Altersgrenze gilt in Deutschland wofür? | 7 Jahre – Beschränkt geschäftsfähig (z. B. Taschengeldkäufe); 14 Jahre – Strafmündig; 16 Jahre – Wählen bei der Europawahl; 18 Jahre – Volljährig |

### Einheit 14: Wald & Moore in Bayern

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Welcher Anteil der Fläche Bayerns ist mit Wald bedeckt? | gut ein Drittel |
| 2 | Stimmt? | Bayern hat die größte Waldfläche aller deutschen Bundesländer. | stimmt |
| 3 | Auswahl | Welche Baumart ist in Bayerns Wäldern am häufigsten? | Fichte |
| 4 | Reihenfolge | Ein Wald hat Stockwerke. Sortiere von unten nach oben. | Moosschicht → Krautschicht → Strauchschicht → Baumschicht |
| 5 | Lücke | Der Begriff „Nachhaltigkeit“ stammt aus der ___: Hans Carl von Carlowitz forderte 1713, nur so viel Holz zu fällen, wie nachwächst. | Forstwirtschaft |
| 6 | Paare | Welcher Baum hat welche Früchte oder Zapfen? | Rotbuche – Bucheckern; Eiche – Eicheln; Fichte – Hängende Zapfen; Weißtanne – Aufrecht stehende Zapfen |
| 7 | Auswahl | Warum sind viele Fichtenwälder in Bayern in Gefahr? | Hitze und Trockenheit schwächen die Bäume, dann befällt sie der Borkenkäfer |
| 8 | Stimmt? | Die Fichte ist ein Tiefwurzler und kommt deshalb gut mit Trockenheit zurecht. | stimmt nicht |
| 9 | Lücke | Werden reine Nadelwälder nach und nach in klimastabile Mischwälder verwandelt, spricht man von Wald___. | umbau |
| 10 | Auswahl | Wem gehört der größte Teil des Waldes in Bayern? | Privatleuten |
| 11 | Stimmt? | Laut Bundeswaldinventur hat der Wald in Deutschland zwischen 2017 und 2022 mehr Kohlenstoff verloren als gespeichert. | stimmt |
| 12 | Auswahl | Was ist ein Schutzwald in den Alpen? | Ein Wald, der Dörfer und Straßen vor Lawinen, Steinschlag und Muren schützt |
| 13 | Auswahl | Wie schnell wächst die Torfschicht in einem intakten Hochmoor ungefähr? | rund 1 Millimeter pro Jahr |
| 14 | Stimmt? | Wer torffreie Blumenerde kauft, hilft beim Schutz der Moore. | stimmt |
| 15 | Paare | Was passt zusammen? | Hochmoor – Wird nur von Regenwasser gespeist; Niedermoor – Wird von Grundwasser gespeist; Torfmoos – Saugt sich voll Wasser wie ein Schwamm; Sonnentau – Fleischfressende Moorpflanze |
| 16 | Lücke | Wird ein entwässertes Moor wieder nass gemacht, spricht man von ___. | Wiedervernässung |
| 17 | Reihenfolge | Wie entsteht ein Hochmoor aus einem See? Bringe die Stufen in die richtige Reihenfolge. | Flacher See → Verlandung mit Schilf und Seggen → Niedermoor → Hochmoor |
| 18 | Auswahl | Wie viel der Moorflächen in Bayern sind entwässert? | rund 95 % |

**Bilderrätsel in dieser Einheit:**

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Bild | Was speichert dieses Moor besonders gut? | Kohlenstoff (CO₂) |

### Einheit 15: Deutschland: Energie & Klima in Zahlen

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Wie viele Treibhausgase hat Deutschland 2025 ungefähr ausgestoßen (in CO₂-Äquivalenten)? | rund 650 Millionen Tonnen |
| 2 | Auswahl | Um wie viel lagen die Treibhausgas-Emissionen 2025 unter dem Wert von 1990? | rund 48 % |
| 3 | Lücke | Laut Klimaschutzgesetz darf Deutschland 2030 nur noch rund ___ Millionen Tonnen Treibhausgase ausstoßen. | 438 |
| 4 | Stimmt? | Von 2024 auf 2025 sind die Treibhausgas-Emissionen in Deutschland kaum gesunken. | stimmt |
| 5 | Stimmt? | Im Verkehr und bei den Gebäuden sind die Emissionen 2025 im Vergleich zum Vorjahr gestiegen. | stimmt |
| 6 | Reihenfolge | Sortiere die Treibhausgas-Mengen Deutschlands vom größten zum kleinsten Wert. | 1990: rund 1.253 Millionen Tonnen → 2025: rund 649 Millionen Tonnen → Ziel 2030: rund 438 Millionen Tonnen → Ziel 2045: netto null |
| 7 | Auswahl | Wie viel Prozent des Stromverbrauchs in Deutschland deckten erneuerbare Energien 2025? | fast 56 % |
| 8 | Auswahl | Welche Energiequelle erzeugte 2025 den meisten Strom in Deutschland? | Windkraft |
| 9 | Stimmt? | Solaranlagen erzeugten 2025 erstmals mehr Strom als Braunkohlekraftwerke. | stimmt |
| 10 | Lücke | Ende 2025 hatten alle Solaranlagen in Deutschland zusammen rund ___ Gigawatt Leistung. | 117 |
| 11 | Auswahl | Wie viel Leistung hatten alle Windräder an Land in Deutschland Ende 2025 ungefähr? | rund 68 Gigawatt |
| 12 | Paare | Welche Leistung gehört zu welcher Anlagenart (Deutschland, Ende 2025)? | Solaranlagen – rund 117 Gigawatt; Windräder an Land – rund 68 Gigawatt; Windräder auf See – rund 9,5 Gigawatt; Alle erneuerbaren Anlagen zusammen – rund 210 Gigawatt |
| 13 | Auswahl | Welches Bundesland hat die meiste Solarleistung installiert? | Bayern |
| 14 | Lücke | Ende 2025 gab es in Bayern fast ___ Millionen Photovoltaik-Anlagen. | 1,4 |
| 15 | Stimmt? | Bayern hat 2025 so viel Solarleistung neu gebaut wie kein anderes Bundesland. | stimmt |
| 16 | Auswahl | Was besagte die bayerische „10H-Regel“ für Windräder? | Ein Windrad muss mindestens das Zehnfache seiner Höhe von Wohnhäusern entfernt stehen |
| 17 | Reihenfolge | Bringe die Geschichte der 10H-Regel in Bayern in die richtige Reihenfolge. | Die 10H-Regel wird eingeführt → Der Landtag beschließt eine Lockerung → Die Lockerung tritt in Kraft |
| 18 | Paare | Welche Zahl gehört zu welchem Bayern-Fakt? | rund 35 Gigawatt – Solarleistung in Bayern Ende 2025; rund 4,5 Gigawatt – Solar-Zubau in Bayern 2025; 2014 – Einführung der 10H-Regel; 1.000 Meter – Mindestabstand nach der Lockerung, z. B. in Wäldern und an Autobahnen |

### MMG-Special: AG „Going green und fair“

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Auswahl | Von wem stammt das Zitat „Was wir heute tun, entscheidet darüber, wie die Welt morgen aussieht“? | Marie von Ebner-Eschenbach |
| 2 | Lücke | Die AG am MMG heißt „Going green und ___“. | fair |
| 3 | Auswahl | Wofür steht die Abkürzung BNE? | Bildung für nachhaltige Entwicklung |
| 4 | Stimmt? | BNE ist eine weltweite Bildungskampagne der Vereinten Nationen. | stimmt |
| 5 | Auswahl | Was sollen die AG-Mitglieder bei ihren Projekten erleben? | Selbstwirksamkeit und Gemeinschaft |
| 6 | Lücke | BNE soll es allen Menschen ermöglichen, die Auswirkungen des eigenen ___ auf die Welt zu verstehen. | Handelns |
| 7 | Auswahl | Wie hieß der Workshop der AG in der Woche der Gesundheit und Nachhaltigkeit? | „Change Fashion“ |
| 8 | Stimmt? | Fast Fashion ist Trendmode, die in schnell aufeinanderfolgenden Kollektionen erscheint. | stimmt |
| 9 | Auswahl | Wo sind die fairen Produkte des MMG-Weltladens gut sichtbar ausgestellt? | In einer Glasvitrine in der Mensa |
| 10 | Auswahl | Wie oft öffnet der MMG-Weltladen? | Einmal im Monat |
| 11 | Lücke | Im Advent verteilten Nikolaus, Knecht Ruprecht und Engel faire ___ an alle Schüler*innen des MMG. | Schokonikoläuse |
| 12 | Stimmt? | Nikolaus, Knecht Ruprecht und die Engel waren Mitglieder der SMV. | stimmt |
| 13 | Auswahl | Wie viel Geld erhielt das Hilfswerk „Missio“ pro gespendetem Handy? | 50 Cent |
| 14 | Auswahl | Wie viele Handys schickte das MMG an das Sammelcenter? | 49 |
| 15 | Stimmt? | Mit den Handyspenden werden Projekte für Kinder unter anderem in Ghana und auf den Philippinen unterstützt. | stimmt |
| 16 | Paare | Welche Eigenschaft der MMG-Hefte hat welchen Vorteil? | 100 % Recyclingpapier – Schont Wälder; Aus Dorfen – Kurze Transportwege; Stabiler Einband – Kein Plastikumschlag nötig; Integrierter Heftstreifen – Kein extra Schnellhefter |
| 17 | Lücke | Die MMG-Hefte kommen regional vom Musikverlag Streubel aus ___. | Dorfen |
| 18 | Auswahl | Wie erkennt man bei den MMG-Heften ohne Plastikumschlag das Fach? | Man malt den Rand in der Fachfarbe an |

### Schätzen & Mythen – Schätzfragen

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Schätzen | Wie viele Liter Wasser stecken in der Herstellung eines Baumwoll-T-Shirts? | 2700 Liter |
| 2 | Schätzen | Wie viele Liter Wasser stecken in 1 kg Rindfleisch? | 15000 Liter |
| 3 | Schätzen | Wie viele Liter Trinkwasser verbraucht eine Person in Deutschland pro Tag? | 122 Liter |
| 4 | Schätzen | Wie viele neue Kleidungsstücke kauft eine Person in Deutschland pro Jahr? | 60 Stück |
| 5 | Schätzen | Wie viele Jahre braucht eine Plastikflasche, um in der Natur zu zerfallen? | 450 Jahre |
| 6 | Schätzen | Wie viele Ziele für nachhaltige Entwicklung (SDGs) gibt es? | 17 Ziele |
| 7 | Schätzen | Wie viel Prozent des Wassers auf der Erde ist Süßwasser? | 2.5 % |
| 8 | Schätzen | Wie viel Prozent Heizenergie spart man, wenn man die Raumtemperatur um 1 °C senkt? | 6 % |
| 9 | Schätzen | Wie viele Nationalparks gibt es in Deutschland? | 16 Nationalparks |
| 10 | Schätzen | Wie viele Millionen Tonnen Lebensmittel werden in Deutschland pro Jahr weggeworfen? | 11 Mio. Tonnen |
| 11 | Schätzen | In welchem Jahr wurde das Pariser Klimaabkommen beschlossen? | 2015  |
| 12 | Schätzen | Wie viele Handys hat das MMG bei der Sammelaktion ans Sammelcenter geschickt? | 49 Handys |
| 13 | Schätzen | Wie viele Millionen Kinder weltweit sind laut ILO und UNICEF von Kinderarbeit betroffen? | 138 Millionen |
| 14 | Schätzen | Um wie viel Grad hat sich die Erde seit Beginn der Industrialisierung ungefähr erwärmt? | 1.4 °C |
| 15 | Schätzen | Wie oft kann eine Glas-Mehrwegflasche höchstens wiederbefüllt werden? | 50 Mal |

### Schätzen & Mythen – Wahr oder Mythos?

| # | Art | Frage | Richtige Antwort |
|---|---|---|---|
| 1 | Stimmt? | Bio-Lebensmittel kommen immer aus der Region. | stimmt nicht |
| 2 | Stimmt? | Papiertüten sind immer umweltfreundlicher als Plastiktüten. | stimmt nicht |
| 3 | Stimmt? | Geräte im Standby verbrauchen keinen Strom. | stimmt nicht |
| 4 | Stimmt? | Schon 1 °C weniger Raumtemperatur spart rund 6 % Heizenergie. | stimmt |
| 5 | Stimmt? | Nach dem Mindesthaltbarkeitsdatum muss man Lebensmittel wegwerfen. | stimmt nicht |
| 6 | Stimmt? | Joghurtbecher muss man vor dem Wegwerfen gründlich ausspülen. | stimmt nicht |
| 7 | Stimmt? | Trinkgläser und Keramik gehören in den Altglascontainer. | stimmt nicht |
| 8 | Stimmt? | Der heutige Klimawandel ist nur ein natürlicher Klimazyklus. | stimmt nicht |
| 9 | Stimmt? | Das Ozonloch ist die Hauptursache des Klimawandels. | stimmt nicht |
| 10 | Stimmt? | Leitungswasser ist in Deutschland streng kontrolliert und kann meist bedenkenlos getrunken werden. | stimmt |
| 11 | Stimmt? | Recyclingpapier ist schlechter als Papier aus frischen Fasern. | stimmt nicht |
| 12 | Stimmt? | Kleidung aus Polyester verliert beim Waschen Mikroplastikfasern. | stimmt |
| 13 | Stimmt? | Bäume pflanzen allein reicht, um den Klimawandel zu stoppen. | stimmt nicht |
| 14 | Stimmt? | Fair gehandelte Produkte gibt es nur im Weltladen. | stimmt nicht |
| 15 | Stimmt? | Ein Smartphone länger zu nutzen ist gut fürs Klima. | stimmt |
