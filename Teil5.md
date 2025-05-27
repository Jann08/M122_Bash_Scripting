## 📤 Teil 5: Ein- & Ausgabe / Umleitung

### Ausgabe umleiten
```bash
echo "Test" > datei.txt
```

### Anhängen statt überschreiben
```bash
echo "weiterer Text" >> datei.txt
```

### Fehler unterdrücken / zusammenfassen
```bash
command > /dev/null 2>&1
```

### Eingabe umleiten
```bash
cat < eingabe.txt
```

### Pipeline
```bash
cat datei.txt | grep "Suchwort"
```
