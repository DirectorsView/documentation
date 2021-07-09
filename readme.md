# DirectorsView

**Diplomarbeitstitel:** DirectorsView - Plattform für die Verwaltung von Videoprojekten 
**Mitglieder:** Wiesinger Jonas, Knogler Simon 

### Ausgangslage

Firmen und Selbstständige im Filmbereich haben oft Probleme damit, Projekte und die damit verbundenen Aufgaben gesammelt zu verwalten. Es gibt Plattformen für das Suchen von Mitarbeitern und es gibt Apps, welche für die Organisation von Projekten für Firmen gebaut wurden. Wir möchten mit unserem Produkt diese Programme vereinen und so die Planung von Videoprojekten erleichtern.

### Projektteam

| Name                                  | Individuelle Themenstellung           | Klasse |
| :------------------------------------ | :------------------------------------ | :----- |
| Jonas Wiesinger (Hauptverantwortlich) | Quarkus Backend, PostgreSQL Datenbank | 5AHITM |
| Simon Knogler                         | Webclient, UI, Frontend               | 5AHITM |

### Untersuchungsanliegen der individuellen Themenstellungen

Das Userinterface, welches den wichtigsten Teil der gesamten Customer Experience darstellt, wird in Form einer funktionierenden Weboberfläche mithilfe des Angular Frameworks "Ionic" von **Knogler Simon** implementiert. Auch für das Design ist **Simon Knogler** verantwortlich, also für Farben, Fonts und ähnliche Inhalte, die das Auftreten der Website maßgeblich prägen.

**Jonas Wiesinger** ist für das Backend und die Kommunikation zwischen Client und Server zuständig. Der Server mit Datenbankanbindung ist essenziell nötig für das Erfüllen der Funktionalitäten, da die eingehenden Daten richtig verarbeitet werden müssen. Mithilfe einer PostgreSQL Datenbank und einem Quarkus Server werden so alle Funktionalitäten abgedeckt. 

### Zielsetzung

Es wird eine Webapplikation erstellt, welche mit einem Quarkus Server und einer PostgreSQL Datenbank Firmen ermöglicht, einfach und schnell Projekte, ihre zugeteilten Mitarbeiter und ihr Equipment zu verwalten. Es können sich auch Selbstständige für freie Stellen, welche von Firmen ausgeschrieben wurden, bewerben und bei einer akzeptierten Bewerbung zu dem jeweiligen Projekt hinzugefügt werden.

### Geplantes Ergebnis der Prüfungskandidatin/des Prüfungskandidaten

Unser Kundenportal bietet folgenden Leistungsumfang:

- Jobportal für Selbstständige und Firmen
- Tool zur Equipment-Verwaltung
- Einfache Projektübersicht für Firmen
- Chatfunktion zwischen Benutzern

Da die Arbeit großteils auf Client (**Simon Knogler**) und Server (**Jonas Wiesinger**) aufgeteilt ist, besteht bei den meisten Funktionen keine klare Zuteilung dieser auf eine einzelne Person.

### Meilensteine

09.07.2021 Vollendung der Planung

06.08.2021 Erstellung und Bearbeitung von Firmen- und Privataccounts möglich

27.08.2021 Firmen können ihre Mitarbeiter verwalten

17.09.2021 Firmen können den Equipment Bestand verwalten

08.10.2021 Fertigstellung der Projektverwaltung für Firmen

29.10.2021 Fertigstellung der Jobbörse und des Bewerbungssystems

26.11.2021 Ausarbeitung von Feinheiten (Animationen, Bug-fixes, ...)