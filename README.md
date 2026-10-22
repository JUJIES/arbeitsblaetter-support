# JUJIES Arbeitsblätter

Arbeitsblätter planen, als HTML erstellen und gemeinsam überarbeiten – ein Plugin von [JUJIES](https://github.com/JUJIES) für Lehrkräfte in ChatGPT Work und Codex.

**Öffentliche Pilotversion 0.1.48:** [Download und Kurzanleitung](https://github.com/JUJIES/arbeitsblaetter-support/releases/tag/v0.1.48).

Die vollständige Plugin-ZIP enthält Regeln, Skripte und **13 Arbeitsblattpakete** als Gestaltungs- und Aufgabenreferenzen. Die Quellen sind dadurch in der ZIP einsehbar; sie liegen nicht zusätzlich als entpackter Quellbaum in diesem Repository. Enthalten sind unter anderem Lesetexte, Leseverständnis, Hörvorlagen, Wortschatz-/Schreibaufgaben, Prozessbeschreibungen, Filmbeobachtung und getrennte Lösungen. Nicht jedes Aufgabenformat hat ein eigenes Beispiel; neue Formate bleiben möglich.

## Sprache und Zielgruppe

Der Arbeitsablauf und die Dokumentation sind deutschsprachig ausgerichtet. Das Plugin eignet sich für deutschsprachige Arbeitsblätter und auch für Fremdsprachenunterricht. Englische Beispiele sind bereits enthalten. Andere Arbeitsblattsprachen können ausdrücklich im Auftrag angegeben werden; sprachliche Qualität und landesspezifische Konventionen müssen von einer fachkundigen Lehrkraft geprüft werden. Nicht jede Sprache wurde praktisch getestet.

Beispiel: „Erstelle ein Arbeitsblatt für Französisch, Klasse 8. Die Aufgaben und der Lesetext sollen auf Französisch sein; Rückfragen an mich bitte auf Deutsch.“

Die geplante Region Deutschland für eine spätere Verzeichnisveröffentlichung ist eine Verfügbarkeitseinstellung, keine Beschränkung der möglichen Arbeitsblattsprachen. Dieses öffentliche GitHub-Repository ist weltweit lesbar.

## Start in wenigen Schritten

1. Unter [Releases](https://github.com/JUJIES/arbeitsblaetter-support/releases/tag/v0.1.48) **JUJIES-Arbeitsblaetter-0.1.48-Pilot.zip** herunterladen, nicht „Source code (zip)“. Die Plugin-ZIP nicht entpacken.
2. In ChatGPT **Plugins → Hinzufügen → Plugin-Archiv hochladen** wählen, soweit diese Importfunktion im eigenen Konto vorhanden ist. ZIP auswählen und die angezeigten Installationsschritte abschließen.
3. Einen neuen **Work**-Chat öffnen, **@JUJIES Arbeitsblätter** auswählen und Fach, Klasse, Thema und Lernziel nennen.
4. Kurze Rückfragen beantworten, den Entwurf prüfen und konkrete Änderungen anfordern.
5. Das erzeugte **Arbeitsblatt-Paket** vollständig entpacken und seine Browser-Startdatei öffnen. Dort gibt es **Drucken / PDF** und **Besprechen**.

[Ausführliche Installation und Nutzung](INSTALLATION.md) · [Kurzanleitung mit Screenshots](docs/Kurzanleitung-0.1.40.pdf)

## Was beim Pilottest wichtig ist

Ergebnisse sind KI-gestützte Entwürfe. Fachliche Richtigkeit, Lerngruppenpassung, Bilder und Druckansicht vor dem Unterricht prüfen. HTML ist die Hauptausgabe; „Drucken / PDF“ öffnet den Druckdialog des Browsers. Eine zusätzlich im Chat angefragte PDF und automatische Sichtprüfung hängen von den verfügbaren Werkzeugen ab; fehlen sie, bleibt der Prüfstand offen. Eine einzelne ChatGPT-HTML-Vorschau kann zugehörige Bilder/CSS nicht zuverlässig laden; das vollständige Paket verwenden. Eingaben im Arbeitsblatt werden nicht automatisch dauerhaft gespeichert.

Keine Annahme oder Veröffentlichung im OpenAI-Plugin-Verzeichnis ist damit belegt. Der GitHub-Pilot ist ein separater manueller Verteilungsweg. Neue ZIP-Versionen selbst herunterladen und importieren; keine automatische Aktualisierung zugesichert.

## Support und Hinweise

[Fehler melden oder Frage stellen](https://github.com/JUJIES/arbeitsblaetter-support/issues/new/choose). Bitte Version, verwendete Umgebung, kurze Fehlerbeschreibung und gegebenenfalls anonymisierten Screenshot angeben. **Issues und Anhänge sind öffentlich.** Keine Schülernamen, Gesundheitsdaten, Zugangsdaten oder privaten Chatverläufe posten.

- [Datenschutz](DATENSCHUTZ.md)
- [Nutzung und Rechte](NUTZUNG.md)
- [Änderungsverlauf](CHANGELOG.md)

Dieses Projekt stammt nicht von OpenAI und wird nicht als von OpenAI geprüft oder empfohlen dargestellt.

Die bebilderte Kurzanleitung trägt Stand 0.1.40. Die Installation bleibt gleich; die dortige Schaltfläche „Drucken“ heißt seit 0.1.45 „Drucken / PDF“.
