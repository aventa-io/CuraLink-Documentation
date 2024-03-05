[Zurück zu "Dokumentation"](README.md)

# Technische Dokumentation

Die technische Dokumentation ist für Entwickler, IT-Support-Mitarbeiter und andere technische Fachkräfte gedacht, die CuraLink implementieren, warten oder anpassen. In diesem Abschnitt werden die technischen Aspekte der App, einschließlich der Architektur, der API-Integrationen, der Sicherheitsmerkmale und der Anpassungsmöglichkeiten, ausführlich beschrieben. Ziel ist es, Ihnen das notwendige Wissen und die Werkzeuge an die Hand zu geben, um CuraLink nahtlos in bestehende Systeme zu integrieren und seine Funktionalität nach Bedarf zu erweitern.

## Sicherheit

Die Sicherheit Ihrer Daten und die Integrität der CuraLink-Software haben für uns oberste Priorität, unabhängig davon, ob Sie sich für den Cloud-Betrieb oder den Betrieb auf eigenen Servern entscheiden. Wir setzen auf eine Vielzahl von Sicherheitsmaßnahmen und -protokollen, um einen umfassenden Schutz zu gewährleisten. Dazu gehören unter anderem die Verschlüsselung von Daten sowohl bei der Übertragung als auch bei der Speicherung, regelmäßige Sicherheitsüberprüfungen, Zugriffskontrollen und die Einhaltung von Best Practices der Branche. Unsere Sicherheitsansätze sind darauf ausgerichtet, Risiken zu minimieren, Schwachstellen proaktiv zu identifizieren und zu beheben sowie die Vertraulichkeit, Integrität und Verfügbarkeit Ihrer Daten zu jeder Zeit zu sichern. Wir verstehen die Bedeutung der Sicherheit in der Pflegebranche und sind verpflichtet, ein hohes Maß an Schutz für alle Nutzer von CuraLink zu bieten, damit Sie sich auf die wichtige Arbeit der Pflege konzentrieren können.

Bei der Sicherheitsarchitektur von CuraLink wird eine klare Unterscheidung zwischen der Sicherheit der Softwarekomponenten und der der Infrastrukturkomponenten gemacht. Die Sicherheit der Softwarekomponenten bezieht sich auf Maßnahmen und Protokolle, die direkt in die CuraLink-Anwendung integriert sind, um Datenintegrität, Authentifizierung, Zugriffskontrolle und Schutz vor Bedrohungen zu gewährleisten. Unabhängig vom gewählten Betriebsmodell sind diese Sicherheitsmaßnahmen stets auf dem neuesten Stand.

Die Sicherheit der Infrastrukturkomponenten hingegen hängt stark vom gewählten Betriebsmodell ab – ob Cloud-Hosting, bei dem der Hersteller die Verantwortung für die Sicherheit der Server und Netzwerke übernimmt, oder Selbst-Hosting, bei dem der Betreiber selbst für die Absicherung seiner Netzwerk- und Infrastrukturkomponenten zuständig ist. Diese Unterscheidung ist entscheidend, um die jeweiligen Verantwortlichkeiten klar zu definieren und sicherzustellen, dass alle Aspekte der System- und Datensicherheit angemessen adressiert werden.

## Systemanforderungen Client

Dank unserer fortschrittlichen Sicherheitsarchitektur, die keine Speicherung von sensiblen Daten auf dem Client-Endgerät vorsieht, kann unsere App sicher auf einer Vielzahl von Endgeräten genutzt werden. Dies bedeutet, dass Mitarbeiter die Freiheit haben, die App gemäß den Unternehmensrichtlinien auch auf ihren privaten Geräten zu verwenden, solange diese Richtlinien den Zugriff erlauben. Alternativ dazu können Unternehmen natürlich auch die Nutzung auf firmenverwalteten Geräten, die durch Mobile Device Management (MDM) Lösungen gesichert sind, bevorzugen. Diese Flexibilität ermöglicht es, die App nahtlos in den Arbeitsalltag zu integrieren, ohne dabei Kompromisse bei der Sicherheit eingehen zu müssen.

