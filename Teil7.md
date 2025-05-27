## 📡 Teil 7: Extern bearbeiten und remote starten

### 1. Lokal bearbeiten
- Beliebigem Editor verwenden (z.B. VS Code, Nano, Vim)
- Als `.sh`-Datei speichern (z.B. `mein_script.sh`)
- Ausführbar machen:  
```bash
chmod +x mein_script.sh
```

### 2. Auf Linux-Server kopieren
```bash
scp mein_script.sh user@host:/pfad/zum/script/
```

### 3. Remote per SSH ausführen
```bash
# Variante 1: Direkter Aufruf
ssh user@host 'bash /pfad/zum/script/mein_script.sh'

# Variante 2: Mit Parameterübergabe
ssh user@host '/pfad/zum/script/mein_script.sh param1 param2'

# Variante 3: Als Hintergrundprozess
ssh user@host 'nohup /pfad/zum/script/mein_script.sh &'
```

### 4. Alternative: Direkte Remote-Bearbeitung
```bash
# Mit VS Code Remote-SSH
code --remote ssh-remote://user@host/pfad/zum/script/mein_script.sh

# Mit Nano über SSH
ssh user@host 'nano /pfad/zum/script/mein_script.sh'
```
