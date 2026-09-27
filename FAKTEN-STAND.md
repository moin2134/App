# GGAF Quizzes! – Faktenstand und jährliche Aktualisierung

**Aktueller Faktenstand: September 2026.** Er steht in `index.html` in der Konstante `FACT_STAND` und wird in der App unter Profil angezeigt.

Einmal pro Schuljahr prüfen, am besten im September, weil viele Zahlen im Frühjahr und Sommer neu erscheinen:
1. In jeder Zeile unten den **Suchtext** in `index.html` suchen (Strg+F).
2. Den Wert mit der **Quelle** vergleichen und bei Bedarf in der Frage **und** im Infotext ändern. Beide Stellen sind jeweils angegeben.
3. `FACT_STAND` auf den neuen Monat setzen.
4. Die APK neu bauen:
   ```
   powershell -File android/build.ps1
   ```
   Dabei in `android/AndroidManifest.xml` den `versionCode` um 1 erhöhen.

## Zahlen, die sich regelmäßig ändern

| Thema | Suchtext in index.html | Stand | Quelle |
|---|---|---|---|
| Ökostrom-Anteil | `2024 stammte mehr als die Hälfte des Stroms` | 2024: ca. 54–60 % | UBA „Erneuerbare Energien in Zahlen“, Fraunhofer ISE energy-charts |
| CO₂-Fußabdruck pro Kopf | `rund 10 Tonnen` | ca. 10,3 t CO₂e | UBA CO₂-Rechner |
| Erderwärmung | `rund 1,4 °C` (Frage und Infotext) | ca. 1,4 °C, 2024 > 1,5 °C | Copernicus „Global Climate Highlights“, WMO |
| Kakao Elfenbeinküste + Ghana | `rund die Hälfte des Kakaos` (Frage und Infotext) | ca. 50 % | ICCO Quarterly Bulletin |
| Kinderarbeit | `rund 140 Millionen` / `rund 138 Millionen` | 138 Mio. (Schätzung 2025) | ILO/UNICEF, nächste Schätzung ca. 2029 |
| Lieferkettengesetz | `Lieferkettengesetz` | gilt, Überarbeitung (EU-CSDDD) angekündigt | Bundestag, BMAS |
| Weltläden | `rund 900 Weltläden` | über 900 | Weltladen-Dachverband |
| Wasserverbrauch pro Kopf | `rund 122 Liter` (Frage und Infotext) | 122 l/Tag (2024) | BDEW |
| Menschen ohne sicheres Trinkwasser | `Mehr als 2 Milliarden` | 2,1 Mrd. (JMP 2025) | WHO/UNICEF JMP |
| Lebensmittelabfälle | `rund 11 Millionen Tonnen` / `rund 75 kg pro Person` | 10,9 Mio. t, 75 kg (2023) | UBA, Destatis |
| Bedrohte Arten | `rund 1 Million` | IPBES 2019 | IPBES |
| Kleidung pro Kopf | `rund 60` | ca. 60 Teile/Jahr | Greenpeace |
| Erdüberlastungstag Deutschland | `2026: 10. Mai` | 10. Mai 2026 | Germanwatch, Global Footprint Network |
| Erdüberlastungstag weltweit | `Ende Juli` (Infotext) | 30. Juli 2026 | Global Footprint Network |
| „Erden“ bei deutschem Lebensstil | `rund 3` | ca. 2,8–3 | Global Footprint Network |
| Gender Pay Gap | `2025 in Deutschland der unbereinigte Gender Pay Gap` (Frage und Infotext) | 16 % (2025) | Destatis, Pressemitteilung zum Equal Pay Day |
| Konsum-Emissionen der Reichsten | `reichsten 10 %` / `rund 8 %` | ca. 50 % / 8 % | Oxfam/SEI |
| Extreme Armut | `Mehr als 800 Millionen` (Frage und Infotext) | > 800 Mio. (Weltbank, Sept. 2026) | Weltbank Poverty Update |
| Verpackungsmüll im EU-Vergleich | `besonders viel Verpackungsmüll pro Kopf` | DE 215 kg vs. EU 178 kg (2023) | Eurostat |
| Nationalparks | `Deutschland hat 16 Nationalparks` | 16 | BfN |

