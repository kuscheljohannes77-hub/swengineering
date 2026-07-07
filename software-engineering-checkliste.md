# Software Engineering Master-Checkliste

Diese Checkliste ist als Discovery-, Scoping- und Projektplanungs-Fragebogen gedacht. Du kannst sie vor einem Projekt, waehrend der Analyse, im Sprint Planning, bei Reviews oder als Grundlage fuer ein Pflichtenheft benutzen.

Arbeitsweise:

- `[ ]` Frage offen
- `[x]` beantwortet
- `N/A` nicht relevant
- Bei wichtigen Punkten immer Quelle, Entscheidung und Datum notieren.
- Unklare Antworten werden als Risiko oder offene Frage festgehalten.

Empfohlene Ergebnisdokumente:

- Projektsteckbrief
- Stakeholderliste
- Zielbild / Vision
- Kontextdiagramm
- Anforderungsliste
- User Stories
- Use-Case-Diagramm und Use-Case-Beschreibungen
- Aktivitaetsdiagramme fuer Kernprozesse
- Domaenenmodell / Klassendiagramm
- Objektbeispiele
- Sequenzdiagramme fuer wichtige Szenarien
- Zustandsdiagramme fuer wichtige Objekte
- Wireframes
- Dialog Map
- Architekturuebersicht
- Testkonzept
- Deployment- und Betriebskonzept
- Risiko- und Entscheidungslog
- Review-Protokolle

---

## 1. Projektsteckbrief

- [ ] Wie lautet der Projektname?
- [ ] Gibt es einen Arbeitstitel und einen offiziellen Namen?
- [ ] Wer ist Auftraggeber?
- [ ] Wer ist Auftragnehmer?
- [ ] Wer finanziert das Projekt?
- [ ] Wer ist fachlich verantwortlich?
- [ ] Wer ist technisch verantwortlich?
- [ ] Wer trifft finale Entscheidungen?
- [ ] Wann startet das Projekt?
- [ ] Wann soll das Projekt fertig sein?
- [ ] Gibt es feste externe Deadlines?
- [ ] Gibt es interne Meilensteine?
- [ ] Warum wird das Projekt gestartet?
- [ ] Welches konkrete Problem soll geloest werden?
- [ ] Was ist der wichtigste Nutzen?
- [ ] Wer profitiert direkt vom Projekt?
- [ ] Wer profitiert indirekt vom Projekt?
- [ ] Was passiert, wenn das Projekt nicht umgesetzt wird?
- [ ] Was ist der grobe Projektumfang?
- [ ] Was gehoert ausdruecklich nicht zum Projekt?
- [ ] Gibt es ein Budget?
- [ ] Ist das Budget fix oder verhandelbar?
- [ ] Gibt es feste Ressourcen?
- [ ] Gibt es feste Technologien?
- [ ] Gibt es bestehende Systeme, die beruecksichtigt werden muessen?
- [ ] Gibt es bestehende Daten?
- [ ] Gibt es bestehende Prozesse?
- [ ] Gibt es bekannte Risiken?
- [ ] Gibt es rechtliche Rahmenbedingungen?
- [ ] Gibt es organisatorische Rahmenbedingungen?
- [ ] Was waere ein sichtbarer Projekterfolg nach 1 Woche?
- [ ] Was waere ein sichtbarer Projekterfolg nach 1 Monat?
- [ ] Was waere ein sichtbarer Projekterfolg am Projektende?

## 2. Vision, Ziele und Erfolgskriterien

- [ ] Welche Vision beschreibt das fertige Produkt in einem Satz?
- [ ] Welches Hauptziel hat das Produkt?
- [ ] Welche Nebenziele gibt es?
- [ ] Welche Ziele sind messbar?
- [ ] Welche Ziele sind nur qualitativ beschreibbar?
- [ ] Welche Ziele sind Muss-Ziele?
- [ ] Welche Ziele sind Wunsch-Ziele?
- [ ] Welche Ziele widersprechen sich moeglicherweise?
- [ ] Welche Ziele haben Prioritaet, falls Zeit oder Budget knapp werden?
- [ ] Welche Kennzahlen zeigen Projekterfolg?
- [ ] Welche Kennzahlen zeigen Produkterfolg?
- [ ] Welche Kennzahlen zeigen Benutzerzufriedenheit?
- [ ] Welche Kennzahlen zeigen wirtschaftlichen Erfolg?
- [ ] Welche Kennzahlen zeigen technische Qualitaet?
- [ ] Welche Kennzahlen zeigen Betriebsstabilitaet?
- [ ] Wie wird Erfolg gemessen?
- [ ] Wer misst Erfolg?
- [ ] Wann wird Erfolg gemessen?
- [ ] Welche Zielwerte gelten?
- [ ] Welche minimal akzeptablen Zielwerte gelten?
- [ ] Welche Annahmen stecken hinter den Zielen?
- [ ] Wie werden falsche Annahmen erkannt?
- [ ] Welche Ziele koennen spaeter entfallen?
- [ ] Welche Ziele duerfen nicht entfallen?
- [ ] Welche Ziele gehoeren erst in eine spaetere Version?

## 3. Projektart und Vorgehensmodell

- [ ] Ist das Projekt eher neu, erweiternd oder ersetzend?
- [ ] Wird ein bestehendes System modernisiert?
- [ ] Wird ein Prototyp gebaut?
- [ ] Wird ein internes Werkzeug gebaut?
- [ ] Wird ein kundenoffenes Produkt gebaut?
- [ ] Ist der Umfang klar oder noch unscharf?
- [ ] Sind die Anforderungen stabil oder erwartbar veraenderlich?
- [ ] Ist die Technologie bekannt oder neu?
- [ ] Ist die Domaene bekannt oder neu?
- [ ] Ist das Team erfahren oder neu zusammengestellt?
- [ ] Ist ein Wasserfallmodell sinnvoll?
- [ ] Ist ein inkrementelles Vorgehen sinnvoll?
- [ ] Ist ein agiles Vorgehen sinnvoll?
- [ ] Ist ein concurrent/ueberlappendes Vorgehen sinnvoll?
- [ ] Welche Phasen gibt es im Projekt?
- [ ] Welche Artefakte werden pro Phase erwartet?
- [ ] Welche Phase darf erst starten, wenn die vorherige abgeschlossen ist?
- [ ] Welche Phasen duerfen parallel laufen?
- [ ] Welche Entscheidungen muessen frueh getroffen werden?
- [ ] Welche Entscheidungen koennen spaeter getroffen werden?
- [ ] Welche Zwischenergebnisse werden vom Kunden abgenommen?
- [ ] Wann werden Anforderungen eingefroren?
- [ ] Wann werden Designentscheidungen eingefroren?
- [ ] Wann beginnt Implementierung?
- [ ] Wann beginnt Test?
- [ ] Wann beginnt Deployment-Vorbereitung?
- [ ] Wie wird mit Aenderungen umgegangen?
- [ ] Gibt es Change Requests?
- [ ] Wer genehmigt Change Requests?
- [ ] Welche Projektmethode versteht das Team wirklich?

## 4. Stakeholder

