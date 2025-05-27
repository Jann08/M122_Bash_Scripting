## 🖥 Teil 1: Linuxbefehle

### Terminal & Prompt
- **Terminal**: Eingabefenster für Befehle
- **Prompt (`$`)**: Zeigt an, dass Eingaben möglich sind

### Hilfe holen
```bash
man <befehl>      # Handbuchseite anzeigen
<befehl> --help   # Kurze Hilfe zu einem Befehl
```

### Systembefehle
```bash
uname -a   # Zeigt Systeminformationen
df -h      # Zeigt Speicherplatznutzung
top        # Zeigt laufende Prozesse
```

### Verzeichnisbefehle
```bash
pwd   # Zeigt aktuelles Verzeichnis
cd    # Verzeichnis wechseln
ls    # Zeigt Inhalte eines Verzeichnisses
```

### Pfade
```bash
/home/user   # absoluter Pfad
../          # relativer Pfad (ein Verzeichnis zurück)
```

### Dateibefehle
```bash
touch test.txt      # Neue Datei erstellen
rm test.txt         # Datei löschen
mv alt.txt neu.txt  # Datei umbenennen/verschieben
```

### Aliase
```bash
alias ll='ls -la'   # Erstelle Kurzbefehle
```

### Wildcards / Expansion
```bash
ls *.txt             # Alle .txt-Dateien anzeigen
echo file{1..3}.txt  # Ausgabe: file1.txt file2.txt file3.txt
```

### Tilde
```bash
cd ~   # Zum Home-Verzeichnis wechseln
```
