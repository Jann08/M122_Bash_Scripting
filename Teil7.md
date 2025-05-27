📡 Teil 7: Extern bearbeiten und remote starten
1. Lokal bearbeiten
Beliebiger Editor (z. B. VS Code)

Datei speichern als .sh

2. Auf Linux-Server kopieren
bash
Kopieren
Bearbeiten
scp script.sh user@host:/pfad/
3. Remote per SSH ausführen
bash
Kopieren
Bearbeiten
ssh user@host 'bash /pfad/script.sh'
