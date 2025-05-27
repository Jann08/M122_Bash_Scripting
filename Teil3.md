## 🔁 Teil 3: Kontrollstrukturen

### Entscheidungen mit If
```bash
if [ $a -gt $b ]; then
  echo "a > b"
else
  echo "a <= b"
fi
```

### Entscheidungen mit Case
```bash
case $1 in
  start) echo "Starte...";;
  stop)  echo "Stoppe...";;
  *)     echo "Unbekannter Befehl";;
esac
```

### Funktionen
```bash
begrüssen() {
  echo "Hallo $1!"
}
begrüssen Max
```

### Parameterübergabe
```bash
echo "1. Argument: $1"
echo "2. Argument: $2"
```