- [ ] Wer nutzt die Software direkt?
- [ ] Wer nutzt die Ergebnisse der Software indirekt?
- [ ] Wer bezahlt die Software?
- [ ] Wer betreibt die Software?
- [ ] Wer administriert die Software?
- [ ] Wer entwickelt die Software?
- [ ] Wer testet die Software?
- [ ] Wer nimmt die Software ab?
- [ ] Wer entscheidet ueber Anforderungen?
- [ ] Wer entscheidet ueber Budget?
- [ ] Wer entscheidet ueber Termine?
- [ ] Wer entscheidet ueber Architektur?
- [ ] Wer entscheidet ueber Sicherheit?
- [ ] Wer entscheidet ueber Datenschutz?
- [ ] Wer kann das Projekt blockieren?
- [ ] Wer kann das Projekt beschleunigen?
- [ ] Wer hat fachliches Wissen?
- [ ] Wer hat technisches Wissen?
- [ ] Wer hat Prozesswissen?
- [ ] Wer hat Kundenkontakt?
- [ ] Welche externen Partner gibt es?
- [ ] Welche Lieferanten gibt es?
- [ ] Welche Dienstleister gibt es?
- [ ] Welche Behoerden oder gesetzlichen Stellen sind relevant?
- [ ] Welche Stakeholder haben konkurrierende Interessen?
- [ ] Welche Stakeholder sind schwer erreichbar?
- [ ] Welche Stakeholder muessen regelmaessig informiert werden?
- [ ] Welche Stakeholder muessen nur bei Entscheidungen eingebunden werden?
- [ ] Welche Stakeholder duerfen Anforderungen aendern?
- [ ] Welche Stakeholder haben Vetorecht?

## 5. Benutzergruppen und Personas

- [ ] Welche Benutzergruppen gibt es?
- [ ] Welche Benutzergruppe ist am wichtigsten?
- [ ] Welche Benutzergruppe ist am haeufigsten?
- [ ] Welche Benutzergruppe ist am kritischsten?
- [ ] Welche Aufgaben hat jede Benutzergruppe?
- [ ] Welche Ziele hat jede Benutzergruppe?
- [ ] Welche Probleme hat jede Benutzergruppe heute?
- [ ] Welche Vorkenntnisse hat jede Benutzergruppe?
- [ ] Wie technisch versiert sind die Benutzer?
- [ ] Welche Sprache sprechen die Benutzer?
- [ ] Welche Fachbegriffe verwenden die Benutzer?
- [ ] Welche Geraete verwenden die Benutzer?
- [ ] Arbeiten Benutzer am Desktop?
- [ ] Arbeiten Benutzer mobil?
- [ ] Arbeiten Benutzer mit Tablets?
- [ ] Arbeiten Benutzer unterwegs oder im Buero?
- [ ] Arbeiten Benutzer unter Zeitdruck?
- [ ] Arbeiten Benutzer mit schlechter Internetverbindung?
- [ ] Gibt es Benutzer mit Barrierefreiheitsbedarf?
- [ ] Gibt es Benutzer mit Sehbeeintraechtigungen?
- [ ] Gibt es Benutzer mit motorischen Einschraenkungen?
- [ ] Gibt es Benutzer mit kognitiven Einschraenkungen?
- [ ] Welche Fehler machen Benutzer heute haeufig?
- [ ] Welche Schritte sind fuer Benutzer besonders laestig?
- [ ] Welche Informationen brauchen Benutzer sofort?
- [ ] Welche Informationen brauchen Benutzer nur selten?
- [ ] Welche Funktionen duerfen Benutzer selbst ausfuehren?
- [ ] Welche Funktionen brauchen Freigabe?
- [ ] Welche Benutzer brauchen Schulung?
- [ ] Welche Benutzer koennen als Testpersonen dienen?

## 6. Ist-Zustand und Problemverstaendnis

- [ ] Wie laeuft der aktuelle Prozess?
- [ ] Welche Systeme werden heute genutzt?
- [ ] Welche Dateien werden heute genutzt?
- [ ] Welche Tabellen werden heute genutzt?
- [ ] Welche Papierformulare werden heute genutzt?
- [ ] Welche manuellen Schritte gibt es?
- [ ] Welche Schritte sind doppelt?
- [ ] Welche Schritte sind fehleranfaellig?
- [ ] Welche Schritte dauern zu lange?
- [ ] Welche Informationen gehen verloren?
- [ ] Welche Medienbrueche gibt es?
- [ ] Welche Abteilungen sind beteiligt?
- [ ] Welche Rollen sind beteiligt?
- [ ] Welche Entscheidungen werden im Prozess getroffen?
- [ ] Welche Ausnahmen gibt es?
- [ ] Welche Sonderfaelle kommen selten vor?
- [ ] Welche Sonderfaelle kommen oft vor?
- [ ] Welche Eskalationen gibt es?
- [ ] Welche Fristen gibt es?
- [ ] Welche Wartezeiten gibt es?
- [ ] Wo entstehen Kosten?
- [ ] Wo entstehen Risiken?
- [ ] Wo entstehen Datenschutzprobleme?
- [ ] Wo entstehen Qualitaetsprobleme?
- [ ] Was funktioniert heute gut?
- [ ] Was darf durch das neue System nicht schlechter werden?
- [ ] Welche Altdaten muessen uebernommen werden?
- [ ] Welche alten Prozesse muessen parallel weiterlaufen?
- [ ] Wann wird der alte Prozess abgeschaltet?

## 7. Soll-Prozesse und Aktivitaetsmodellierung

- [ ] Welche Kernprozesse soll das System unterstuetzen?
- [ ] Welche Supportprozesse gibt es?
- [ ] Welche Managementprozesse gibt es?
- [ ] Welche Prozessschritte werden automatisiert?
- [ ] Welche Prozessschritte bleiben manuell?
- [ ] Welche Prozessschritte werden teilautomatisiert?
- [ ] Welche Rollen fuehren welche Schritte aus?
- [ ] Welche Systemaktionen passieren ohne Benutzer?
- [ ] Welche Entscheidungen trifft der Benutzer?
- [ ] Welche Entscheidungen trifft das System?
- [ ] Welche Prozessschritte koennen parallel laufen?
- [ ] Welche Prozessschritte muessen nacheinander laufen?
- [ ] Welche Startpunkte hat der Prozess?
- [ ] Welche Endpunkte hat der Prozess?
- [ ] Welche Abbruchpunkte gibt es?
- [ ] Welche Fehlerpfade gibt es?
- [ ] Welche Genehmigungsschritte gibt es?
- [ ] Welche Benachrichtigungen gibt es?
- [ ] Welche Dokumente entstehen im Prozess?
- [ ] Welche Daten werden im Prozess veraendert?
- [ ] Welche Daten werden im Prozess nur gelesen?
- [ ] Welche Aktivitaetsdiagramme werden benoetigt?
- [ ] Welche Swimlanes werden benoetigt?
- [ ] Welche Varianten des Prozesses gibt es?
- [ ] Welche Prozessvariante kommt am haeufigsten vor?
- [ ] Welche Prozessvariante ist kritisch?
- [ ] Welche Prozessvariante gehoert nicht in Version 1?
- [ ] Woran erkennt man, dass ein Prozess erfolgreich abgeschlossen ist?

## 8. Systemkontext und Systemgrenze

