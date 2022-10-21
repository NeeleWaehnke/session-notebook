# Shell Basics

## Allgemeines

Die Shell und der Terminal sind _Command Line Interfaces_ (CLI). CLIs sind text-based und haben keine GUI (Graphical User Interfaces).
--> Man muss durch 'commands' interagieren
Entwickler arbeiten oft mit CLIs

Vorteile/Gründe

- Viele Tools funktionieren nur als CLI/ haben keine GUI
- Man kann Scripts anwenden

Verwendungszwecke:

- Server warten (bspw. Fernadministration)
- Probleme behandeln/ Telematrie abstellen
- Einstellungen vornehmen, wenn keine GUI vorhanden ist
- Versteckte Dateien anzeichen
- Installation von (System-)Software

Zielgruppe: Anwender, die keine GUI benötigen (Systemadministrator)

---

Auf MacOs benutzen wir zsh (z shell). Das kann standardmäßig über den Terminal verwendet werden. Im Kurs nutzen wir auch iTerm und Visual Studio Code als Alternativen

- A shell (like zsh) is the command interpreter that runs and executes commands on your computer and outputs results.
- A terminal (like Terminal, iTerm, Visual Studio Code) is a text input and output environment (emulating a hardware computer terminal) that sends commands to the shell and displays its output.

---

## Wichtige Shell commands

| command            | functionality                                                              |
| ------------------ | -------------------------------------------------------------------------- |
| `ls`               | list the content of the current directory                                  |
| `cd <folder name>` | change directory into a folder                                             |
| `cd ..`            | change into the parent folder                                              |
| `cd ~`             | change into your home directory                                            |
| `pwd`              | print the current directory path                                           |
| `touch example.md` | create a file called "example.md"                                          |
| `mkdir newFolder`  | create a folder called "newFolder"                                         |
| `rm <file name>`   | delete a file permanently (there is no trash bin to recover files!)        |
| `open .`           | open the current folder in the finder                                      |
| `cat <file name>`  | prints the content of a specific file                                      |
| `curl <url>`       | prints the received content from the specified url. (try `curl ipinfo.io`) |
