## 🔄 Teil 4: Schleifen

### While-Schleife
```bash
a=0
while [ $a -lt 5 ]; do
  echo $a
  ((a++))
done
```

### Until-Schleife
```bash
a=0
until [ $a -ge 5 ]; do
  echo $a
  ((a++))
done
```

### For-Schleife
```bash
for i in {1..3}; do
  echo "Durchlauf $i"
done
```

### Nützliche Shell-Tricks
```bash
[ -f file.txt ] && echo "Datei existiert"
mkdir test && cd test
```