- [ ] Was gehoert zum System?
- [ ] Was gehoert nicht zum System?
- [ ] Welche externen Personen interagieren mit dem System?
- [ ] Welche externen Systeme interagieren mit dem System?
- [ ] Welche Organisationen interagieren mit dem System?
- [ ] Welche Daten fliessen in das System hinein?
- [ ] Welche Daten fliessen aus dem System heraus?
- [ ] Welche Ereignisse starten Systemaktionen?
- [ ] Welche Schnittstellen liegen ausserhalb der eigenen Kontrolle?
- [ ] Welche Funktionen werden bewusst nicht gebaut?
- [ ] Welche Funktionen werden von Fremdsystemen erbracht?
- [ ] Welche Verantwortung hat das eigene System?
- [ ] Welche Verantwortung hat ein Fremdsystem?
- [ ] Welche Verantwortung hat ein Benutzer?
- [ ] Gibt es mehrere Systemversionen?
- [ ] Gibt es eine Minimalversion?
- [ ] Gibt es spaetere Ausbaustufen?
- [ ] Welche Kontextdiagramme werden benoetigt?
- [ ] Welche Annahmen zur Systemumgebung gibt es?
- [ ] Was passiert, wenn ein externes System nicht erreichbar ist?
- [ ] Was passiert, wenn ein externer Datenlieferant falsche Daten liefert?
- [ ] Welche Systemgrenzen sind fachlich unklar?
- [ ] Welche Systemgrenzen sind technisch unklar?

## 9. Anforderungen allgemein

- [ ] Welche Anforderungen sind bereits bekannt?
- [ ] Welche Anforderungen sind noch Vermutungen?
- [ ] Welche Anforderungen stammen vom Kunden?
- [ ] Welche Anforderungen stammen von Benutzern?
- [ ] Welche Anforderungen stammen aus Gesetzen?
- [ ] Welche Anforderungen stammen aus bestehenden Systemen?
- [ ] Welche Anforderungen stammen aus Prozessen?
- [ ] Welche Anforderungen stammen aus technischen Randbedingungen?
- [ ] Welche Anforderungen sind funktional?
- [ ] Welche Anforderungen sind qualitativ?
- [ ] Welche Anforderungen sind organisatorisch?
- [ ] Welche Anforderungen sind rechtlich?
- [ ] Welche Anforderungen sind technisch?
- [ ] Welche Anforderungen sind Muss?
- [ ] Welche Anforderungen sind Soll?
- [ ] Welche Anforderungen sind Kann?
- [ ] Welche Anforderungen sind Nice-to-have?
- [ ] Welche Anforderungen sind widerspruechlich?
- [ ] Welche Anforderungen sind unklar formuliert?
- [ ] Welche Anforderungen sind nicht testbar?
- [ ] Welche Anforderungen sind zu allgemein?
- [ ] Welche Anforderungen enthalten mehrere Aussagen gleichzeitig?
- [ ] Welche Anforderungen benutzen unklare Woerter wie "schnell", "einfach", "modern"?
- [ ] Welche Anforderungen brauchen messbare Kriterien?
- [ ] Welche Anforderungen brauchen Akzeptanzkriterien?
- [ ] Welche Anforderungen brauchen Beispiele?
- [ ] Welche Anforderungen brauchen Gegenbeispiele?
- [ ] Welche Anforderungen muessen priorisiert werden?
- [ ] Welche Anforderungen gehoeren nicht in den Projektumfang?
- [ ] Welche Anforderungen werden in Version 1 umgesetzt?
- [ ] Welche Anforderungen werden spaeter umgesetzt?
- [ ] Welche Anforderungen sind Voraussetzung fuer andere?
- [ ] Welche Anforderungen blockieren andere Arbeiten?
- [ ] Wie werden Anforderungen versioniert?
- [ ] Wie werden Anforderungen freigegeben?
- [ ] Wie werden Anforderungen geaendert?

## 10. Funktionale Anforderungen

- [ ] Welche Funktionen muss das System anbieten?
- [ ] Welche Funktionen muessen Benutzer direkt ausloesen?
- [ ] Welche Funktionen laufen automatisch?
- [ ] Welche Funktionen laufen zeitgesteuert?
- [ ] Welche Funktionen laufen ereignisgesteuert?
- [ ] Welche Daten werden pro Funktion benoetigt?
- [ ] Welche Daten erzeugt jede Funktion?
- [ ] Welche Funktion veraendert Daten?
- [ ] Welche Funktion loescht Daten?
- [ ] Welche Funktion exportiert Daten?
- [ ] Welche Funktion importiert Daten?
- [ ] Welche Funktion informiert andere Benutzer?
- [ ] Welche Funktion informiert externe Systeme?
- [ ] Welche Funktion braucht Freigabe?
- [ ] Welche Funktion braucht Protokollierung?
- [ ] Welche Funktion braucht Rollenpruefung?
- [ ] Welche Funktion ist kritisch fuer den Geschaeftsbetrieb?
- [ ] Welche Funktion wird sehr haeufig genutzt?
- [ ] Welche Funktion wird selten genutzt?
- [ ] Welche Funktion muss besonders einfach sein?
- [ ] Welche Funktion darf komplexer sein, weil sie selten genutzt wird?
- [ ] Welche Funktion darf nie ohne Bestaetigung ausgefuehrt werden?
- [ ] Welche Funktion braucht Undo oder Rueckgaengigmachen?
- [ ] Welche Funktion braucht Entwurf/Speichern/Fortsetzen?
- [ ] Welche Funktion braucht Suche?
- [ ] Welche Funktion braucht Filter?
- [ ] Welche Funktion braucht Sortierung?
- [ ] Welche Funktion braucht Massenbearbeitung?
- [ ] Welche Funktion braucht Import/Export?
- [ ] Welche Funktion braucht Druck/PDF?
- [ ] Welche Funktion braucht Benachrichtigungen?
- [ ] Welche Funktion braucht Historie?
- [ ] Welche Funktion braucht Kommentare?
- [ ] Welche Funktion braucht Anhänge?

## 11. Nicht-funktionale Anforderungen und Qualitaetsmerkmale

- [ ] Welche Antwortzeiten werden erwartet?
- [ ] Welche Antwortzeiten sind maximal akzeptabel?
- [ ] Wie viele Benutzer arbeiten gleichzeitig?
- [ ] Wie viele Datensaetze werden erwartet?
- [ ] Wie stark wachsen die Daten?
- [ ] Welche Verfuegbarkeit wird erwartet?
- [ ] Welche Ausfallzeiten sind akzeptabel?
- [ ] Welche Wartungsfenster sind erlaubt?
- [ ] Wie wichtig ist Bedienbarkeit?
- [ ] Wie wichtig ist Barrierefreiheit?
- [ ] Wie wichtig ist Sicherheit?
- [ ] Wie wichtig ist Datenschutz?
- [ ] Wie wichtig ist Performance?
- [ ] Wie wichtig ist Skalierbarkeit?
- [ ] Wie wichtig ist Wartbarkeit?
- [ ] Wie wichtig ist Erweiterbarkeit?
- [ ] Wie wichtig ist Portierbarkeit?
- [ ] Wie wichtig ist Kompatibilitaet?
- [ ] Wie wichtig ist Testbarkeit?
- [ ] Wie wichtig ist Nachvollziehbarkeit?
- [ ] Welche Qualitaetsanforderungen sind messbar?
- [ ] Welche Qualitaetsanforderungen brauchen konkrete Grenzwerte?
- [ ] Welche Qualitaetsanforderungen koennen durch Tests nachgewiesen werden?
- [ ] Welche Qualitaetsanforderungen koennen durch Reviews nachgewiesen werden?
- [ ] Welche Qualitaetsanforderungen koennen durch Monitoring nachgewiesen werden?
- [ ] Welche Qualitaetsanforderungen sind fuer Version 1 zwingend?
- [ ] Welche Qualitaetsanforderungen koennen spaeter verbessert werden?

