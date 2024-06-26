[Zurück zu "Dokumentation"](README.md)

# Rechte- und Rollenverwaltung
Die folgende Dokumentation beschreibt die Benutzerrechte- und Rollenverwaltung der App zur Bestellung von Gebrauchs- und Verbrauchsgegenständen für Pflegeheimbewohner bzw. Mieter im betreuten Wohnen. Ziel dieses Dokuments ist die Beschreibung der einzelnen Benutzerrollen sowie der damit verbundenen Berechtigungen in CuraLink. Die Rechteverwaltung erfolgt auf vier Ebenen: Träger, Einrichtung, Team und Anwender. Ziel dieser Aufteilung ist es, die unterschiedlichen Aufgaben und Tätigkeiten der verschiedenen Personen in der Pflege abzubilden und eine bestmögliche Struktur für die Anwendung von CuraLink zu geben. Dabei unterscheidet sich die Rechte- und Rollenverwaltung nicht zwischen der Anwendung von CuraLink in der stationären oder ambulanten Pflege. 

## Träger
Träger bezeichnet grundsätzlich die Dachorganisation, zu der eine oder mehrere Pflegeeinrichtungen oder -dienste gehören können. Einem Träger werden somit Anwender und Einrichtungen zugeordnet.  
* **Benutzer- und Teamverwaltung:** Innerhalb einer Einrichtung werden Benutzer und Teams erstellt und verwaltet.
* **Bewohnertransparenz:** Alle Benutzer innerhalb einer Einrichtung haben Zugriff auf die Daten aller Bewohner dieser Einrichtung.

## Einrichtung
Eine Einrichtung ist ein konkretes Pflegeheim bzw. ein konkreter Pflegedienst. Einer Einrichtung werden einzelne Patienten/Bewohner zugeordnet.  
* **Benutzer- und Teamverwaltung:** Innerhalb einer Einrichtung werden Benutzer und Teams erstellt und verwaltet.
* **Bewohnertransparenz:** Alle Benutzer innerhalb einer Einrichtung haben Zugriff auf die Daten aller Bewohner dieser Einrichtung.

## Team
Ein Team ist eine Einheit innerhalb einer Einrichtung, der Anwender und Patienten/Bewohner zugeordnet werden können. Team kann als Attribut ebenso ausgewählt werden, um in der Bewohnerübersicht Patienten/Bewohner zu filtern. Die Rolle Team orientiert sich an den jeweiligen Anforderungen einer Einrichtung und kann je nach Anforderung anders bezeichnet werden, z.B. Wohnbereich oder Tour.  
* **Teamzugehörigkeit:** Benutzer werden bestimmten Teams zugeordnet.
* **Event-Steuerung:** Teams dienen der Steuerung von Events innerhalb der App.

## Anwender
Der Anwender ist eine einzelne Person bzw. Rolle, der/die CuraLink nutzt. Diese Rolle kann gleichermaßen einem einzelnen Mitarbeiter zugeordnet werden als auch beispielsweise einem Wohnbereich. In letzterem Fall teilen sich dann mehrere Nutzer die Zugangsdaten. Eine Nachvollziehbarkeit wer welche Bestellungen abgesendet oder Dokument eübermittelt hat ist in diesem Fall dann nicht mehr möglich.
- **Erstellung mit E-Mail-Adresse:** Anwender werden mit einer E-Mail-Adresse angelegt.
- **Dummy-E-Mail-Adressen:** Es können Dummy-E-Mail-Adressen verwendet werden, da die Passwortzurücksetzung durch einen Administrator erfolgt. Dies vereinfacht die Benutzerverwaltung und erhöht die Sicherheit, da die Benutzer keine persönlichen E-Mail-Adressen verwenden müssen.

## Anwender-Rollen
Die Anwender-Rollen unterscheiden sich in dem Umfang welche Tätigkeiten sie innerhalb von CuraLink durchführen können. Die Tätigkeiten innerhalb von CuraLink lassen Sich in folgende Bereiche unterteilen: 
* **Nutzerverwaltung**: Die Anlage und Pflege von Nutzern, Teams so die Passwortverwaltung
* **Patientenverwaltung** Die Anlage und Verwaltung von Patienten/Bewohnern inkl. Pflege der Patienten-/Bewohnerdaten sowie assoziierten Dokumenten und Hilfsmitteln.
* **Kommunikation** Die Übermittlung von ausgefüllten Kontaktformularen an den Versorger inkl. möglichen Anhängen in Form von Dokumenten oder Fotografien (z.B. von beschädigten Hilfsmitteln). Diese Kommunikation kann mit Bezug zu einem Patienten/Bewohner, mit Bezug zu einer Bestellung oder ohne konkreten Bezug erfolgen. 
* **Bestellverwaltung** Die Auswahl von Artikel auf Patienten-/Bewohnerebene und Hinzufügen zu einem Warenkorb, die Erstellung einer Wiedervorlage für einen Bestellvorschlag zu einem späteren Zeitpunk sowie die Übertragung von Bestellungen an den Versorger.

Die wesentlichen Unterscheidungen zwischen den einzelnen Rollen beziehen sich auf die Bereichtigungen im Bereich Nutzerverwaltung sowie die Bestellverwaltung. 
Demnach kann jede Rolle alle Tätigkeiten im Bereich Patientenverwaltung und Kommunikation durchführen. Die Unterscheidungen zwischen den Rollen werden im nächsten Abschnitt dargestellt:  

* **Admin:** Admins verfügen über die umfassendsten Rechte innerhalb eines Trägers. Sie können als einzige Rolle neue Anwender und Teams anlegen, diese verschiedenen Standorten zuordnen und bei Bedarf Passwörter zurücksetzen. Darüber hinaus können sie alle Tätigkeiten durchführen, die auch mit den anderen Rollen assoziiert sind, beispielsweise die Bestellverwaltung oder Kommunikation. 
* **Teamleitung:** Teamleitungen sind berechtigt alle Funktionalitäten der Bestellverwaltung zu nutzen, d.h. Bestellungen für die Bewohner des Pflegeheims abzuschicken. Darüber hinaus kann die Teamleitung alle Funktionalitäten der Patientenverwaltung sowie der Kommunikation nutzen. 
* **Anwender:** Anwender können Bedarfe für die Bewohner erheben und die bereits getätigten Bestellungen einsehen. Ein Versanden der Bestellung ist einem Anwender nicht möglich. Darüber hinaus kann die Anwender-Rolle alle Funktionen der Patientenverwaltung sowie Kommunikation nutzen. 
