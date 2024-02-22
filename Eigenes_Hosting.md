# Eigenes Hosting

Der Betrieb von CuraLink auf eigenen Servern in der eigenen Infrastruktur bietet Unternehmen volle Kontrolle über ihre Daten und Anwendungen. Diese Methode ermöglicht es, die Sicherheitsstandards und Compliance-Anforderungen individuell anzupassen und zu verwalten.

Sie stellen selber die Server- und Speicherkapazitäten bereit, wir helfen Ihnen bei der Installation und Wartung unserer Plattform-Bestandteile.

## Systemanforderungen Server

Für Kunden, die sich für das eigene Hosting von CuraLink entscheiden, bieten wir zwei Betriebsmodelle an: den Betrieb als Container über Docker oder eine direkte Installation auf dem Server. Hier sind die technischen Anforderungen für beide Szenarien:

### Installation mittels Docker
- Docker-Dienst: Es muss ein Docker-Dienst auf einem Linux-kompatiblen System bereitstehen. Docker ermöglicht es, CuraLink als Container zu betreiben, was eine einfache Skalierung und Portabilität gewährleistet.
- Arbeitsspeicher: Für den Docker-Container von CuraLink wird mindestens 32 GB Arbeitsspeicher benötigt, um eine optimale Leistung zu gewährleisten.
- CPU-Anforderungen: Die CPU sollte folgende Merkmale aufweisen:
  - Mehrere Kerne (mindestens 4 Kerne empfohlen), um parallele Verarbeitung und eine effiziente Ausführung der Anwendungen zu unterstützen.
  - Moderne CPU-Architektur (x86_64 oder ARMv8), um Kompatibilität mit Docker und die erforderliche Rechenleistung sicherzustellen.
  - Unterstützung für Virtualisierungstechnologien, um die Docker-Performance zu optimieren.
- Festplattenspeicher: Es wird eine Festplattenkapazität von etwa 100 GB benötigt, um die Anwendungsdaten, Docker-Images und Logs zu speichern.

### Installation
Kunden, die eine direkte Installation von CuraLink bevorzugen, sollten sich direkt an den Support unter support@curalink.io wenden. Das Support-Team bietet individuelle Anleitungen und Unterstützung, um sicherzustellen, dass die Systemumgebung den Anforderungen von CuraLink entspricht und eine reibungslose Installation gewährleistet ist.

## Einrichtung

## Sicherheit

Bei der Entscheidung für das Selbst-Hosting der Progressive Web App (PWA) von CuraLink liegt die Verantwortung für die Gewährleistung der Sicherheit in den Händen des Betreibers bzw. der IT-Abteilung des Unternehmens. Dies umfasst eine umfassende Palette an Sicherheitsmaßnahmen, von der Absicherung der Netzwerkinfrastruktur über die Implementierung von Firewalls und Intrusion-Detection-Systemen bis hin zur regelmäßigen Anwendung von Sicherheitsupdates und Patches für die Server. Es ist entscheidend, dass die IT-Abteilung proaktive Sicherheitsstrategien verfolgt, um die Integrität, Verfügbarkeit und Vertraulichkeit der gehosteten Daten und Dienste zu schützen. Dies beinhaltet auch die Sicherstellung der Compliance mit relevanten Datenschutzgesetzen und Sicherheitsstandards. Die Eigenverantwortung für die Sicherheit erfordert ein kontinuierliches Engagement und Fachwissen, um potenzielle Sicherheitsrisiken zu minimieren und eine sichere Nutzungsumgebung für alle Nutzer von CuraLink zu schaffen.