## 12. User Stories

- [ ] Welche Benutzerrolle steht in der Story?
- [ ] Welches Ziel hat die Benutzerrolle?
- [ ] Welcher Nutzen wird genannt?
- [ ] Ist die Story aus Benutzersicht formuliert?
- [ ] Ist die Story klein genug?
- [ ] Ist die Story unabhaengig genug?
- [ ] Ist die Story verhandelbar?
- [ ] Ist die Story wertvoll?
- [ ] Ist die Story schaetzbar?
- [ ] Ist die Story testbar?
- [ ] Hat die Story Akzeptanzkriterien?
- [ ] Gibt es Beispiele fuer erfolgreiche Nutzung?
- [ ] Gibt es Beispiele fuer Fehlerfaelle?
- [ ] Gibt es fachliche Regeln?
- [ ] Gibt es technische Einschraenkungen?
- [ ] Gibt es UI-Hinweise?
- [ ] Gibt es Datenschutz-Hinweise?
- [ ] Gibt es Sicherheits-Hinweise?
- [ ] Gibt es Performance-Hinweise?
- [ ] Gibt es Abhaengigkeiten zu anderen Stories?
- [ ] Gibt es offene Fragen zur Story?
- [ ] Ist die Story einem Ziel zugeordnet?
- [ ] Ist die Story einer Version zugeordnet?
- [ ] Ist die Story priorisiert?
- [ ] Ist die Story vom Product Owner bestaetigt?

## 13. Use Cases

- [ ] Welche Akteure gibt es?
- [ ] Welche Akteure sind Menschen?
- [ ] Welche Akteure sind externe Systeme?
- [ ] Welche Akteure sind primaere Akteure?
- [ ] Welche Akteure sind sekundaere Akteure?
- [ ] Welche Ziele verfolgen die Akteure?
- [ ] Welche Use Cases ergeben sich aus den Zielen?
- [ ] Welche Use Cases sind Kernfunktionen?
- [ ] Welche Use Cases sind Hilfsfunktionen?
- [ ] Welche Use Cases sind administrativ?
- [ ] Welche Use Cases sind fuer Version 1 noetig?
- [ ] Welche Use Cases koennen spaeter kommen?
- [ ] Hat jeder Use Case einen klaren Namen?
- [ ] Hat jeder Use Case einen Ausloeser?
- [ ] Hat jeder Use Case Vorbedingungen?
- [ ] Hat jeder Use Case Nachbedingungen?
- [ ] Hat jeder Use Case ein Hauptszenario?
- [ ] Hat jeder Use Case alternative Szenarien?
- [ ] Hat jeder Use Case Fehlerszenarien?
- [ ] Hat jeder Use Case beteiligte Akteure?
- [ ] Hat jeder Use Case fachliche Regeln?
- [ ] Hat jeder Use Case Akzeptanzkriterien?
- [ ] Gibt es Include-Beziehungen?
- [ ] Gibt es Extend-Beziehungen?
- [ ] Sind Include/Extend wirklich sinnvoll oder nur Deko?
- [ ] Ist die Systemgrenze im Use-Case-Diagramm klar?
- [ ] Sind alle Akteure ausserhalb der Systemgrenze?
- [ ] Sind alle Use Cases innerhalb der Systemgrenze?
- [ ] Ist das Use-Case-Diagramm fuer Fachleute verstaendlich?

## 14. Domaenenmodell, Begriffe und Glossar

- [ ] Welche wichtigen Fachbegriffe gibt es?
- [ ] Welche Begriffe werden unterschiedlich verwendet?
- [ ] Welche Synonyme gibt es?
- [ ] Welche Begriffe duerfen nicht verwechselt werden?
- [ ] Welche Objekte existieren in der Fachwelt?
- [ ] Welche Objekte sind nur technische Hilfsobjekte?
- [ ] Welche Objekte haben eine Identitaet?
- [ ] Welche Objekte haben einen Lebenszyklus?
- [ ] Welche Objekte enthalten andere Objekte?
- [ ] Welche Objekte referenzieren andere Objekte?
- [ ] Welche Attribute hat jedes Objekt?
- [ ] Welche Attribute sind Pflicht?
- [ ] Welche Attribute sind optional?
- [ ] Welche Attribute sind berechnet?
- [ ] Welche Attribute sind historisiert?
- [ ] Welche Regeln gelten fuer Attribute?
- [ ] Welche Beziehungen gibt es zwischen Objekten?
- [ ] Welche Kardinalitaeten gelten?
- [ ] Welche Beziehungen sind Kompositionen?
- [ ] Welche Beziehungen sind Aggregationen?
- [ ] Welche Beziehungen sind einfache Assoziationen?
- [ ] Welche Vererbungen gibt es?
- [ ] Sind Vererbungen fachlich sinnvoll?
- [ ] Welche Klassen gehoeren ins Domaenenmodell?
- [ ] Welche Klassen gehoeren eher ins technische Design?
- [ ] Gibt es Beispielobjekte fuer typische Faelle?
- [ ] Gibt es Beispielobjekte fuer Grenzfaelle?
- [ ] Gibt es ein Glossar mit klaren Definitionen?

## 15. Daten und Datenmodell

- [ ] Welche Daten werden gespeichert?
- [ ] Welche Daten werden nur angezeigt?
- [ ] Welche Daten werden importiert?
- [ ] Welche Daten werden exportiert?
- [ ] Welche Daten werden berechnet?
- [ ] Welche Daten werden protokolliert?
- [ ] Welche Daten sind personenbezogen?
- [ ] Welche Daten sind besonders schuetzenswert?
- [ ] Welche Daten sind oeffentlich?
- [ ] Welche Daten sind intern?
- [ ] Welche Daten sind vertraulich?
- [ ] Welche Datenquelle ist fuehrend?
- [ ] Woher stammen die Daten?
- [ ] Wer darf Daten anlegen?
- [ ] Wer darf Daten lesen?
- [ ] Wer darf Daten aendern?
- [ ] Wer darf Daten loeschen?
- [ ] Wer darf Daten exportieren?
- [ ] Wie lange werden Daten gespeichert?
- [ ] Wann muessen Daten geloescht werden?
- [ ] Wann muessen Daten archiviert werden?
- [ ] Welche Daten muessen versioniert werden?
- [ ] Welche Daten muessen historisiert werden?
- [ ] Welche Daten brauchen Audit-Trails?
- [ ] Welche Daten brauchen Plausibilitaetspruefungen?
- [ ] Welche Daten duerfen leer sein?
- [ ] Welche Daten muessen eindeutig sein?
- [ ] Welche Daten brauchen Indizes?
- [ ] Welche Daten werden sehr haeufig gesucht?
- [ ] Welche Daten werden sehr haeufig geaendert?
- [ ] Welche Datenmengen werden erwartet?
- [ ] Welche Datenmigration ist notwendig?
- [ ] Welche Altdaten sind fehlerhaft?
- [ ] Welche Altdaten sollen bereinigt werden?

