# LA_1300_elephant
#### Ein Vokabeltrainer, bei dem man eigene Dateien verwenden kann. Programmiert in C#.
<br>

#### Was ist das Ziel dieses Portfolios ?
###### Die LeserInnen können am Ende dieses Beitrages eine Funktion in C# erstellen und kenne den Unterschied zwischen einer Funktion mit und ohne Rückgabewert
<br>

## Funktionen in C#
Was ist Funktion?
Eine Funktion ist ein Stück Code welches vorprogrammiert wurde, welches man immer wieder verwenden kann ohne diese neu schreiben zu müssen.
Es gibt mehrer Arten von Funktionen, diese kann man in 2 Gruppen unterteilen, Funktion mit und ohne Rückgabewert.
Bei Funktionen mit Rückgabewert wird nach dem Ausführen der Funktion eine gewisse Datei zurück gegeben welche man in der Main Methode weiter verwendet werden kann.
Wenn eine Funktion ohne Rückgabewert verwendet wird bedeutet das, dass man die Funktion ausführt und wenn diese beendet ist forfährt jedoch dieses mal keine Daten mitnimmt.
Zwei wichtige Punkte welchen man beachten muss, wenn man eine Funktion verwendent ist, dass erstens man die Funktion ausserhalb der Main Methode erstellt und da dieses Portfolio nur die Grundlagen von Funktionen erklären soll werde ich nicht in die Details wie ``static`` und ``pubilc``oder Parameter eingehen.


### Anleitung
#### Funktion mit Rückgabewert
Um eine Funktion mit Rückegabewert zu erstellen geht man wie folgt vor. Als erstes wählt man die Art der Funktion, für unser Beispiel verwenden wir die ``static`` Funktion. 
Da wir hier mit einem Rückgabewert arbeiten muss man nun einen Datentyp für die Rückgabe wählen, ich entscheide mich für ein ``string``. Für den nächsten Schritt geben wir der Funktion einen Namen, zum Beispiel ``AlterErweitern``. Als letztes fügt man noch ``()`` in diese könnte man Parameter eingeben auf welche ich jedoch auch nicht genauer eingehe.
Hinter diesen Angaben setzt man noch ``{}`` Klammern in welche man den Code dann schreibt. Ein sehr wichtiger Punkt bei einer solchen Funktion ist das man in den {} am Schluss mit dem Befehl ``return()`` einen Wert zurück gibt weil sonst ein Fehler ensteht.
##### Hier ein Beispiel für den Code:
```csharp
static string AlterErweitern() 
{
string Alter;
Alter = Alter + 1;
return(Alter)
}
```


#### Funktion ohne Rückgabewert
Bei einer Funktion ohne Rückgabewert ist das ganze etwa gleich, nur 2 Punkte unterscheiden sich. Anstatt das man einen Datentyp wählt gibt man hier einfach nur ``void`` ein und in den ``{}`` wird kein ``return`` verwendet.
#### Ein Beispiel für diese Art von Funktion wäre also:
```csharp
static void string AlterErweitern()
{
string Alter;
Alter = Alter + 1;
Console.WriteLine(Alter);
}
```
#### Um diese Funktion in der Main Funktion zu verwenden kann man diese so Aufrufen und einem Wert zuweisen (Beispiel ist im Main):
Mit Rückgabe:
```csharp
string Alter = AlterErweitern();
```
Ohne Rückgabe:
```csharp
AlterErweitern();

```





 
 ### Einbettung in einen Code
Im folgenden Bild sieht man ein Beispiel, wo man diese Funktionen benutzen könnte.

![alt text](https://raw.githubusercontent.com/1Lomino5/LA_1300_elephant/main/Bild%20f%C3%BCr%20Portfolio.JPG)



## Verifikation
Mit der Anleitung sollten die Leser wissen, wie man eine Funktion in C# erstellt und was der Unterschied zwischen Funktionen mit und ohne Rückgabewert ist.


## Reflexion
Das Projekt LA_1300 war das erstes Projekt in C# welches in einer Gruppe bearbeitete. Auf dem Weg zum fertig Produkt gab es immer wieder Probleme, einmal war ein Kollege krank und die Woche darauf habe ich mich erkältet. Aufgrund dessen musste wir versuchen Digital miteinander zu kommunizieren und so zu versuchen das Projekt nach vorne zu treiben. Auch wenn dies manchmal ein wenig stressig war bin ich froh über diese Erfahrung. Nach einiger Zeit haben gute Wege gefunden um miteinander zu Arbeiten, mein VBV (Verbesserungsvorschlag) für das nächste Projekt wäre das wennn wieder eine Person fehlt, die Person welche physisch nicht dabei sein kann besser in das Projekt einzubinden. Das würde ich tun da ich selbst gemerkt habe das es störend sein kann wenn man wenig Informationen bekommt.
