# Binäre Codes — Zahlencodes

## Populäre Zahlensysteme

- Dezimal (zehn Ziffern)
- Binär (zwei Ziffern)
- Hexadezimal (sechzehn Ziffern)
- Oktal (acht Ziffern)

### Dezimal

Tausendfünfundzwanzig Dezimal (in Ziffern: `1025`)

| Zerlegung       | Potenzschreibweise  | In Worten      |
|----------------:|:-------------------:|:---------------|
| 1 x  1.000      |             1 x 10³ | Tausender      |
| 0 x    100      |             0 x 10² | Hunderter      |
| 2 x     10      |             2 x 10¹ | Zehner         |
| 5 x      1      |             5 x 10⁰ | Einer          |


### Binär

Dreizehn Binär (in Ziffern: `1101`)

| Zerlegung       | Potenzschreibweise  | In Worten      |
|----------------:|:-------------------:|:---------------|
| 1 x      8      |              1 x 2³ | Achter         |
| 1 x      4      |              1 x 2² | Vierer         |
| 0 x      2      |              0 x 2¹ | Zweier         |
| 1 x      1      |              1 x 2⁰ | Einer          |


## Umwandeln auf dem Papier

### Subtraktions-Methode

***FRAGE: Was ist 12 in Binär?***

`1)` Potenzen von 2 anschreiben (1, 2, 4 ...)

```
   _  _  _  _  _  _  _  _ 
 128 64 32 16  8  4  2  1
```

`2)` Ist meine Zahl größer als die Potenz?

- `Nein` → `0` 
- `Ja` → `1` (Potenz von meiner Zahl abziehen)
	
`3)` Fertig?

- `Ja` → Jippie!
- `Nein` → Gehe zurück zu `2)`

### Los gehts!

#### Vier mal die Null
- 12 ist kleiner als 128
- 12 ist kleiner als 64 
- ...
	 
	 
```
   0  0  0  0 _  _  _  _
 128 64 32 16 8  4  2  1
```

####  Einmal die Eins

- 12 ist größer als 8
- Rest 4

```
   0  0  0  0 1  _  _  _
 128 64 32 16 8  4  2  1
 
 Rest: 12 - 8 = 4
```

#### Nochmal die Eins

4 ist NICHT größer als 4  
Rest 0  

```
   0  0  0  0 1  1  _  _
 128 64 32 16 8  4  2  1
 
 Rest: 4 - 4 = 0
```

#### Zwei mal die Null

2 und 1 sind größer als 0.

```
   0  0  0  0 1  1  _  _
 128 64 32 16 8  4  2  1
 
 Rest: 12 - 8 = 4
  4 - 4 = 0 (Rest)
```

## Gruppen-Aufgabe

Binäre Flüsterpost:

`Person A` denkt sich eine Zahl zwischen 1 und 255 und schreibt sie DEZIMAL auf.  
`Person B` codiert von DEZIMAL nach BINÄR  
`Person C` codiert von BINÄR nach HEXADEZIMAL  
`Person D` codiert von HEXADEZIMAL nach BINÄR  
`Person E` codiert von BINÄR nach DEZIMAL  

### Fragen
- Was kommt hinten raus?
- Gab es einen Fehler, wenn ja wo?
- Wie kann man Fehler vermeiden?

## Code-Tabellen

### Hexadezimal-Tabelle

Eine Hexadezimal Ziffer entspricht **VIER** Binär-Ziffern

| Binär  | Hex |
|:-------|:----|
| 0000   | 0   |
| 0001   | 1   |
| 0010   | 2   |
| 0011   | 3   |
| 0100   | 4   |
| 0101   | 5   |
| 0110   | 6   |
| 0111   | 7   |
| 1000   | 8   |
| 1001   | 9   |
| 1010   | a   |
| 1011   | b   |
| 1100   | c   |
| 1101   | d   |
| 1110   | e   |
| 1111   | f   |

### Oktal-Tabelle

Eine Oktal Ziffer entspricht **DREI** Binär-Ziffern

| Binär | Okt |
|:------|:----|
| 000   | 0   |
| 001   | 1   |
| 010   | 2   |
| 011   | 3   |
| 100   | 4   |
| 101   | 5   |
| 110   | 6   |
| 111   | 7   |



## Umwandeln mit dem Taschenrechner

1. Auf dem Mac `Calculator` öffnen
2. Programmer View (mit `CMD` + `3`)
3. Modus auswählen + Zahl eintippen
4. Modus wechseln (`8`, `10`, `16`)

## Umwandeln mit Code

1. Browser Console öffnen
2. Javascript eingeben :)

### Zahl → Binär-Code
| Sprache      | Ausdruck             |
|--------------|----------------------|
| Mathematica  | `BaseForm[1025, 2]`  |
| Javascript   | `(1025).toString(2)` |
| Python       | `bin(1025)`          |

### Zahl → Hexadezimal-Code
| Sprache      | Ausdruck              |
|--------------|-----------------------|
| Mathematica  | `BaseForm[1025, 16]`  |
| Javascript   | `(1025).toString(16)` |
| Python       | `hex(1025)`           |

### Zahl → Oktal-Code
| Sprache      | Ausdruck              |
|--------------|-----------------------|
| Mathematica  | `BaseForm[1025, 8]`   |
| Javascript   | `(1025).toString(8)`  |
| Python       | `oct(1025)`           |

--- 

### Binär-Code → Zahl

*Für welche Zahl steht der Binärcode 1100101 ?*

| Sprache      | Ausdruck                    |
|--------------|-----------------------------|
| Mathematica  | `FromDigits["1100101 ", 2]` |
| Javascript   | `parseInt("1100101 ", 2)`   |
| Python       | `int("1100101 ", 2)`        |

### Hexadezimal-Code → Zahl

*Für welche Zahl steht der Hexadezimal-Code ff0000 ?*

| Sprache      | Ausdruck                    |
|--------------|-----------------------------|
| Mathematica  | `FromDigits["ff0000", 16]`  |
| Javascript   | `parseInt("ff0000", 16)`    |
| Python       | `int("ff0000", 16)`         |


### Oktal-Code → Zahl

*Für welche Zahl steht der Oktal-Code `7777` ???*

| Sprache      | Ausdruck               |
|--------------|------------------------|
| Mathematica  | `FromDigits["7777", 8]`     |
| Javascript   | `parseInt("7777 ", 8)` |
| Python       | `int("7777", 8)`       |


## Tools

- Taschenrechner 
- Browser (Javascript)
- Raspi (Mathematica)

## Links

- [Computers 101](https://www.khanacademy.org/computing/ap-computer-science-principles/computers-101) (Khan Academy)
- [Python Console](https://repl.it/languages/python) (repl.it)
- [Bitwise Command](http://bitwisecmd.com/) (javascript Binär-Operatioen)