## 16. Szenarien, Sequenzen und Systemverhalten

- [ ] Welche Hauptszenarien muessen detailliert beschrieben werden?
- [ ] Welche Fehlerszenarien muessen beschrieben werden?
- [ ] Welche Alternativszenarien muessen beschrieben werden?
- [ ] Welche Beteiligten tauschen Nachrichten aus?
- [ ] Welche Systemkomponenten sind beteiligt?
- [ ] Welche externen Systeme sind beteiligt?
- [ ] Welche Reihenfolge haben die Nachrichten?
- [ ] Welche Nachricht loest welche Reaktion aus?
- [ ] Welche Antwort erwartet der Benutzer?
- [ ] Welche Antwort erwartet ein Fremdsystem?
- [ ] Welche Verarbeitung laeuft synchron?
- [ ] Welche Verarbeitung laeuft asynchron?
- [ ] Welche Verarbeitung kann laenger dauern?
- [ ] Wo braucht es Ladezustaende?
- [ ] Wo braucht es Fortschrittsanzeigen?
- [ ] Wo braucht es Timeouts?
- [ ] Wo braucht es Wiederholungen?
- [ ] Wo braucht es Transaktionen?
- [ ] Was passiert bei Teilfehlern?
- [ ] Was passiert bei Netzwerkfehlern?
- [ ] Was passiert bei gesperrten Daten?
- [ ] Welche Sequenzdiagramme sind hilfreich?
- [ ] Welche Szenarien muessen mit Kunden validiert werden?

## 17. Zustaende und Lebenszyklen

- [ ] Welche Objekte haben wichtige Zustaende?
- [ ] Welche Statuswerte gibt es?
- [ ] Welche Statuswerte sind fachlich sichtbar?
- [ ] Welche Statuswerte sind nur technisch?
- [ ] Was ist der Startzustand?
- [ ] Was sind Endzustaende?
- [ ] Welche Zustaende sind Zwischenzustaende?
- [ ] Welche Ereignisse loesen Zustandswechsel aus?
- [ ] Welche Bedingungen muessen fuer Zustandswechsel gelten?
- [ ] Welche Aktionen passieren beim Zustandswechsel?
- [ ] Welche Zustandswechsel sind verboten?
- [ ] Welche Zustandswechsel brauchen Berechtigung?
- [ ] Welche Zustandswechsel brauchen Freigabe?
- [ ] Welche Zustandswechsel werden protokolliert?
- [ ] Kann ein Zustand rueckgaengig gemacht werden?
- [ ] Gibt es parallele Zustaende?
- [ ] Gibt es automatische Zustandswechsel?
- [ ] Gibt es zeitgesteuerte Zustandswechsel?
- [ ] Welche Zustandsdiagramme werden benoetigt?
- [ ] Sind alle Statuswerte fuer Benutzer verstaendlich benannt?

## 18. UI, UX, Wireframes und Dialoge

- [ ] Welche Hauptansichten braucht das System?
- [ ] Welche Nebenansichten braucht das System?
- [ ] Welche Dialoge braucht das System?
- [ ] Welche Popups oder Modale braucht das System?
- [ ] Welche Formulare braucht das System?
- [ ] Welche Listen braucht das System?
- [ ] Welche Detailseiten braucht das System?
- [ ] Welche Dashboards braucht das System?
- [ ] Welche Navigation ist notwendig?
- [ ] Welche Informationen muessen sofort sichtbar sein?
- [ ] Welche Informationen koennen versteckt sein?
- [ ] Welche Aktionen sind primaer?
- [ ] Welche Aktionen sind sekundaer?
- [ ] Welche Aktionen sind gefaehrlich?
- [ ] Welche Aktionen brauchen Bestaetigung?
- [ ] Welche Eingabefelder sind Pflicht?
- [ ] Welche Eingabefelder sind optional?
- [ ] Welche Eingabefelder brauchen Validierung?
- [ ] Welche Fehlermeldungen braucht das System?
- [ ] Welche Erfolgsmeldungen braucht das System?
- [ ] Welche Leere-Zustaende gibt es?
- [ ] Welche Ladezustaende gibt es?
- [ ] Welche Rollen sehen welche UI-Elemente?
- [ ] Welche Geraetegroessen muessen unterstuetzt werden?
- [ ] Welche Tastaturbedienung ist wichtig?
- [ ] Welche Screenreader-Anforderungen gibt es?
- [ ] Welche Sprache und Tonalitaet soll die UI nutzen?
- [ ] Welche Wireframes werden benoetigt?
- [ ] Welche Wireframes muessen mit Benutzern getestet werden?
- [ ] Welche Dialog Map beschreibt die Navigation?
- [ ] Welche Buttons fuehren zu welchem Dialog?
- [ ] Welche Dialoge koennen abgebrochen werden?
- [ ] Welche Dialoge duerfen keine Daten verlieren?

## 19. Sicherheit, Rollen und Berechtigungen

- [ ] Wer darf sich anmelden?
- [ ] Gibt es anonyme Benutzer?
- [ ] Gibt es registrierte Benutzer?
- [ ] Gibt es Administratoren?
- [ ] Gibt es externe Benutzer?
- [ ] Wie erfolgt Authentifizierung?
- [ ] Gibt es Single Sign-on?
- [ ] Gibt es Zwei-Faktor-Authentifizierung?
- [ ] Wie werden Passwoerter behandelt?
- [ ] Welche Rollen gibt es?
- [ ] Welche Rechte hat jede Rolle?
- [ ] Welche Rechte sind objektbezogen?
- [ ] Welche Rechte sind mandantenbezogen?
- [ ] Welche Rechte sind zeitlich begrenzt?
- [ ] Wer darf Rollen vergeben?
- [ ] Wer darf Rollen entziehen?
- [ ] Welche Aktionen brauchen besondere Berechtigung?
- [ ] Welche Daten muessen verschluesselt werden?
- [ ] Welche Daten muessen beim Transport verschluesselt werden?
- [ ] Welche Daten muessen im Speicher verschluesselt werden?
- [ ] Welche Sicherheitsereignisse werden protokolliert?
- [ ] Welche Angriffsszenarien sind relevant?
- [ ] Wie wird gegen unberechtigten Zugriff geschuetzt?
- [ ] Wie wird gegen Datenmanipulation geschuetzt?
- [ ] Wie wird gegen Injection-Angriffe geschuetzt?
- [ ] Wie wird gegen Cross-Site-Scripting geschuetzt?
- [ ] Wie wird gegen Cross-Site-Request-Forgery geschuetzt?
- [ ] Wie wird gegen Brute Force geschuetzt?
- [ ] Wie werden Sessions beendet?
- [ ] Wie werden API-Zugriffe abgesichert?

