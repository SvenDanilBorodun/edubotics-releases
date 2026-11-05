# EduBotics – Downloads

Hier stehen die Installationsdateien von **EduBotics**, der Lernplattform für
Robotik und KI mit echten Roboterarmen. Der Quellcode von EduBotics ist nicht
öffentlich; dieses Repository enthält nur die veröffentlichten Programmdateien.

## Installation unter Windows

1. Unter **[Releases](https://github.com/SvenDanilBorodun/edubotics-releases/releases/latest)**
   die Datei `EduBotics_Setup.exe` herunterladen.
2. Die Datei ausführen und den Anweisungen folgen. Die Installation braucht
   Windows 11 und Administratorrechte; sie richtet WSL2 selbst ein.

Eine installierte EduBotics-Anwendung sucht selbst nach Updates und installiert
sie; ein erneuter Download ist nur für eine neue Installation nötig. Vor der
Installation prüft die Anwendung jedes Update anhand der veröffentlichten
SHA-256-Prüfsumme und seiner Größe.

Wer eine heruntergeladene Datei selbst prüfen möchte, berechnet die Prüfsumme in
PowerShell mit `Get-FileHash .\EduBotics_Setup.exe -Algorithm SHA256`.

## Orange Pi

`edubotics-pi-agent.tar.gz` ist das Update-Paket des EduBotics-Agenten auf dem
Orange Pi. Der Agent lädt und prüft es selbst; es muss nicht von Hand
heruntergeladen werden.

## Lizenz

EduBotics steht unter dem [Endnutzer-Lizenzvertrag](LICENSE). Bestandteile
Dritter, ihre Lizenzen und das Angebot zum Quellcode der GPL/LGPL-Bestandteile
stehen in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt); die Lizenztexte im
Ordner [licenses](licenses/).

## Sicherheit

Sicherheitslücken bitte vertraulich melden, wie in [SECURITY.md](SECURITY.md)
beschrieben.

## Kontakt

Sven Danil Borodun (EduBotics)
Unsuhrstrasse 10, 45325 Essen, Deutschland
svendanilborodun@gmail.com
