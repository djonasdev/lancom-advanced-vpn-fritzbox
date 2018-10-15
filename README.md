# Einrichten einer VPN Verbindung zwischen LANCOM Advanced VPN Client und einer Fritzbox

**Die Einstellungen sollten kompatibel mit dem NCP Client sein** (https://www.ncp-e.com/de/service/download-vpn-client/)


*Diese Anleitung wurde auf Grundlage folgender Hard- und Software erstellt*

- FRITZ!Box Fon WLAN 7390 (FRITZ!OS: 06.83)
- LANCOM Advanced VPN Client v3.11 build 32792
- Windows 10pro, 64bit v1803 build 17134.345
- einen Benutzer in der Fritzbox mit VPN Zugriff, hier "laptop-dell-w10"

## Profileinstellungen öffnen

![](img\1.png)

## Neues Profil hinzufügen

![](img\2.png)

## Neue IPsec Verbindung

![](img\3.png)

## Anzeigename im VPN Client

![](img\4.png)

## Verbindungsquelle wählen

![](img\5.png)

## MyFritz Adresse oder DynDNS eintragen

Benutzername und Passwort entnehmen Sie bitte der Fritzbox (VPN Einstellungen des Benutzers)

![](img\6.png)

## Parameter wie folgt anpassen

![](img\7.png)

## Parameter wie folgt anpassen

Pre-shared Key entnehmen Sie den Fritzbox Benutzer Einstellungen (VPN Einstellungen; wird automatisch erzeugt)

![](img\8.png)

## IP - Adresse

Diese wird in der Fritzbox automatisch vergeben. Kann in der Fritzbox unter **Heimnetz -> Heimnetzübersicht -> Netzwerkverbindungen -> IP-Adresse** eingesehen werden!

![](img\9.png)

## Das Subnetz bestimmen das NICHT über den VPN geroutet werden soll. Hier das Subnetz des Clients bzw. der Fritzbox

![](img\10.png)