## 20. Datenschutz, Recht und Compliance

- [ ] Welche personenbezogenen Daten werden verarbeitet?
- [ ] Welche besonderen Kategorien personenbezogener Daten gibt es?
- [ ] Welche Rechtsgrundlage gilt?
- [ ] Gibt es Einwilligungen?
- [ ] Wie werden Einwilligungen dokumentiert?
- [ ] Wie koennen Einwilligungen widerrufen werden?
- [ ] Welche Informationspflichten bestehen?
- [ ] Welche Auskunftsrechte muessen unterstuetzt werden?
- [ ] Welche Loeschrechte muessen unterstuetzt werden?
- [ ] Welche Berichtigungsrechte muessen unterstuetzt werden?
- [ ] Welche Datenportabilitaet ist notwendig?
- [ ] Gibt es Auftragsverarbeitung?
- [ ] Gibt es Drittlanduebermittlungen?
- [ ] Gibt es eine Datenschutz-Folgenabschaetzung?
- [ ] Welche Aufbewahrungsfristen gelten?
- [ ] Welche Loeschfristen gelten?
- [ ] Welche Archivierungspflichten gelten?
- [ ] Welche Branchenvorschriften gelten?
- [ ] Welche Lizenzbedingungen gelten?
- [ ] Welche Open-Source-Lizenzen werden verwendet?
- [ ] Welche Impressums- oder Anbieterkennzeichnungspflichten gibt es?
- [ ] Welche Barrierefreiheitsgesetze koennen relevant sein?
- [ ] Welche Nachweise muessen bei Audits vorliegen?

## 21. Schnittstellen und Integrationen

- [ ] Mit welchen Systemen muss kommuniziert werden?
- [ ] Welche Systeme liefern Daten?
- [ ] Welche Systeme empfangen Daten?
- [ ] Welche APIs existieren bereits?
- [ ] Welche APIs muessen neu gebaut werden?
- [ ] Wer besitzt die API?
- [ ] Wer dokumentiert die API?
- [ ] Welche Authentifizierung nutzt die API?
- [ ] Welche Autorisierung nutzt die API?
- [ ] Welche Datenformate werden verwendet?
- [ ] Wird JSON verwendet?
- [ ] Wird XML verwendet?
- [ ] Wird CSV verwendet?
- [ ] Wird ein proprietaeres Format verwendet?
- [ ] Welche Protokolle werden verwendet?
- [ ] Gibt es Webhooks?
- [ ] Gibt es Message Queues?
- [ ] Gibt es Batch-Importe?
- [ ] Gibt es Dateiablagen?
- [ ] Gibt es Rate Limits?
- [ ] Gibt es Groessenlimits?
- [ ] Gibt es Timeouts?
- [ ] Gibt es Retry-Regeln?
- [ ] Gibt es Versionierung der Schnittstelle?
- [ ] Gibt es Testumgebungen der Schnittstellen?
- [ ] Gibt es Mock-Systeme?
- [ ] Was passiert bei Schnittstellenfehlern?
- [ ] Wie werden Schnittstellenfehler sichtbar?
- [ ] Wie werden Schnittstellen vertraglich abgesichert?

## 22. Architektur und technische Entscheidungen

- [ ] Welche Architekturform ist passend?
- [ ] Ist ein Monolith passend?
- [ ] Sind Microservices passend?
- [ ] Ist eine modulare Architektur passend?
- [ ] Ist eine Client-Server-Architektur passend?
- [ ] Ist eine Event-getriebene Architektur passend?
- [ ] Welche Programmiersprache wird verwendet?
- [ ] Welches Framework wird verwendet?
- [ ] Welche Datenbank wird verwendet?
- [ ] Welche Frontend-Technologie wird verwendet?
- [ ] Welche Backend-Technologie wird verwendet?
- [ ] Welche Mobile-Technologie wird verwendet?
- [ ] Welche Cloud-Plattform wird verwendet?
- [ ] Wird On-Premises betrieben?
- [ ] Werden Container verwendet?
- [ ] Wird Kubernetes verwendet?
- [ ] Wird eine Message Queue verwendet?
- [ ] Wird Caching verwendet?
- [ ] Wird ein Suchindex verwendet?
- [ ] Wird ein Dateispeicher verwendet?
- [ ] Welche Architekturentscheidungen muessen dokumentiert werden?
- [ ] Welche Architecture Decision Records werden benoetigt?
- [ ] Welche technischen Risiken gibt es?
- [ ] Welche Technologien kennt das Team bereits?
- [ ] Welche Technologien muss das Team lernen?
- [ ] Welche Standards gelten im Unternehmen?
- [ ] Welche Abhaengigkeiten zu Lieferanten entstehen?
- [ ] Welche Komponenten sind kritisch?
- [ ] Welche Komponenten koennen spaeter ausgetauscht werden?
- [ ] Welche Architekturqualitaeten sind besonders wichtig?

## 23. Implementierung und Codeorganisation

- [ ] Welche Repository-Struktur wird verwendet?
- [ ] Welche Module gibt es?
- [ ] Welche Pakete gibt es?
- [ ] Welche Namenskonventionen gelten?
- [ ] Welche Coding Standards gelten?
- [ ] Welche Formatierung wird verwendet?
- [ ] Welche Linter werden verwendet?
- [ ] Welche statische Analyse wird verwendet?
- [ ] Welche Branching-Strategie wird verwendet?
- [ ] Welche Commit-Konvention wird verwendet?
- [ ] Welche Pull-Request-Regeln gelten?
- [ ] Welche Definition of Done gilt fuer Code?
- [ ] Welche Fehlerbehandlung wird verwendet?
- [ ] Welche Logging-Konventionen gelten?
- [ ] Welche Konfigurationsdateien gibt es?
- [ ] Welche Secrets duerfen nie ins Repository?
- [ ] Welche Umgebungsvariablen gibt es?
- [ ] Welche lokalen Entwicklungsdaten werden benoetigt?
- [ ] Wie wird die Entwicklungsumgebung eingerichtet?
- [ ] Wie startet man das Projekt lokal?
- [ ] Wie fuehrt man Tests lokal aus?
- [ ] Wie baut man ein Release lokal?
- [ ] Welche technischen Schulden sind erlaubt?
- [ ] Wie werden technische Schulden dokumentiert?

## 24. Konfigurationsmanagement und Versionierung

- [ ] Wo liegt das Git-Repository?
- [ ] Wer hat Zugriff?
- [ ] Welche Rollen gibt es im Repository?
- [ ] Welche Branches gibt es?
- [ ] Was ist der Hauptbranch?
- [ ] Wie werden Feature-Branches benannt?
- [ ] Wie werden Releases getaggt?
- [ ] Wie werden Hotfixes behandelt?
- [ ] Wie werden Merge-Konflikte geloest?
- [ ] Wer darf direkt in Hauptbranches mergen?
- [ ] Welche Dateien werden versioniert?
- [ ] Welche Dateien werden ignoriert?
- [ ] Welche Konfiguration ist environment-spezifisch?
- [ ] Welche Artefakte werden gebaut?
- [ ] Welche Artefakte werden gespeichert?
- [ ] Welche Abhaengigkeiten werden fixiert?
- [ ] Wie werden Dependency-Updates durchgefuehrt?
- [ ] Wie werden Versionen nummeriert?
- [ ] Wie werden Releases dokumentiert?
- [ ] Wie wird nachvollziehbar, welche Version wo laeuft?
- [ ] Wie wird nachvollziehbar, welche Anforderung in welcher Version umgesetzt ist?