Die Progressive Web App (PWA) von CuraLink ist so gestaltet, dass sie eine hohe Kompatibilität und Benutzerfreundlichkeit bietet. Als PWA ist CuraLink darauf ausgelegt, auf jedem Gerät mit Internetzugang und einem kompatiblen Webbrowser zu funktionieren. Dies ermöglicht es Benutzern, von einer Vielzahl von Geräten aus – einschließlich Smartphones, Tablets, Laptops und Desktop-Computern – auf die App zuzugreifen, ohne spezifische Anforderungen an das Betriebssystem des Geräts zu stellen.

- Internetverbindung: Stabile Internetverbindung für den Zugriff auf und die Nutzung der PWA.
- Webbrowser: Ein aktueller Webbrowser ist erforderlich. CuraLink unterstützt die neuesten Versionen von Chrome, Firefox, Safari, Edge und anderen modernen Browsern, die mit den PWA-Standards kompatibel sind.
- Betriebssystem: Da die PWA im Webbrowser läuft, gibt es keine spezifischen Anforderungen an das Betriebssystem. Sie ist kompatibel mit Windows, macOS, Linux, iOS, Android und anderen Betriebssystemen, die moderne Webbrowser unterstützen.
- Bildschirmauflösung: Angepasst an verschiedene Bildschirmgrößen und -auflösungen für eine optimale Darstellung auf allen Geräten.
Die Flexibilität und Zugänglichkeit von CuraLink als PWA bedeutet, dass Benutzer unabhängig von ihrem Standort oder dem verwendeten Gerät effizient auf die App zugreifen und sie nutzen können. Diese universelle Zugänglichkeit gewährleistet, dass Pflegekräfte und Administratoren die für ihre Arbeit notwendigen Informationen und Funktionen stets zur Hand haben, was die Pflegeverwaltung und -koordination erheblich erleichtert.

Für Nutzer, die eine optimierte und sichere Nutzungserfahrung mit der Progressive Web App (PWA) von CuraLink wünschen, bieten wir die Möglichkeit, speziell konfigurierte Geräte zur Verfügung zu stellen. Diese Geräte sind mit einem Mobile Device Management (MDM) System ausgestattet, welches die Verwaltung von Updates und Sicherheitspatches zentralisiert. Durch das MDM-System stellen wir sicher, dass alle bereitgestellten Geräte stets auf dem neuesten Stand sind, was Betriebssystemaktualisierungen, Anwendungsupdates und Sicherheitspatches betrifft. Diese Maßnahme maximiert die Sicherheit und Effizienz der Geräte im Einsatz.

Sollten Anwender jedoch den Wunsch haben, eigene Geräte für den Zugriff auf CuraLink zu nutzen, liegt die Verantwortung für die Wartung und Aktualisierung dieser Geräte beim Anwender selbst. Dies umfasst die regelmäßige Installation von Updates und Sicherheitspatches, um die Kompatibilität mit der PWA zu gewährleisten und ein hohes Sicherheitsniveau aufrechtzuerhalten. Es ist wichtig, dass die Anwender, die eigene Geräte nutzen, sich der Bedeutung regelmäßiger Wartungsarbeiten bewusst sind, um die Integrität und Leistungsfähigkeit ihrer Zugriffspunkte auf CuraLink zu sichern.

Aus Sicherheitsgründen werden bei der Nutzung der Progressive Web App (PWA) von CuraLink keine sensiblen Daten direkt auf den Client-Geräten gespeichert. Diese Maßnahme dient dazu, die Sicherheit und den Schutz der Daten zu maximieren, indem potenzielle Risiken, die durch den Verlust oder unbefugten Zugriff auf das Gerät entstehen könnten, minimiert werden. Um eine kontinuierliche Funktionalität und den Zugang zu den benötigten Informationen zu gewährleisten, ist daher eine permanente Internetverbindung ausschlaggebend. Diese ständige Verbindung stellt sicher, dass alle Nutzeraktionen und Datenanfragen in Echtzeit verarbeitet und über sichere Server abgewickelt werden können, wodurch die Integrität und Verfügbarkeit der Daten jederzeit gewährleistet ist. Die Entscheidung, keine Daten auf den Clients zu speichern, unterstreicht unser Engagement für die Sicherheit und den Datenschutz aller Anwender und ihrer sensiblen Informationen.

