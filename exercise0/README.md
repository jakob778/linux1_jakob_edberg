# Exercise0 solutions documentation

## Task 1
a) Skapade mappar med brace expansion

```bash
mkdir exercise{0..3}
```


skapade sedan filer med touch

```bash
touch exercise0/README.md
```

## Task 2
a) Skapade 3 filer med brace expansion

```bash
touch file{1..3}.md
```

b) Skapade ett directory för dessa filer

```bash
mkdir files
```

c) Flyttade in filerna i directory:t med globbing

```bash
mv *.md files
```

d) Plockade ut file2.md till exercise0

```bash
mv file2.mv ..
```

e) Lade in text i file2.md

```bash
echo "Hello file2" >> file2.md
```

f) Kopierade filen och gjorde kopian till textfil

```bash
cp file2.md file2.txt
```

g) Läste ut båda filerna

```bash
cat file2.md file2.txt
```

h) Raderade directory:t + filerna jag skapat

```bash
rm -r files
rm file2.md file2.txt
```