## 25. Tests und Qualitaetssicherung

- [ ] Welche Teststufen gibt es?
- [ ] Gibt es Unit Tests?
- [ ] Gibt es Integrationstests?
- [ ] Gibt es Systemtests?
- [ ] Gibt es Akzeptanztests?
- [ ] Gibt es Regressionstests?
- [ ] Gibt es Smoke Tests?
- [ ] Gibt es Performance Tests?
- [ ] Gibt es Sicherheitstests?
- [ ] Gibt es Usability Tests?
- [ ] Gibt es Barrierefreiheitstests?
- [ ] Welche Anforderungen haben Testfaelle?
- [ ] Welche User Stories haben Akzeptanztests?
- [ ] Welche Use Cases haben Szenario-Tests?
- [ ] Welche Schnittstellen haben Vertragstests?
- [ ] Welche kritischen Pfade werden automatisiert getestet?
- [ ] Welche Tests laufen bei jedem Commit?
- [ ] Welche Tests laufen vor jedem Release?
- [ ] Welche Tests laufen manuell?
- [ ] Welche Testdaten werden benoetigt?
- [ ] Welche Testumgebungen werden benoetigt?
- [ ] Wer schreibt Tests?
- [ ] Wer fuehrt Tests aus?
- [ ] Wer bewertet Testergebnisse?
- [ ] Was passiert bei fehlgeschlagenen Tests?
- [ ] Welche Fehlerschweregrade gibt es?
- [ ] Welche Fehler blockieren ein Release?
- [ ] Wie wird Testabdeckung gemessen?
- [ ] Welche Qualitaetskosten entstehen durch Fehler spaet im Projekt?
- [ ] Wie wird verhindert, dass Fehler erst spaet gefunden werden?

## 26. Reviews und Inspektionen

- [ ] Welche Artefakte werden reviewed?
- [ ] Werden Anforderungen reviewed?
- [ ] Werden Modelle reviewed?
- [ ] Werden Wireframes reviewed?
- [ ] Wird Architektur reviewed?
- [ ] Wird Code reviewed?
- [ ] Werden Tests reviewed?
- [ ] Werden Dokumentationen reviewed?
- [ ] Welche Review-Methode wird genutzt?
- [ ] Gibt es formale Inspektionen?
- [ ] Gibt es Checklisten fuer Reviews?
- [ ] Wer ist Moderator?
- [ ] Wer ist Autor?
- [ ] Wer ist Reviewer?
- [ ] Wer protokolliert?
- [ ] Welche Quellen werden beim Review verwendet?
- [ ] Welche Fehlerklassen werden gesucht?
- [ ] Welche Schweregrade gibt es?
- [ ] Wie werden Findings dokumentiert?
- [ ] Wie werden Findings priorisiert?
- [ ] Wie wird Nacharbeit verfolgt?
- [ ] Wann gilt ein Review als abgeschlossen?
- [ ] Welche Review-Regeln gelten?
- [ ] Wie wird verhindert, dass Reviews persoenlich werden?
- [ ] Wie wird sichergestellt, dass Reviews wirklich Fehler finden?

## 27. Deployment, Release und Rollback

- [ ] Wo laeuft die Software?
- [ ] Welche Umgebungen gibt es?
- [ ] Gibt es Development?
- [ ] Gibt es Test?
- [ ] Gibt es Staging?
- [ ] Gibt es Production?
- [ ] Wie unterscheiden sich die Umgebungen?
- [ ] Wer installiert die Software?
- [ ] Wer aktualisiert die Software?
- [ ] Wie wird ein Release gebaut?
- [ ] Wie wird ein Release veroeffentlicht?
- [ ] Gibt es CI/CD?
- [ ] Welche Pipeline-Schritte gibt es?
- [ ] Welche Freigaben sind vor Production noetig?
- [ ] Gibt es Datenbankmigrationen?
- [ ] Wie werden Migrationen getestet?
- [ ] Wie wird ein Rollback gemacht?
- [ ] Was passiert mit Daten bei Rollback?
- [ ] Gibt es Feature Flags?
- [ ] Gibt es Blue-Green Deployment?
- [ ] Gibt es Canary Releases?
- [ ] Wie werden Benutzer ueber Releases informiert?
- [ ] Wie werden Release Notes erstellt?
- [ ] Welche Downtime ist erlaubt?
- [ ] Wie wird nach Deployment validiert?

## 28. Betrieb, Monitoring und Support

- [ ] Wer betreibt das System?
- [ ] Wer ist fachlicher Support?
- [ ] Wer ist technischer Support?
- [ ] Welche Servicezeiten gelten?
- [ ] Gibt es Bereitschaft?
- [ ] Welche Verfuegbarkeit wird zugesichert?
- [ ] Welche SLAs gelten?
- [ ] Welche Metriken werden ueberwacht?
- [ ] Welche Logs werden geschrieben?
- [ ] Wo werden Logs gespeichert?
- [ ] Wie lange werden Logs gespeichert?
- [ ] Welche Alarme gibt es?
- [ ] Wer bekommt Alarme?
- [ ] Was passiert bei Alarmen?
- [ ] Welche Dashboards gibt es?
- [ ] Welche Health Checks gibt es?
- [ ] Welche Backups gibt es?
- [ ] Wie oft werden Backups erstellt?
- [ ] Wie werden Restores getestet?
- [ ] Welche Notfallplaene gibt es?
- [ ] Wie werden Fehler gemeldet?
- [ ] Wie werden Fehler priorisiert?
- [ ] Wie werden Fehler behoben?
- [ ] Wie werden Workarounds kommuniziert?
- [ ] Wie werden Wartungsarbeiten geplant?

## 29. Projektmanagement, Planung und Aufwand

- [ ] Welche Arbeitspakete gibt es?
- [ ] Welche Meilensteine gibt es?
- [ ] Welche Lieferobjekte gibt es?
- [ ] Welche Abhaengigkeiten gibt es?
- [ ] Welche Aufgaben koennen parallel laufen?
- [ ] Welche Aufgaben blockieren andere?
- [ ] Welche Rollen werden benoetigt?
- [ ] Welche Personen sind verfuegbar?
- [ ] Wie viel Zeit haben die Personen?
- [ ] Welche Skills fehlen?
- [ ] Welche externen Ressourcen werden benoetigt?
- [ ] Welche Aufwandsschaetzung gibt es?
- [ ] Welche Schaetzmethode wird verwendet?
- [ ] Welche Unsicherheiten stecken in der Schaetzung?
- [ ] Welche Puffer gibt es?
- [ ] Welche kritischen Pfade gibt es?
- [ ] Welche Termine sind realistisch?
- [ ] Welche Termine sind Wunschtermine?
- [ ] Welche Termine sind harte Deadlines?
- [ ] Wie wird Fortschritt gemessen?
- [ ] Wie wird Scope kontrolliert?
- [ ] Wie wird Budget kontrolliert?
- [ ] Wie werden Entscheidungen dokumentiert?
- [ ] Wie werden offene Punkte verfolgt?
- [ ] Wie werden Meetings organisiert?
- [ ] Welche Regeltermine gibt es?

