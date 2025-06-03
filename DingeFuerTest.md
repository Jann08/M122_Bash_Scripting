
# 📘 Bash Cheatsheet für den Test (M122)

## 🧭 Verzeichnisse navigieren

```bash
cd ~            # Zum Homeverzeichnis
cd /etc         # Absoluter Pfad
cd ..           # Ein Verzeichnis zurück
cd ../dev       # Relativ zu aktuellem Pfad
```

## 🌀 Wildcards & Braces

```bash
touch file{1..10}       # file1 bis file10
rm *1                  # Alle mit '1' im Namen löschen
rm file{2,4,7}         # Nur bestimmte Dateien löschen
```

```bash
cp -r Ordner Ordner2           # Verzeichnis kopieren
mv Ordner Ordner1              # Verzeichnis umbenennen
rm -r Ordner*                  # Alle Ordner löschen
```

## 🏠 Tilde Expansion

```bash
~     # Home
~+    # aktuelles Verzeichnis
~-    # vorheriges Verzeichnis
~user # Home eines anderen Users
```

## 🔍 grep – Zeilen suchen

```bash
grep --color=auto 'text' datei.txt     # Text suchen
grep -v 'wort' datei.txt               # Zeilen ohne 'wort'
grep -E '[123]' datei.txt              # Regex mit mehreren Zeichen
```

## ✂️ cut – Spalten extrahieren

```bash
cut -d ':' -f1 datei.txt   # alles vor dem ersten :
cut -d ':' -f2 datei.txt   # zwischen zwei :
cut -d ':' -f3 datei.txt   # nach dem letzten :
```

## 🧠 awk – dynamisch Spalten anzeigen

```bash
awk -F':' '{print $(NF-1)}' datei.txt   # vorletzte Spalte
```

## 🛠 Tools Überblick

| Tool | Funktion |
|------|----------|
| `grep` | Zeilen filtern mit Mustern |
| `cut`  | Spalten ausschneiden |
| `awk`  | Flexible Textverarbeitung |
| `sed`  | Zeichen ersetzen (nur erwähnt) |

---
