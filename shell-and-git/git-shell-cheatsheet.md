# Git + Shell commands

## Allgemeines

| Befehl        | Beschreibung                      |
| ------------- | --------------------------------- |
| man + command | manual öffnen zu gewählten Befehl |
| clear         | Ausgabe leeren                    |
| open .        | aktuelles Verzeichnis öffnen      |
| code .        | aktuelle Datei in VS öffnen       |
| ls            | Verzeichnisse & Dateien anzeigen  |
| ls -l         | genauere Darstellung              |
| ls -la        | versteckte Dateien anzeigen       |

---

## Befehle zu Dateien etc.

| Befehl                          | Beschreibung                           |
| ------------------------------- | -------------------------------------- |
| mkdir                           | Verzeichnis erstellen                  |
| touch                           | Datei erstellen                        |
| cat                             | .md File angucken (Inhalt)             |
| rm                              | Datei löschen                          |
| rm -rf                          | force löschen (z.b ganzes Verzeichnis) |
| unzip <name>                    | .zip Datei öffnen                      |
| echo "text" > <filename.md>     | etw. in eine .md file schreiben        |
| mv <filename> <newname>         | Datei umbenennen                       |
| mv <filename> <Verzeichnisname> | Datei in Verzeichnis verschieben       |

---

## Git Remote Befehle

| Befehl                        | Beschreibung                                                                  |
| ----------------------------- | ----------------------------------------------------------------------------- |
| git status                    | Listet alle Dateien, die verändert wurden und deren Status                    |
| git add <filename>            | Fügt eine Datei zur Stage hinzu                                               |
| git commit -m"Commit message" | erstellt einen commit mit allen Dateien auf der Stage                         |
| git log --oneline             | Zeigt die commit Historie an                                                  |
| git init                      | macht eine Datei zum Git Repository                                           |
| git push                      | Pusht die commits im remote repository                                        |
| git pull                      | lädt die Veränderungen vom remote repository runter                           |
| git merge main                | lädt Änderungen vom Main branch auf den feature branch (muss ausgewählt sein) |
| git branch -d <branchname>    | löscht den gewählten Branch                                                   |
| git branch                    | zeigt aktuelle Branches an                                                    |
| git switch -c <name>          | erstellt einen Feature Branch mit dem gewählten Namen                         |
| git switch <name>             | switcht auf den gewählten Branch                                              |
