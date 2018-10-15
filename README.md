# Einrichten einer VPN Verbindung zwischen LANCOM Advanced VPN Client und einer Fritzbox

**Die Einstellungen sollten kompatibel mit dem NCP Client sein** (https://www.ncp-e.com/de/service/download-vpn-client/)


*Diese Anleitung wurde auf Grundlage folgender Hard- und Software erstellt*

- FRITZ!Box Fon WLAN 7390 (FRITZ!OS: 06.83)
- LANCOM Advanced VPN Client v3.11 build 32792
- Windows 10pro, 64bit v1803 build 17134.345
- einen Benutzer in der Fritzbox mit VPN Zugriff, hier "laptop-dell-w10"

## Profileinstellungen öffnen

![1](img\1.png "1")

## Neues Profil hinzufügen

![2](img\2.png "2")

## Neue IPsec Verbindung

![3](img\3.png "3")

## Anzeigename im VPN Client

![4](img\4.png "4")

## Verbindungsquelle wählen

![5](img\5.png "5")

## MyFritz Adresse oder DynDNS eintragen

Benutzername und Passwort entnehmen Sie bitte der Fritzbox (VPN Einstellungen des Benutzers)

![6](img\6.png "6")

## Parameter wie folgt anpassen

![7](img\7.png "7"

## Parameter wie folgt anpassen

Pre-shared Key entnehmen Sie den Fritzbox Benutzer Einstellungen (VPN Einstellungen; wird automatisch erzeugt)

![8](img\8.png "8")

## IP - Adresse

Diese wird in der Fritzbox automatisch vergeben. Kann in der Fritzbox unter **Heimnetz -> Heimnetzübersicht -> Netzwerkverbindungen -> IP-Adresse** eingesehen werden!

![9](img\9.png "9")

## Das Subnetz bestimmen das NICHT über den VPN geroutet werden soll. Hier das Subnetz des Clients bzw. der Fritzbox

![10](img\10.png "10")