## CuraLink-Cloud

Der Betrieb von CuraLink in unserer Cloud ermöglicht eine sichere und flexible Lösung, die es Unternehmen erlaubt, sich auf ihre Kerngeschäfte zu konzentrieren, ohne die IT-Infrastruktur verwalten zu müssen. Sie profitieren dabei von vorgegebenen Sicherheitsmaßnahmen und Compliance-Standards, ohne eigene Anpassungen vornehmen zu müssen.

In unserer Cloud übernehmen wir die Bereitstellung von Server- und Speicherkapazitäten. Sie haben dabei immer die volle Kontrolle über Ihre Daten und bleiben stets Eigentümer dieser.

[Hier finden Sie weiterführende Informationen zu CuraLink-Cloud](CuraLink_Cloud.md)

## Eigenes Hosting

Der Betrieb von CuraLink auf eigenen Servern in der eigenen Infrastruktur bietet Unternehmen volle Kontrolle über ihre Daten und Anwendungen. Diese Methode ermöglicht es, die Sicherheitsstandards und Compliance-Anforderungen individuell anzupassen und zu verwalten.

Sie stellen selber die Server- und Speicherkapazitäten bereit, wir helfen Ihnen bei der Installation und Wartung unserer Plattform-Bestandteile.

[Hier finden Sie weiterführende Informationen für eigenes Hosting](Eigenes_Hosting.md)

## Anwendungskomponenten

Bei der Implementierung von CuraLink haben Kunden die Möglichkeit, die verschiedenen Komponenten der Anwendung – wie Datenbanken, Dateispeicher und E-Mail-Server – je nach gewähltem Betriebsmodell (Cloud-Betrieb oder Eigenhosting) zu trennen oder zu bündeln. Diese Flexibilität ermöglicht es, CuraLink optimal an die spezifischen Bedürfnisse und bestehende Infrastruktur des Unternehmens anzupassen.

### Datenbanken

Bei der Nutzung von CuraLink, unabhängig davon, ob Sie sich für das Hosting als Container via Docker oder für eine direkte Installation entscheiden, besteht die Möglichkeit, eine eigene Datenbankinfrastruktur zu integrieren. CuraLink unterstützt eine Vielzahl von Datenbanksystemen, um eine flexible und leistungsstarke Datenverwaltung zu gewährleisten. Die unterstützten Datenbanken umfassen:

- PostgreSQL: Moderne Versionen ab PostgreSQL 9.6 und höher werden unterstützt, wobei die Nutzung von Versionen 12 oder neuer aufgrund verbesserter Leistungsmerkmale und Sicherheitsfunktionen empfohlen wird.
- MySQL: Unterstützt werden Versionen ab MySQL 5.7, mit einer Empfehlung für MySQL 8.0 oder höher, um von den neuesten Optimierungen und Sicherheitsfeatures zu profitieren.
- SQL Server: Für Microsoft SQL Server werden Versionen ab 2016 unterstützt. Die Nutzung von SQL Server 2019 oder neuer wird empfohlen, um die besten Leistungs- und Sicherheitseigenschaften zu erzielen.
Durch die Integration Ihrer eigenen Datenbank können Sie die Kontrolle über die Datenspeicherung behalten und CuraLink nahtlos in Ihre bestehende IT-Infrastruktur einbinden.

### Dateispeicheroptionen
CuraLink ermöglicht die Nutzung eigener Dateispeichersysteme für die Speicherung und Verwaltung von Dateien. Unterstützt werden die folgenden Protokolle, die eine sichere Übertragung und Speicherung von Daten garantieren:

- SCP (Secure Copy Protocol)
- SFTP (SSH File Transfer Protocol)
- FTPS (FTP Secure)
Diese Protokolle bieten die Flexibilität, Dateien sicher über das Netzwerk zu übertragen und stellen eine zuverlässige Lösung für die Datenspeicherung dar. Die Wahl des passenden Dateispeichers hängt von Ihren spezifischen Sicherheitsanforderungen und der bestehenden Infrastruktur ab.

