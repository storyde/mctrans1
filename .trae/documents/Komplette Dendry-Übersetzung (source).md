## Ziel

* Alle `.dry` Dateien in `source/` vollständig ins Deutsche übersetzen.

* Nur sichtbarer Text wird übersetzt (Titel, Untertitel, Story-Text, Choice-Labels, Sidebar-Texte).

* Sämtliche Spiellogik/Syntax bleibt unverändert (Variablen, Tags, Scene-IDs, Bedingungen, Handler wie `on-arrival`, `go-to`, `view-if`, etc.).

* Der Name **Facylin** bleibt exakt unverändert.

* Zeilenpräfix **`Me:`** bleibt am Zeilenanfang exakt unverändert (Text dahinter wird übersetzt).

## Was genau übersetzt wird (Regeln)

* **Properties**

  * `title:` Wert übersetzen (Key bleibt `title:`).

  * `subtitle:` Wert übersetzen.

  * `unavailable-subtitle:` (falls vorhanden) Wert übersetzen.

  * Andere Properties nicht anfassen (z.B. `tags:`, `view-if:`, `choose-if:`, `on-arrival:`, `go-to:` …).

* **Story-/Markdown-Text**

  * Fließtextzeilen übersetzen.

  * Überschriftenzeilen mit `=`: nur den Text nach `=` übersetzen.

  * Markdown-Markup (`*…*`, `**…**`) erhalten, nur Inhalt übersetzen.

* **Choices / Links**

  * `- @scene_id: Label` → nur **Label** übersetzen, `@scene_id` bleibt.

  * `- @scene_id` ohne Label bleibt unverändert.

  * `- #tag` bleibt unverändert.

* **Dialogzeilen**

  * `Me:` Präfix unverändert lassen.

  * Andere Sprecherlabels wie `Facylin:`, `Stranger:`, `Vendor:` etc. als Label **nicht übersetzen**, nur den Text nach dem Doppelpunkt.

* **Inline-Conditional Text** in `progress.scene.dry`

  * In `[? if … : TEXT ?]` nur **TEXT** übersetzen, die Bedingung/Syntax bleibt unverändert.

* **QDisplay** (`qholtext_progress.qdisplay.dry`)

  * In Zeilen wie `(0..0) : Text` nur den **Text** nach `:` übersetzen, Range/Format bleibt.

## Terminologie/Glossar (konsistent über alle Szenen)

* „Whole Under Management“ → „bewirtschaftete Ganzheit“ oder auch bloß "Ganzheit"

* „Holistic Context“ → „holistischer Kontext“ (oder „Holistic Context“ falls im Spiel absichtlich englisch; ich halte es sonst konsequent deutsch)

* „Quality of Life“ → „Lebensqualität“

* „Future Resource Base“ → „zukünftige Ressourcenbasis“

* „Filter Questions“ → „Filterfragen“ oder "Kontrollfragen"

* „Statement of Purpose“ → „Daseinszweck“ (für Organisationen)

<br />

* DIE SIEBEN KONTEXTFRAGEN

1. Ursache und Wirkung.

„Behandelt diese Maßnahme
die eigentliche Ursache des
Problems?“

2. Schwächste Verbindung.

SOZIALE SCHWACHSTELLE

„Könnte diese Maßnahme
aufgrund von derzeit vorherr-
schenden Meinungen oder
Glaubenssätzen die Beziehung
zwischen uns und den
Personen, deren Unterstützung
wir benötigen, schwächen?“

BIOLOGISCHE SCHWACHSTELLE

„Ist diese Maßnahme
auf die schwächste Stelle
im Lebenszyklus dieses
Organismus gerichtet?”

FINANZIELLE SCHWACHSTELLE

„Stärkt
diese Aktion die Schwachstelle
in der Produktionskette?”

3. Grenznutzen

„Welche Maßnahme bringt im
Hinblick auf das Ziel für jede
zusätzlich investierte Geld-
oder Zeiteinheit den größten
Nutzen?”

4. Rohgewinnanalyse

„Welche Unternehmensbereiche
tragen am meisten zur Deckung
der Gemeinkosten bei?“

5. Energie-/Geldquelle und deren Verwendung.

„Stammt die Energie oder
das Geld für diese Maßnahme
vor dem Hintergrund unseres
ganzheitlichen Kontexts aus
der sinnvollsten Quelle? Ist die
Art und Weise, wie die Energie
oder das Geld eingesetzt wird,
mit unserem ganzheitlichen
Kontext vereinbar?“

ENERGIEQUELLEN

GELDQUELLEN

FORMEN DER ENERGIE- UND
GELDVERWENDUNG

6. Nachhaltigkeit

„Wird diese Maßnahme in die
Richtung der im ganzheitlichen
Kontext beschriebenen
zukünftigen Ressourcenbasis
führen oder eher weg davon?“

7. Bauchgefühl

„Wie fühle ich mich jetzt mit
dieser Maßnahme? Wird sie
zu der von mir gewünschten
Lebensqualität führen? Wird
sie sich negativ auf das Leben
anderer Personen auswirken?“

## Vorgehen (Datei für Datei)

1. **Inventarisieren**: Alle Dateien in `source/` (inkl. `scenes/` und `qdisplays/`) in Übersetzungsreihenfolge aufnehmen.
2. **Übersetzen**:

   * Jede Datei einzeln patchen, strikt nach obigen Regeln.

   * Auf durchgehende Wortwahl/Terminologie achten, besonders in den Framework-Szenen (WUM/QoL/FRB/Filter Questions).
3. **Sicherheits-Checks währenddessen**:

   * Keine Änderungen an `@scene_id`, `#tags`, Variablennamen, Operatoren, Anführungszeichen in Code-Properties.

   * Doppelte Leerzeile zwischen Properties und Content beibehalten.
4. **Abschluss-Qualitätssicherung**:

   * Suche nach typischen Rest-Englischstellen in `source/` (z.B. „Start“, „Progress“, „Ask for…“, „Whole Under Management“, etc.) und gezielt nachübersetzen.

## Dateien im aktuellen Scope

* `source/info.dry`

* `source/qdisplays/qholtext_progress.qdisplay.dry`

* Alle `source/scenes/*.scene.dry` (inkl. `root`, `progress`, `info`, `credits`, `faq` etc.).

Wenn du den Plan bestätigst, übersetze ich danach konsequent alle Dateien im `source`-Ordner und baue am Ende die HTML-Ausgabe neu.
