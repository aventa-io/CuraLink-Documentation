[Zurück zu "Dokumentation"](README.md)

# Rechte- und Rollenverwaltung
Die folgende Dokumentation beschreibt die Benutzerrechte- und ROllenverwaltung der App zur Bestellung von Gebrauchs- und Verbrauchsgegenständen für Pflegeheimbewohner bzw. Mieter im betreuten Wohnen. Ziel dieses Dokuments ist die Beschreibung der einzelnen Benutzerrollen sowie der damit verbundenen Berechtigungen in CuraLink. Die Rechteverwaltung erfolgt auf vier Ebenen: Träger, Einrichtung, Team und User. Ziel dieser Aufteilung und den unterschiedlichen assoziierten die unterschiedlichen Aufgaben und Prozesse der verschiedenen Personen in der Pflege abzubilden und eine bestmögliche Struktur für die Anwendung von CuraLink zu geben. Dabei unterscheidet sich die Rechte- und Rollenverwaltung nicht zwischen der Anwendung von CuraLink in der stationären oder ambulanten Pflege. 

## Träger
Träger bezeichnet grundsätzlich die Dachorganisation, zu der eine oder mehrere Einrichtungen gehören können. Einem Träger werden somit keine individuellen User zugeordnet sondern Einrichtungen.  
* **Benutzer- und Teamverwaltung:** Innerhalb einer Einrichtung werden Benutzer und Teams erstellt und verwaltet.
* **Bewohnertransparenz:** Alle Benutzer innerhalb einer Einrichtung haben Zugriff auf die Daten aller Bewohner dieser Einrichtung.

## Einrichtung
Eine Einrichtung ist ein konkretes Pflegeheim bzw. ein konkreter Pflegedienst. Einer Einrichtung werden einzelne Patienten/Bewohner zugeordnet.  
* **Benutzer- und Teamverwaltung:** Innerhalb einer Einrichtung werden Benutzer und Teams erstellt und verwaltet.
* **Bewohnertransparenz:** Alle Benutzer innerhalb einer Einrichtung haben Zugriff auf die Daten aller Bewohner dieser Einrichtung.

## Team
* **Teamzugehörigkeit:** Benutzer werden bestimmten Teams zugeordnet.
* **Event-Steuerung:** Teams dienen der Steuerung von Events innerhalb der App.

## User
- **Erstellung mit E-Mail-Adresse:** User werden mit einer E-Mail-Adresse angelegt.
- **Dummy-E-Mail-Adressen:** Es können Dummy-E-Mail-Adressen verwendet werden, da die Passwortzurücksetzung durch einen Administrator erfolgt. Dies vereinfacht die Benutzerverwaltung und erhöht die Sicherheit, da die Benutzer keine persönlichen E-Mail-Adressen verwenden müssen.

## User-Rollen
* **Admin:** Admins verfügen über die umfassendsten Rechte innerhalb eines Trägers. Sie können neue User und Teams anlegen, diese verschiedenen Standorten zuordnen und bei Bedarf Passwörter zurücksetzen.
* **Teamleitung:** Teamleitungen sind berechtigt, Bestellungen für die Bewohner des Pflegeheims abzuschicken.
* **User:** User können Bedarfe für die Bewohner erheben und die bereits getätigten Bestellungen einsehen.
