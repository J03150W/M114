# M114
ePortfolie des Moduls-114

## Inhaltsverzeichnis
 - [Tag-1](#Tag-1)

---

## Tag-1
### Vorwissen
Wir haben mit einem Kahoot zur Vorwissen kontrolle gestartet.

Files wenn man sie mit der Endung ".txt" bennent, zeigen nach Öffnung die verwandelte Bits in Text an. <br>
[HEX-Editor](https://hexed.it/) um das File als Bits zu sehen.

### Aufgabe: Schachbrett
#### Frage:
Ein Schachbrett ist 8x8 (64 Felder). Wenn aufdem ersten Feld 0 Reiskörner, dem zweitem Feld 1 Reiskorn und sich die Anzahl Reiskörner mit jedem weiterem Feld verdoppelt. Wie viel Reiskörner befinden sich auf dem letsten Feld?

#### Antwort:
Die Antwort lautet 2^63 <=> 9223372036854775807. 63, da das erste Feld keins beinhaltet und 2^0 Eins ergibt. 

Man musste die Antwort auch mit einem Java programm beweisen sollen <br>
Code: 
```
public class Main {
    public static void main(String[] args) {
        long number = (long) Math.pow(2,63);

        System.out.println(number);
    }
}
``` 
### Aufgabe: Zahlensysteme
| Name | Beispiel mit Nummer 16
|------|----------
| Zehner | 16
| Binär | 10000
| Oktal | 20
| Hexadezimal | 10

#### Aufgabe 2. 911 zu Binär 
911 in Zehner ist 1110001111 in Binär

#### Aufgabe 3. 10110110 zu Zehner
10110110 in Binär ist 182 in Zehner

#### Aufgabe 4. 1110001010100101 zu Hexadezimal
0101 = 5 = 5 <br>
1010 = 10 = a <br>
0010 = 2 = 2 <br>
1110 = 14 = e <br>
<br>
1110001010100101 in Binär e2a5 in Hexadezimal

#### Aufgabe 5. Zahl A: 11011001 plus Zahl B: 01110101
11011001 = 217 <br>
01110101 = 117 <br>
217 + 117 = 334 <br>
334 - 256 = 78  --> 1 <br>
78 - 128 = null --> 0 <br>
78 - 64 = 14    --> 1 <br> 
14 - 32 = null  --> 0 <br>
14 - 16 = null  --> 0 <br>
14 - 8 = 6      --> 1 <br>
6 - 4 = 2       --> 1 <br>
2 - 2 = 0       --> 1 <br>
0 - 1 = null    --> 0 <br>
= 101001110

#### Aufgabe 6. Was bedeutet "11000000.10101000.01001100.11010011"
Ich denke, dass 11000000.10101000.01001100.11010011 für eine IPv4 Addresse steht. <br>
Umgerechnet in Dezimal wäre es 192.168.76.21

#### Aufgabe 7. Was bedeutet die Bit Kombination "1011 1110 - 1000 0011 - 1000 0101 - 1101 0101 - 1110 0100 - 1111 1110"
Ich denke, dass die Kombination umgerechnet in Hexadezimal eine IPv6 Addresse steht. <br>
Umgerechnet in Hexadezimal wäre es be.83.85.d5.e4.fe




