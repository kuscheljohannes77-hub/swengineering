# Software Engineering Fragebogen

Dieses Repository enthaelt nur den interaktiven Software-Engineering-Fragebogen
und die zugehoerigen Checklisten.

## Dateien

- `software-engineering-fragebogen.html`: interaktive Web-App mit Accordions,
  Antwortfeldern, Status, Filter, JSON-Import/Export und Markdown-Export
- `software-engineering-checkliste-kurz-30.md`: kurze Einstiegsversion mit
  30 Kernfragen und Folgefragen
- `software-engineering-checkliste.md`: ausfuehrliche Mastercheckliste

## Lokal starten

Die HTML-Datei laedt die Markdown-Checklisten nach. Deshalb sollte sie ueber
einen kleinen lokalen Server gestartet werden.

```bash
python3 -m http.server 8010
```

Dann im Browser oeffnen:

```text
http://127.0.0.1:8010/software-engineering-fragebogen.html
```

## Antworten speichern

Antworten werden zuerst lokal im Browser gespeichert. Fuer eine dauerhafte
Ablage oder Weitergabe im Team:

1. Fragebogen ausfuellen.
2. `JSON exportieren` klicken.
3. Exportierte JSON-Datei im Projekt oder in einem separaten Arbeitsordner
   ablegen.
4. Spaeter mit `JSON importieren` wieder laden.

Der Markdown-Export ist sinnvoll, wenn die Antworten als lesbares Dokument
weitergegeben oder abgegeben werden sollen.
