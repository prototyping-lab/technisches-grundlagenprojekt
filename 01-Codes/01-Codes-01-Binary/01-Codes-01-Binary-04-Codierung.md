# Binäre Codierung

*Wieviele Bits brauche ich für binär-codierung von Morse-Nachrichten?*

**Beispiel-Code**

##### 3-Bit pro Zeichen

| Zeichen         | Code           | 
|-----------------|----------------|
| Pause.          | 0 0 0          |
| Punkt           | 0 1 0          |
| Strich          | 1 1 1          |

- Was bedeutet 010010010111111111010010010 ?
- Was bedeutet 110?

#### Aufgabe
- Schreibe den Code auf einen PapierStreifen mit Kästchenpapier und gib ihn weiter
- Benutze zwei der Symoble ◯,	⬤, X, ▢ statt 0 und 1
- Code weiterreichen
- Code entschlüsseln

#### 2-Bit pro Zeichen

| Zeichen         | Code  | 
|-----------------|-------|
| Pause           | 0 0   |
| Punkt           | 0 1   |
| Punkt           | 1 0   |
| Strich          | 1 1   |

#### Beobachtungen
- Was ist eindeutig, wo muß man sich einigen ?
- Was passiert wenn man den Code rückwärts liest?

## Leserichtung

> "The Big-Endians, who broke their boiled eggs at the big end, rebelled against the king, who demanded that his subjects break their eggs at the little end." Gullivers Travels

- [On Holy Wars and a Plea for Peace](https://www.ietf.org/rfc/ien/ien137.txt)  von [Danny Cohen](https://www.internethalloffame.org/inductees/danny-cohen)
- [Bitwertigkeit](https://de.wikipedia.org/wiki/Bitwertigkeit) (Endianess)

- Ordnung von Bits (Leserichtung innerhalb eines Bytes)
	- MSB = Most Siginificant Bit
	- LSB = Least Significant Bit

- Ordnung von Bytes (Leserichtung innerhalb eines "Wortes")
	- Little Endian (Kleinstes Bit zuerst / LSB first)
	- Big Endian (Größtes Bit zuerst / MSB first)
	
- Chip-Hersteller:
	- Motorola (big-endian)
	- Intel (little-endian)

### Serielle Kommunikation (Bit-Order)

#### [I2C](https://learn.adafruit.com/i2c-addresses) (big-endian)

- Kommunikation zwischen Chips (via Datenbus)
- nur zwei Kabel (Signal und Takt)
- MSB wird zuerst gesendet (big-endian)

![signal](https://cdn.sparkfun.com/assets/6/4/7/1/e/51ae0000ce395f645d000000.png)

#### [RS232](https://de.wikipedia.org/wiki/RS-232)

- Kommunikation zwischen Computern / Geräten
- Seriell (Bit für Bit)
- LSB wird zuerst gesendet (little-endian)

![RS232](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/Rs232_oscilloscope_trace.svg/500px-Rs232_oscilloscope_trace.svg.png)


#### Netzwerk-Kommunikation (Byte Order)

- "Network-Byte-Order" = Big-Endian (!)
- Beispiel: Portnummern in TCP/IP (Internet-Protokoll)
- Demo: Wireshark

#### Computer-Entwicklung
- Früher bunt gemischt
- Heute: Praktisch ausschließlich **Little-Endian**, 64 Bit-Computer
- [Macintosh Entwicklung](https://de.wikipedia.org/wiki/Macintosh-Modelle)
	- Motorola 68000-Prozessor (Big-Endian) 
	- PowerPC (Bi-Endian, kann beides) 
	- x86 (Little-Endian)

Siehe auch [hier](https://www.mikrocontroller.net/articles/Digitaltechnik)





