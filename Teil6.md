🐞 Teil 6: Debugging & Remote
Ein Script debuggen
bash
Kopieren
Bearbeiten
bash -x script.sh
Im Script selbst:

bash
Kopieren
Bearbeiten
set -x  # Debug-Modus an
# ...
set +x  # Debug-Modus aus
