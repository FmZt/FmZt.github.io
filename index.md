# Meine Projekte rund ums THW
 
Ich engagiere mich seit über 25 Jahren ehrenamtlich im Technischen Hilfswerk (THW), im Bereich Information und Kommunikation. Neben der Ausbildung und der Arbeit im Fachzug Führung/Kommunikation probiere ich in meiner Freizeit Ideen aus, die Einsatzkommunikation und Lagedarstellung einfacher, robuster und unabhängiger machen können.
 
> **Hinweis:** Das sind private Projekte und Prototypen. Sie sind keine offiziellen Produkte oder Positionen des THW und kein Ersatz für BOS-Kommunikationssysteme. Vieles ist Experiment oder in Planung.
 
## Kommunikation und Netze
 
### Richtfunknetz für THW-Standorte
Planungsprojekt für ein lizenzfreies Richtfunknetz zwischen 13 Standorten (Regionalstelle und Ortsverbände). Das Konzept soll später auf deutlich mehr Standorte erweiterbar sein und im Betrieb ohne Internet auskommen.
- Netzinfrastruktur auf Basis von MikroTik
- Offline-Netzwerkmanagement und Offline-Update-Verfahren
- Einheitliche Hostnamen und ein durchgängiges IP-Adresskonzept
- Kartengestützte Planung mit QGIS
### MeshCore: LoRa-Mesh für das THW
Anleitung für den Aufbau eines MeshCore-LoRa-Mesh-Netzes im THW-Umfeld. Dazu gehört eine Namenskonvention für Knoten (Personen, Repeater, Dienststellen), die sich an der Funk-Rufnamen-Regelung des THW orientiert.
 
### Reticulum-Client
Eigener Client für das Reticulum-Netzwerk (LXMF) mit Kommandozeile und grafischer Oberfläche. Er dient zum Erstellen, Versenden und Empfangen von Einsatzaufträgen und Lagemeldungen. Ergänzend plane ich Experimente mit Reticulum über CB-Funk.
 
### Langwellen-Broadcast (Forschungsprototyp)
Experimentelles Nachrichtensystem: Eine zentrale Sendestation überträgt digitale Nachrichten per Langwelle an viele reine Empfangsgeräte, ohne Rückkanal. Ziel ist es, robuste, stromsparende und unabhängige Übertragungswege zu erforschen. Getestet wird nur auf rechtlich zulässigen Wegen (Simulation, Kabel, abgeschirmte Umgebung).
 
## Lage und Führung
 
### Kurzmeldungs-Drehscheibe
Prototyp einer analog nutzbaren Drehscheibe, mit der sich Lagemeldungen auf maximal 320 Zeichen kodieren lassen. Sie ist gedacht für Situationen, in denen nur wenig Bandbreite oder gar keine Technik zur Verfügung steht. Die Entwürfe sind in der Abstimmung mit Kameradinnen und Kameraden.
 
### Lagebild-Wiki
Ein Wissensspeicher auf Basis von Obsidian und dem LLM-Wiki-Muster. Er soll aus öffentlich zugänglichen Quellen ein Lagebild für Einsätze zusammenführen und Meldungen einer gemeinsamen Einsatz-Kennung zuordnen. Datenschutz hat dabei Vorrang: Es werden nur Namen gespeichert, keine Telefonnummern.
 
### BR-Manager
Webanwendung zur Verwaltung von Einsätzen und Bereitstellungsräumen (FastAPI, SQLite), betrieben als Container auf einem Raspberry Pi.
 
## Karten und Werkzeuge (QGIS)
 
### Plugin „THW Taktische Zeichen"
QGIS-Plugin, das Punkten auf der Karte taktische Zeichen (SVG) zuordnet, entweder per Klick oder über ein Attributfeld. Die Zeichen erscheinen dauerhaft als Kartensymbol. Der Ordner mit den SVG-Dateien ist frei konfigurierbar.
 
### Plugin zur 4-m-BOS-Funkausbreitung
Geplantes QGIS-Plugin, das die Ausbreitung von 4-m-BOS-Funk auf Basis öffentlicher Geländemodelle abschätzt. Erstes Testgebiet ist das Gebiet mehrerer Ortsverbände im Rheinland.
 
## Wie ich arbeite
 
Meine Software-Projekte entwickle ich phasenweise zusammen mit Claude AI, mit sauberer Versionierung in Git und einer Sicherheitsprüfung des Codes bei jeder Version.
 
---
*Stand: November 2026.*
 
