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


