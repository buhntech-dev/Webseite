# Community Rangverwaltung

Statische GitHub-Pages-Webseite zum Erzeugen von LuckPerms-Befehlen für einen Paper/Aternos-Server.

## Funktionen
- Rang für einen Minecraft-Spieler vergeben oder wechseln
- Prefix-Befehle erzeugen
- LuckPerms-Gruppen initial anlegen
- Einzelne Permission-Befehle erzeugen
- Befehle kopieren

## GitHub Pages aktivieren
1. Repository-Einstellungen öffnen.
2. Links **Pages** wählen.
3. Unter **Build and deployment** bei **Source**: **Deploy from a branch** wählen.
4. Branch **main**, Ordner **/(root)** wählen und speichern.
5. Warten, bis GitHub Pages veröffentlicht ist.

## Aternos verwenden
Die Webseite kann Aternos nicht direkt steuern. Aternos bietet keine offizielle öffentliche API/RCON-Verbindung für externe Rangverwaltung. Befehle werden in der Webseite erzeugt und müssen in der Aternos-Konsole eingefügt werden.

1. Paper-Server starten.
2. Aternos-Konsole öffnen.
3. Befehl kopieren und einfügen.
4. Ergebnis in der Konsole kontrollieren.

Keine Aternos-Passwörter, Session-Cookies oder Tokens in GitHub Pages eintragen.

## Ränge
owner, admin, moderator, supporter, premium, vip, spieler

## Sicherheit
Die Webseite vergibt keine OP-Rechte und führt keine Befehle aus. Permission-Knoten nur gezielt setzen.