## 30. Risiken, Annahmen und offene Fragen

- [ ] Welche fachlichen Risiken gibt es?
- [ ] Welche technischen Risiken gibt es?
- [ ] Welche organisatorischen Risiken gibt es?
- [ ] Welche rechtlichen Risiken gibt es?
- [ ] Welche Terminrisiken gibt es?
- [ ] Welche Budgetrisiken gibt es?
- [ ] Welche Personalrisiken gibt es?
- [ ] Welche Lieferantenrisiken gibt es?
- [ ] Welche Integrationsrisiken gibt es?
- [ ] Welche Datenqualitaetsrisiken gibt es?
- [ ] Welche Sicherheitsrisiken gibt es?
- [ ] Welche Datenschutzrisiken gibt es?
- [ ] Wie wahrscheinlich ist jedes Risiko?
- [ ] Wie hoch ist der Schaden?
- [ ] Welche Fruehwarnzeichen gibt es?
- [ ] Welche Gegenmassnahmen gibt es?
- [ ] Wer ist Risiko-Owner?
- [ ] Welche Annahmen wurden getroffen?
- [ ] Welche Annahmen sind besonders kritisch?
- [ ] Wie werden Annahmen ueberprueft?
- [ ] Welche offenen Fragen gibt es?
- [ ] Wer beantwortet offene Fragen?
- [ ] Bis wann muessen offene Fragen beantwortet sein?
- [ ] Was passiert, wenn offene Fragen nicht beantwortet werden?
- [ ] Was passiert bei Projektabbruch?
- [ ] Was passiert bei Budgetkuerzung?
- [ ] Was passiert bei Terminverschiebung?

## 31. Dokumentation und Schulung

- [ ] Welche technische Dokumentation wird benoetigt?
- [ ] Welche Benutzerdokumentation wird benoetigt?
- [ ] Welche Administrationsdokumentation wird benoetigt?
- [ ] Welche API-Dokumentation wird benoetigt?
- [ ] Welche Architekturdokumentation wird benoetigt?
- [ ] Welche Installationsanleitung wird benoetigt?
- [ ] Welche Betriebsanleitung wird benoetigt?
- [ ] Welche Testdokumentation wird benoetigt?
- [ ] Welche Entscheidungsdokumentation wird benoetigt?
- [ ] Welche Schulungsunterlagen werden benoetigt?
- [ ] Wer schreibt Dokumentation?
- [ ] Wer prueft Dokumentation?
- [ ] Wer haelt Dokumentation aktuell?
- [ ] Wo wird Dokumentation gespeichert?
- [ ] Wie wird Dokumentation versioniert?
- [ ] Welche Zielgruppen lesen welche Dokumentation?
- [ ] Welche Dokumentation muss vor Release fertig sein?
- [ ] Welche Dokumentation kann spaeter entstehen?
- [ ] Welche Schulungen brauchen Benutzer?
- [ ] Welche Schulungen braucht Support?
- [ ] Welche Schulungen braucht Betrieb?

## 32. Abnahme und Projektabschluss

- [ ] Wer nimmt das System ab?
- [ ] Welche Abnahmekriterien gelten?
- [ ] Welche Anforderungen muessen fuer Abnahme erfuellt sein?
- [ ] Welche Tests muessen fuer Abnahme bestanden sein?
- [ ] Welche Dokumentation muss fuer Abnahme vorliegen?
- [ ] Welche offenen Fehler sind fuer Abnahme akzeptabel?
- [ ] Welche offenen Fehler blockieren Abnahme?
- [ ] Gibt es eine formale Abnahme?
- [ ] Gibt es ein Abnahmeprotokoll?
- [ ] Gibt es eine Pilotphase?
- [ ] Gibt es eine Beta-Phase?
- [ ] Wie wird Feedback aus der Pilotphase verarbeitet?
- [ ] Wann gilt das Projekt als abgeschlossen?
- [ ] Welche Aufgaben bleiben nach Projektabschluss?
- [ ] Welche Wartungsphase beginnt danach?
- [ ] Welche Lessons Learned werden dokumentiert?
- [ ] Welche Artefakte werden archiviert?
- [ ] Welche Zugaenge werden entzogen?
- [ ] Welche Projektumgebungen werden abgeschaltet?
- [ ] Welche naechsten Versionen sind geplant?

---

# Kurzvorlagen zum Ausfuellen

## Projektsteckbrief

| Feld | Antwort |
|---|---|
| Projektname | |
| Auftraggeber | |
| Product Owner / fachlich verantwortlich | |
| Technisch verantwortlich | |
| Start | |
| Zieltermin | |
| Hauptproblem | |
| Hauptnutzen | |
| Muss-Ergebnis | |
| Nicht im Scope | |
| Wichtigste Risiken | |

## Stakeholdertabelle

| Stakeholder | Rolle | Interesse | Einfluss | Kontakt | Entscheidungskompetenz |
|---|---|---|---|---|---|
| | | | niedrig / mittel / hoch | | |

## Anforderungsvorlage

| Feld | Inhalt |
|---|---|
| ID | REQ- |
| Titel | |
| Typ | funktional / Qualitaet / Randbedingung |
| Prioritaet | Muss / Soll / Kann |
| Beschreibung | |
| Quelle | |
| Akzeptanzkriterien | |
| Testidee | |
| Status | offen / bestaetigt / umgesetzt / getestet |

## User-Story-Vorlage

```text
Als <Rolle>
moechte ich <Funktion/Ziel>,
damit <Nutzen>.

Akzeptanzkriterien:
- Gegeben ...
- Wenn ...
- Dann ...
```

## Use-Case-Vorlage

| Feld | Inhalt |
|---|---|
| ID | UC- |
| Name | |
| Primaerer Akteur | |
| Weitere Akteure | |
| Ziel | |
| Vorbedingung | |
| Nachbedingung Erfolg | |
| Nachbedingung Fehler | |
| Hauptszenario | |
| Alternativen | |
| Fehlerfaelle | |
| Fachliche Regeln | |

## Risiko-Vorlage

| Risiko | Wahrscheinlichkeit | Schaden | Fruehwarnzeichen | Massnahme | Owner |
|---|---|---|---|---|---|
| | niedrig / mittel / hoch | niedrig / mittel / hoch | | | |

## Review-Protokoll-Vorlage

| Feld | Inhalt |
|---|---|
| Artefakt | |
| Version | |
| Datum | |
| Autor | |
| Reviewer | |
| Quellen | |
| Ergebnis | akzeptiert / akzeptiert mit Nacharbeit / abgelehnt |

| ID | Fundstelle | Problem | Schwere | Empfehlung | Status |
|---|---|---|---|---|---|
| R-01 | | | niedrig / mittel / hoch | | |

## Traceability-Matrix

| Ziel | Requirement | User Story | Use Case | Design/Modell | Testfall | Release |
|---|---|---|---|---|---|---|
| | REQ- | US- | UC- | | TC- | |

