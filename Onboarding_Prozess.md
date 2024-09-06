# Onboarding-Prozess
Das folgende Dokument beschreibt den Onboarding-Prozess auf die Plattform CuraLink. Die Prozessbeschreibung erfolgt auf den 4 Bereitstellungsebenen. (Träger, Einrichtung, Teams & Anwender)

## Träger
Träger bezeichnet grundsätzlich die Dachorganisation, zu der eine oder mehrere Pflegeeinrichtungen oder -dienste gehören können. Einem Träger werden somit Anwender und Einrichtungen zugeordnet. Die Einrichtung einer CuraLink-Umgebung für einen Träger kann in der CuraLink Cloud-Infrastruktur oder in der eigenen Infrastruktur des Trägers erfolgen. Sofern die Bereitstellung auf der Infrastruktur des Trägers erfolgt sind entsprechend die eigenen Prozesse zu berücksichtigen. (siehe ["Eigenes_Hosting.md"](Eigenes_Hosting.md)) Bei Bereitstellung in der CuraLink-Infrasturktur wird zunächst ein Kurzname (FQDN-Subdomain geeignet, keine Punkte, Umlaute, Sonderzeichen o.Ä.) gewählt. Auf Basis dieser Subdomain (z.B. traeger.prod.curalink.io) wird der Tenant mit eigener Umgebung (insb. Datenbank) eingerichtet. Auf dieser Ebene können dann weitere Lokalisierungs-Optionen vorgenommen werden. Darüber hinaus können statische IP-Adressen freigeschaltet werden. Ein Träger wird einmalig durch CuraLink eingerichtet.
- Auswahl Kurzname (Subdomain-geeignet)
- Optional: Bereitstellung von einer oder mehreren **statischen** IP-Adressen für ein Whitelisting

## Einrichtung
Eine Einrichtung ist ein konkretes Pflegeheim bzw. ein konkreter Pflegedienst. Die Einrichtung ist eine logische Zuordnung von Teams, Anwendern und Patienten. Eine Einrichtung wird dabei mittels optionaler Variablen (Teams, Adresse, Typ: Mobil/Stationär und Struktur von Haus, Etage, Flur) definiert. Im Anschluss können Anwender einer Einrichtung zugeordnet werden. Eine Einrichtung wird einmalig durch CuraLink eingerichtet.
- Name
- Adresse
- Struktur (Haus, Etagen, Flure)

## Teams
Ein Team ist eine Einheit innerhalb einer Einrichtung, der Anwender und Patienten/Bewohner zugeordnet werden können. Teams können von Administratoren in der Oberfläche eingerichtet werden.
- Name

## Anwender
Anwender können durch Administratoren in der Oberfläche eingerichtet werden. Dazu muss eine E-Mail Adresse und ein Passwort gewählt werden. CuraLink erfordert aufgrund flexibler Sicherheitsbestimmungen keine dedizierte Passwort-Richtlinie, daher ist der Administrator zur Auswahl eines sicheren Passwortes angehalten. Dies gilt ebenso für das Zurücksetzen von Passwörtern für User, dies kann nur durch einen Administrator erfolgen. Bei der Anlage muss ein Team und eine Rolle (siehen [Rechteverwaltung](Rechteverwaltung.md)) ausgewählt werden.
Dem User wird das Passwort nicht automatisiert mitgeteilt, dies soll auf sicherem Wege durch den Adminsitrator der Einrichtung erfolgen.
- E-Mail Adresse
- Passwort
- Team-Zuordnung
- Standort-Zuordnung
