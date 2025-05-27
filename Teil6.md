## 🐞 Teil 6: Debugging & Remote

### Ein Script debuggen
```bash
bash -x script.sh
```

### Debug-Modus im Script steuern
```bash
set -x  # Debug-Modus an
# ... (dein Code hier)
set +x  # Debug-Modus aus
```

### SSH Verbindung
```bash
ssh benutzer@hostname
```

### SCP Dateitransfer
```bash
# Hochladen
scp datei.txt benutzer@hostname:/pfad/

# Herunterladen
scp benutzer@hostname:/pfad/datei.txt .
```

### Rsync Synchronisation
```bash
rsync -avz /lokaler/pfad/ benutzer@hostname:/entferner/pfad/
```

### Port Weiterleitung
```bash
ssh -L 8080:localhost:80 benutzer@hostname
```