## MMG und AG: jedes Schuljahr mit der AG abstimmen

| Thema | Suchtext | Was prüfen? |
|---|---|---|
| Weltladen-Öffnung | `einmal im Monat` / `Einmal im Monat` | Öffnet der MMG-Weltladen noch monatlich? |
| Glasvitrine | `Glasvitrine in der Mensa` | Steht die Vitrine noch dort? |
| Handysammelaktion | `50 Cent`, `49 Handys` | Neue Aktion oder neue Zahlen? |
| MMG-Hefte | `Musikverlag Streubel aus Dorfen` | Gleicher Lieferant? |
| Workshop | `Change Fashion` | Neues Workshop-Thema ergänzen? |

## Neue Einheiten 9–12 (Mobilität, Digitales, Kinderrechte, Wald & Moore)

| Thema | Suchtext in index.html | Stand | Quelle |
|---|---|---|---|
| Alte Handys in Schubladen | `167 Millionen` | 167 Mio. (Bitkom 2026) | Bitkom |
| Kinderrechte im Grundgesetz | `Grundgesetz` (Stimmt-Frage, Antwort „stimmt nicht“) | noch nicht aufgenommen (Stand 2026) | Bundestag, Deutsches Kinderhilfswerk. **Sofort ändern**, wenn das Grundgesetz geändert wird |
| Rechenzentren und Strom | `1,5 %` | ca. 1,5 % des weltweiten Stroms | IEA „Energy and AI“ |
| Ökostrom-Pflicht für Rechenzentren | `Energieeffizienzgesetz` | 100 % Ökostrom ab 2027, Gesetz wird gerade überarbeitet | BMWK |

Die vollständige Quellenliste der neuen Einheiten steht als Kommentar direkt hinter `NEW_INFOS` in `index.html`.

## Einheiten 13–15: Deutschland & Umweltpolitik (Stand September 2026)

Politische Angaben ändern sich besonders schnell. Diese Themen bei jedem Regierungs- oder Gesetzeswechsel sofort prüfen:

| Thema | Suchtext in index.html | Stand | Hinweis |
|---|---|---|---|
| Ministerien und Zuständigkeiten | `BMUKN` | Klimaschutz beim Umweltministerium seit 2025 | bundesregierung.de |
| Ministerinnen und Minister | `Schneider`, `Reiche`, `Schnieder` | Stand 2026 | ändert sich bei Kabinettsumbildung |
| Nationaler CO₂-Preis | `55` bis `65` (CO₂-Preis) | Korridor 2026/27 | **unsicher:** Gesetz für 2027 war im Entwurf |
| EU-Emissionshandel für Gebäude und Verkehr | `ETS2` | verschoben auf 2028 | **unsicher:** formale Verabschiedung prüfen |
| EU-Klimaziel 2040 | `90 %` | −90 % (bis 5 Punkte über internationale Zertifikate) | **unsicher:** formale Verabschiedung prüfen |
| Sondervermögen Infrastruktur | `500` / `100 Milliarden` | 100 Mrd. für den KTF, Art. 143h GG | Grundgesetzänderung 2025 |
| Gebäudemodernisierungsgesetz | `Gebäudemodernisierungsgesetz` | in Kraft seit 29.07.2026, 65-%-Regel gestrichen | BMWSB |
| Deutschlandticket | `63` | 49 → 58 → 63 € | Preis 2027 wird im Herbst 2026 festgelegt |
| E-Auto-Förderung | `6.000` | bis zu 6.000 € | Förderbedingungen ändern sich oft |
| Treibhausgas-Emissionen | `649` | ca. 649 Mt (2025), −48 % gegenüber 1990 | UBA, jährlich im März |
| Ökostrom-Anteil 2025 | `fast 56 %` | vorläufiger Wert | BDEW/ZSW |
| Solar in Bayern | `rund 35 GW` | ca. 35 GW, ca. 1,4 Mio. Anlagen | Quellen schwanken (32,7–35,4 GW) |

Die vollständige Quellenliste steht als Kommentar direkt hinter `DE_INFOS` in `index.html`.
