
# Einführung in Git

## Was ist Git?
Git ist ein verteiltes Versionskontrollsystem, das ursprünglich von Linus Torvalds entwickelt wurde, um die Entwicklung des Linux-Kernels zu unterstützen. Es ermöglicht mehreren Entwicklern, gleichzeitig an einem Projekt zu arbeiten, Änderungen nachzuverfolgen und bei Bedarf zu einem früheren Zustand zurückzukehren.

## Vorteile von Git
- Verteilte Architektur
- Schnelle Performance
- Branching und Merging
- Vollständige Historie
- Offline-Arbeiten möglich

## Grundlegende Konzepte
- **Repository**: Ein Projektarchiv, das alle Dateien und deren Historie enthält.
- **Commit**: Eine gespeicherte Änderung im Repository.
- **Branch**: Ein paralleler Entwicklungszweig.
- **Merge**: Das Zusammenführen von Änderungen aus verschiedenen Branches.
- **Remote**: Ein externes Repository, z. B. auf GitHub.

## Wichtige Git-Befehle

### Konfiguration
```bash
git config --global user.name "Dein Name"
git config --global user.email "deine@email.de"
```

### Repository erstellen oder klonen
```bash
git init                # Neues Repository erstellen
git clone <url>         # Repository von einem Remote-Server klonen
```

### Status und Änderungen
```bash
git status              # Zeigt den aktuellen Status der Arbeitskopie
git add <datei>         # Datei zur Staging-Area hinzufügen
git add .               # Alle Änderungen hinzufügen
git commit -m "Nachricht"  # Änderungen committen
```

### Historie anzeigen
```bash
git log                 # Zeigt die Commit-Historie
```

### Branches
```bash
git branch              # Zeigt alle Branches
git branch <name>       # Neuen Branch erstellen
git checkout <name>     # Zu einem Branch wechseln
git merge <name>        # Branch in aktuellen Branch mergen
```

### Remote-Repositories
```bash
git remote add origin <url>  # Remote hinzufügen
git push -u origin master    # Änderungen hochladen
git pull                     # Änderungen vom Remote holen
```

### Weitere nützliche Befehle
```bash
git diff                # Zeigt Unterschiede zwischen Dateien
git stash               # Änderungen temporär speichern
git reset --hard        # Änderungen verwerfen
```

## Fazit
Git ist ein mächtiges Werkzeug für die Versionskontrolle und Zusammenarbeit in Softwareprojekten. Mit den oben genannten Befehlen kannst du die wichtigsten Aufgaben im Umgang mit Git meistern.
