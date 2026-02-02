## Was im Vorschlag fehlt

* Zusätzlich zu deiner Liste müssen auch diese sichtbaren Strings in [index.html](file:///p:/Documents/GitHub/mctrans1/out/html/index.html) übersetzt werden:

  * `aria-label="Toggle Theme"` (Theme-Button)

  * Die Button-Texte in der Save/Load-Tabelle: `Save` und `Delete` (mehrfach)

* Keine HTML-Kommentare wie „Dendry … will be populated here“ Übersetzen. Der komplette Code soll englisch bleiben).

## Konkrete Übersetzungen (Vorschlag)

* `lang="en"` → `lang="de"`

* Meta-Description: `TestStory - An interactive story experience` → `Manage Complexity – Eine interaktive Story`

* Titel: `TestStory - storyde` → z.B. `Manage Comlexity`

* Header:

  * `Toggle Progress` → `Fortschritt umschalten`

  * `Toggle Progress Panel` → `Fortschrittsleiste umschalten`

  * `Toggle Info` → `Info umschalten`

  * `Toggle Info Panel` → `Info-Bereich umschalten`

* Sidebar-Überschriften:

  * `Progress` → `Fortschritt`

  * `Info` → `Info`&#x20;

* ARIA labels:

  * `Game Progress Information` → `Informationen zum Spielfortschritt`

  * `Game Story` → `Spielverlauf`

  * `Available Choices` → `Verfügbare Entscheidungen`

  * `Game Info Information` → `Spielinformationen`

  * `Save/Load Game` → `Spiel speichern/laden`

  * `Save & Load Game` → `Spiel speichern & laden`

  * `Close Save Dialog` → `Speicherdialog schließen`

  * `Save Slots` → `Speicherstände`

* Tabellenköpfe:

  * `Slot` → `Slot`

  * `Action` → `Aktion`

  * `Delete` → `Löschen`

  * `Save Info` → `Speicherinfo`

* Tabellenbuttons:

  * `Save` → `Speichern`

  * `Delete` → `Löschen`

* CSS Markertext in [game.css:L1533-L1536](file:///p:/Documents/GitHub/mctrans1/out/html/game.css#L1533-L1536):

  * `⚓  New Content Below  ⚓` → `⚓  Neuer Inhalt unten  ⚓`

## Umsetzungsschritte

1. [index.html](file:///p:/Documents/GitHub/mctrans1/out/html/index.html) gezielt patchen: alle obigen Strings ersetzen (ohne DOM/IDs anzufassen).
2. [game.css](file:///p:/Documents/GitHub/mctrans1/out/html/game.css#L1533-L1536) patchen: `content:`-String auf Deutsch.
3. Verifizieren: Datei einmal komplett scannen (schnelle Suche nach typischen Reststrings wie `Toggle`, `Save`, `Delete`, `Progress`, `Game Story`).
4. Optional danach: Build laufen lassen aber keinen server starten, der Nutzer öffnet `out/html/index.html selber `im Browser und testet.

