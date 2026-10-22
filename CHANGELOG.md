# Änderungen

## 0.1.47 – verbundene Prüfschleifen, 22. Oktober 2026

- Seitenplanung, selbst gelöste Aufgaben als Gegenprobe und Rückkopplung in Aufgaben, Lösungen und Schreibraum im bestehenden Ablauf verbindlich verbunden.
- Technische Prüfung und tatsächliche Screenshot-/Druckbildsichtung bleiben getrennte Nachweise. Änderungen erfordern passende Nachprüfung am aktuellen Quellstand.
- Nach Erstprüfung höchstens zwei gebündelte automatische Korrekturrunden; bei Zielkonflikt oder Restfehler offen aussteigen, kein identischer Werkzeug-/Prüfloop.
- Keine neue Regeldatei, keine Änderungen an Laufzeit oder Vorlagen. Praktische Verhaltensproben folgen erst nach Finalisierung; Dokumentationsprüfung allein ist kein Modellnachweis.

## 0.1.46 – leere und stabile Druckfelder, 22. Oktober 2026

- Browserstart setzt Felder zum Drucken auf die ursprüngliche Vorlage zurück und stellt digitale Antworten/Auswahl danach wieder her, auch nach Abbruch. Vorgegebene Lösungen bleiben erhalten.
- Textfeldränder bleiben nach Bearbeitung stabil. Technischer Abschluss prüft zusätzlich, dass unsichtbare Testantworten nicht im PDF-Text enthalten sind.
- Neue echte PDF-Regression mit negativer Leckkontrolle; alle 13 Vorlagen technisch geprüft. Layouts und Materialinhalte unverändert.
- Frischer Work-Download nutzt den exakten neuen Druckcode: beide Feldfehler dort behoben, Papieroptik/Besprechen erhalten. Ein zusätzlicher Seitenüberlauf der Erstfassung wurde nach externem lokalen Prüfbefund im selben Work-Chat korrigiert und lokal mit zwei Seiten bestanden; keine automatische Cloud-Korrektur oder allgemeine Cloud-Druckfreigabe.

## 0.1.45 – einfacher Browserdruck, 22. Oktober 2026

- Kompakter Button „Drucken / PDF“ öffnet den bestehenden Browser-Druckdialog. Dort je nach Gerät als PDF speichern; A4 / 100 % und Kopf-/Fußzeilen aus.
- HTML bleibt Hauptausgabe. PDF auf Wunsch und bei passenden geprüften Werkzeugen; fehlende Cloud-Werkzeuge blockieren die HTML-Lieferung nicht.
- Keine neue Konvertierungsbibliothek: MuPDF/WeasyPrint erhielten bestehende Vorlagen in Cloud-Proben nicht allgemein zuverlässig.
- Alle 13 Vorlagen: Bedienung, Papieroptik, Besprechen, Antwortzustand und identischer Ausdruck geprüft. Inhalte und Layouts unverändert; keine native Mobilgeräteprüfung.


## 0.1.44 – Cloud- und Druckdiagnose, 22. Oktober 2026

- Druckfläche aus CSS ermitteln und mitwachsendes HTML sowie abgeschnittene Inhalte erkennen; Fehler mit Seite und Überlauf in mm. PDF-Seitenzahl und Eingabeprüfung bleiben erhalten.
- Vollständiger Cloud-Laufzeitbericht statt abgeschnittener Downloadfehler; keine zusätzliche identische Installationsschleife.
- Aktuelle Work-Cloud-Proben erhalten vom offiziellen Browser-CDN eine HTML-Fehlerseite. PDF-/Sichtprüfung bleiben dort offen; keine behobene Hostgrenze behauptet.
- Frische Webapp-Proben: kurzes Original lokal bestanden; langes Original hatte weiterhin einen Überlauf. Nach gezieltem lokalen Prüfbefund in der Webapp korrigiert und lokal mit drei Druckseiten bestanden. Vollautomatische Cloud-Korrektur damit nicht nachgewiesen.
- 13 Vorlagen, Look und didaktische Regeln unverändert. Privater Zwischenstand 0.1.43 enthielt einen flüchtigen Prüfcache; vor öffentlicher Verteilung in 0.1.44 entfernt.


## 0.1.42 – erkennbare Materialaufträge, 21. Oktober 2026

- Die bestehende Auftragshervorhebung gilt ausdrücklich auch für Lese-, Hör- und Betrachtungsaufträge auf Materialseiten.
- Ein Gesamtauftrag darf unnummeriert bleiben; keine zusätzliche Aufgabe nötig.
- Vorlagen und Werkzeuge unverändert. Paket- und Browserstartprüfungen bestanden; lokale Beispielrevision geprüft, neue Modellprobe noch offen.


## 0.1.41 – Material und Aufgaben, 21. Oktober 2026

- Umfangreiches Material bevorzugt als luftige Materialseite vor einer zusammenhängenden Aufgabenfolge.
- Entspannte Einseiter und direkt materialbezogene kleine Aufträge bleiben möglich. Keine starre Trennpflicht, Textstreckung oder Restfüller-Aufgabe.
- Gestaltung, 13 Vorlagen und technische Werkzeuge unverändert. Paket- und Browserstartprüfungen bestanden; noch keine frische Modellprobe der neuen Leitlinie.
- Kurzanleitung 0.1.40 bleibt für Installation und Bedienung gültig.


## 0.1.40 – öffentlicher GitHub-Pilot, 21. Oktober 2026

- Vollständige Plugin-ZIP mit 13 Arbeitsblattpaketen als GitHub-Prerelease bereitgestellt.
- Eigenständige Hörvorlagen und Filmillustrationen; Lizenzhinweise für Motorbilder und Sozialform-Icons ergänzt.
- Eigenes Plugin-Icon; Metadaten und Cloud-Prüfgrenzen beschrieben.
- Deutsche Anleitung mit Screenshots, Sprachhinweise und manuelle Updatehinweise ergänzt.
- Geplante Verzeichnisregion: Deutschland. Die Arbeitsblattsprache kann separat gewählt werden.

Lokale Paketprüfungen bestanden. Keine Veröffentlichung oder Annahme im OpenAI-Plugin-Verzeichnis; keine neue Cloud-/Unterrichtsprüfung dieses GitHub-Releases.
