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
Die komplette App gibt es in **15 Sprachen**: Fragen, Infotexte, Lexikon, Tipps, Einführung und alle Bedienelemente. In der Auswahl stehen die wichtigsten Sprachen oben, Dialekte, Latein und Keilschrift unten.

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
| Boarisch | `bar` | gemäßigtes Oberbairisch |
| Schwiizerdütsch | `gsw` | Zürichdeutsch als Basis |
| Latina | `la` | Schullatein, moderne Begriffe teils in Anführungszeichen |
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

### Android (App-Datei)
1. Die APK aufs Handy laden: über **https://github.com/moin2134/App/raw/main/GGAF-Quizzes.apk**, per Messenger oder per QR-Code aus der App.
2. Datei antippen.
3. Falls gefragt: **„Installation aus unbekannten Quellen“** erlauben.
4. **Installieren** antippen.

Die App läuft ab **Android 7** und komplett **offline**. Neue Versionen installieren sich über die alte, der Fortschritt bleibt erhalten.

### iPhone und iPad (Web-App)
Eine echte iPhone-App (`.ipa`) erfordert einen Mac und ein Apple-Entwicklerkonto. Stattdessen:
1. https://moin2134.github.io/App/ in **Safari** öffnen.
2. Auf **Teilen** (Quadrat mit Pfeil) tippen.
3. **„Zum Home-Bildschirm“** wählen.

Danach startet GGAF Quizzes! mit Sprossi-Symbol im Vollbild, auch offline.

### Android oder PC im Browser
Einfach https://moin2134.github.io/App/ öffnen. Im Browser-Menü lässt sich die Seite mit „App installieren“ ebenfalls wie eine App einrichten.

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