### E-Mail-Versand

Für den Versand von E-Mails bietet CuraLink die Integration mit einem eigenen SMTP-Server. Diese Option ermöglicht es, die E-Mail-Kommunikation nahtlos in bestehende Systeme zu integrieren und die Kontrolle über den Versandprozess zu behalten. Die Nutzung eines eigenen SMTP-Servers gewährleistet, dass alle ausgehenden E-Mails den Unternehmensrichtlinien entsprechen und ermöglicht eine hohe Anpassbarkeit in Bezug auf E-Mail-Vorlagen, Adressierung und Zustellbarkeit.

## API-Referenz

### Einleitung

Unsere REST-API ist ein zentraler Baustein von CuraLink und wurde entwickelt, um eine nahtlose Integration und Interaktion mit Ihren Anwendungen und Systemen zu ermöglichen, unabhängig davon, ob Sie sich für den Cloud-Betrieb oder den Betrieb auf eigenen Servern entscheiden. Diese Dokumentation enthält detaillierte Informationen über Endpunkte, Anforderungs- und Antwortformate sowie Fehlercodes, die Sie für eine erfolgreiche Anbindung benötigen.

Die API von CuraLink ermöglicht es Entwicklern, die vielfältigen Funktionen unserer App in ihre Projekte zu integrieren, benutzerdefinierte Lösungen zu entwickeln oder Daten effizient zwischen verschiedenen Systemen zu synchronisieren. Unabhängig von der gewählten Hosting-Option finden Sie hier alle notwendigen Ressourcen, um die Interoperabilität und Leistungsfähigkeit Ihrer Dienste zu maximieren.

Wir laden Sie ein, die Möglichkeiten unserer API zu erkunden und zu nutzen, um Ihre Pflegedienstleistungen durch eine verbesserte Datenverwaltung und -integration zu optimieren. Für Unterstützung und detaillierte Anleitungen zu spezifischen Aspekten der API stehen wir Ihnen jederzeit zur Verfügung. Bleiben Sie auch auf dem Laufenden über zukünftige Erweiterungen und Aktualisierungen unserer API, die darauf abzielen, Ihre Anforderungen noch besser zu erfüllen und die Qualität Ihrer Dienste zu steigern.

Die REST-API von CuraLink dient nicht nur als Brücke für die Integration und den Datenaustausch zwischen externen Anwendungen und Systemen, sondern bildet auch die Grundlage für die interne Kommunikation zwischen dem Front-End und dem Back-End unserer eigenen Anwendung. Diese zentrale Rolle gewährleistet eine konsistente, effiziente und sichere Datenübertragung innerhalb von CuraLink, unabhängig davon, ob Sie sich für den Cloud-Betrieb oder den Betrieb auf eigenen Servern entscheiden.

Durch die Verwendung derselben API sowohl für interne Prozesse als auch für externe Integrationen ermöglichen wir eine nahtlose Erfahrung und vereinfachen die Entwicklung und Wartung von Anpassungen. Entwickler können sich darauf verlassen, dass die gleichen Standards, Protokolle und Schnittstellen, die für die Interaktion mit CuraLink verwendet werden, auch intern angewendet werden, was die Konsistenz und Zuverlässigkeit des Gesamtsystems erhöht.

Wir ermutigen Sie, die vielseitigen Möglichkeiten unserer API zu erforschen, um die Interaktionen zwischen Ihrem Front-End und Back-End zu optimieren sowie Ihre Dienstleistungen durch eine verbesserte Datenverwaltung und -integration zu erweitern. Unser Support-Team steht bereit, um Ihnen bei der Navigation durch die technischen Details zu helfen und sicherzustellen, dass Sie die volle Leistungsfähigkeit der CuraLink API ausschöpfen können.

### Swagger 
[Link zu SwaggerUI](https://api.curalink.io/swagger)

### Redoc
[Link zu Redoc](https://api.curalink.io/redoc.png)
