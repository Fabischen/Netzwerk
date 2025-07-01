# Grundlagen & Netzwerktypen

- **Was ist ein Netzwerk?**  
Ein Netzwerk ist eine Verbindung mehrerer Geräte wie Computer, Smartphones oder Drucker, sodass sie Informationen austauschen, gemeinsam Daten nutzen oder miteinander kommunizieren können – entweder über Kabel oder drahtlos.

- **LAN (Local Area Network)**  
Ein LAN ist ein lokales Netzwerk, das sich auf einen kleinen Bereich beschränkt, zB. in einem Haus, einer Schule oder einem Büro, in dem Geräte wie PCs und Drucker miteinander verbunden sind – meist über Ethernet-Kabel.

- **WLAN (Wireless LAN)**  
WLAN ist ein drahtloses Netzwerk innerhalb eines LANs, bei dem die Verbindung zwischen Geräten nicht über Kabel, sondern über Funkwellen (meist per Router) erfolgt – das ist das, was wir zuhause als `WLAN` kennen.

- **WAN (Wide Area Network)**  
Ein WAN ist ein Netzwerk, das sich über große geografische Entfernungen erstreckt, wie zB. das Internet, bei dem viele LANs miteinander verbunden sind – oft über Telefonleitungen, Glasfaserkabel oder Satelliten.

- **PAN (Personal Area Network)**  
Ein PAN ist ein sehr kleines Netzwerk rund um eine Person, das Geräte wie ein Smartphone, eine Smartwatch, Kopfhörer oder einen Laptop über Bluetooth oder USB miteinander verbindet.

- **VPN (Virtual Private Network)**  
Ein VPN ist eine sichere, verschlüsselte Verbindung über das Internet, mit der man so auf ein anderes Netzwerk zugreifen kann, als wäre man vor Ort – das wird zB. genutzt, um von zu Hause auf das Firmennetzwerk zuzugreifen oder den Standort zu verschleiern.

- **P2P (Peer to Peer)**  
In einem P2P-Netzwerk sind alle Computer gleichgestellt und kommunizieren direkt miteinander, ohne über einen zentralen Server – bekannt ist dieses Prinzip vor allem durch Dateifreigaben oder Tauschbörsen.

<br>

# Internet, WWW & Protokolle

- **World Wide Web (WWW)**  
Das WWW ist ein Dienst im Internet, bei dem man über Webbrowser auf Webseiten zugreifen kann – es besteht aus Milliarden von miteinander verlinkten Seiten, zB. Wikipedia, YouTube oder Online-Shops.

- **IP (Internet Protocol)**  
IP ist ein Regelwerk, das dafür sorgt, dass jedes Gerät im Internet eine eindeutige Adresse (IP-Adresse) bekommt, damit Datenpakete korrekt von einem Sender zum richtigen Empfänger gelangen.

- **TCP (Transmission Control Protocol)**  
TCP ist ein Übertragungsprotokoll, das beim Versenden von Daten sicherstellt, dass alle Daten korrekt und in der richtigen Reihenfolge beim Empfänger ankommen – ähnlich wie ein zuverlässiger Paketdienst mit Empfangsbestätigung.

- **UDP (User Datagram Protocol)**  
UDP ist ein schnelleres, aber weniger zuverlässiges Übertragungsprotokoll, das keine Bestätigung verlangt – ideal für Dinge wie Online-Spiele, Videotelefonie oder Live-Streams, bei denen Geschwindigkeit wichtiger ist als Perfektion.

- **SSID (Service Set Identifier)**  
Die SSID ist der sichtbare Name eines WLAN-Netzwerks, also das, was du siehst, wenn du auf deinem Handy nach verfügbaren Netzwerken suchst – sie kann vom Benutzer frei benannt werden.

- **Verschlüsselung von WLAN**  
Die Verschlüsselung im WLAN schützt das Netzwerk vor unbefugtem Zugriff, indem alle Daten codiert übertragen werden – moderne Standards wie WPA2 oder WPA3 machen es für Hacker sehr schwer, mitzulesen oder ins Netz einzudringen.

<br>

# Netzwerk-Hardware

- **Router**  
Der Router ist das zentrale Gerät in einem Heimnetzwerk: Er verbindet dein lokales Netzwerk mit dem Internet und verteilt die Verbindung per LAN-Kabel oder WLAN an alle Geräte wie PCs, Smartphones oder Fernseher.

- **Switch**  
Ein Switch ist ein Gerät, das viele Geräte in einem Netzwerk miteinander verbindet, indem es Datenpakete gezielt an den richtigen Empfänger weiterleitet – das wird vor allem in größeren Netzwerken wie in Unternehmen verwendet.

- **Ethernet**  
Ethernet ist eine Technik zur Datenübertragung über Netzwerkkabel (LAN-Kabel) und wird vor allem für schnelle, stabile Verbindungen im lokalen Netzwerk verwendet. *Ethernet wurde zwischen 1973 und 1976 entwickelt und ist bis heute ein Standard in der Netzwerktechnik.*

<br>

# Netzwerkbefehle (CMD / Eingabeaufforderung)

- **ipconfig**  
Der Befehl `ipconfig` zeigt in der Eingabeaufforderung (CMD) wichtige Informationen über dein Netzwerk an, zB. deine IP-Adresse, Subnetzmaske oder Standardgateway – praktisch zur Fehlersuche.

- **ping**  
Mit dem Befehl `ping` kann man testen, ob ein anderes Gerät (zB. ein Server oder eine Webseite) erreichbar ist, indem kleine Datenpakete geschickt und die Antwortzeit gemessen wird – nützlich, wenn man prüfen will, ob das Internet funktioniert.

- **Befehle für Internet-Test (CMD)**
```bash
ping google.de     # Testet die Verbindung.
ipconfig           # Zeigt Netzwerkdaten des eigenen PCs.
tracert google.de  # Zeigt den Weg, den Datenpakete durch das Internet nehmen.
nslookup google.de # Zeigt IP-Adresse zu einem Domainnamen.
```

<br>

# Historisches & Sonstiges

- **Arpanet**  
Das ARPANET war das erste große Computernetzwerk und wurde in den 1960er Jahren vom US-Militär entwickelt – es war der direkte Vorläufer des heutigen Internets und verband erstmals Universitäten und Forschungseinrichtungen digital miteinander.

- **Telegraf**  
Der Telegraf war ein historisches Kommunikationsmittel aus dem 19. Jahrhundert, mit dem Nachrichten in Form von Morsezeichen über weite Entfernungen per Draht übertragen wurden – eine frühe Form digitaler Kommunikation.

<br>

# Warum ist das Netzwerk nützlich und welche Arten es gibt?

- **Warum nützlich?**  
Netzwerke ermöglichen es uns, Informationen schnell auszutauschen, gemeinsam auf Geräte (z. B. Drucker oder Server) zuzugreifen, im Internet zu surfen oder online zu arbeiten – das ist sowohl im Alltag als auch in Unternehmen unverzichtbar.

- **Arten von Netzwerken:**
- > **LAN** - Lokales Netz (zB. Schule oder Büro)
- > **WLAN** - Drahtloses lokales Netz
- > **WAN** - Großflächiges Netz (zB. Internet)
- > **PAN** - Kleines persönliches Netz (zB. Bluetooth)
- > **VPN** - Sicherer Tunnel über das Internet
- > **P2P** - Direktes Netz ohne Server
