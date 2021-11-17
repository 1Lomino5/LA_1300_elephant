# LA_1300_elephant
#### Ein Vokabeltrainer, bei dem man eigene Dateien verwenden kann. Programmiert in C#.
<br>

#### Was ist das Ziel dieses Portfolios?
###### Die LeserInnen können am Ende dieses Beitrages eine Funktion in C# erstellen und kennen den Unterschied zwischen einer Funktion mit und ohne Rückgabewert.
<br>

## Funktionen in C#
Was ist eine Funktion?
Eine Funktion ist ein Stück Code, welches vorprogrammiert wurde. Man kann die Funktion immer wieder verwenden, ohne sie neu schreiben zu müssen.
Es gibt mehrere Arten von Funktionen, diese kann man in zwei Gruppen unterteilen: Funktionen mit und ohne Rückgabewert.
Bei Funktionen mit Rückgabewert wird nach dem Ausführen der Funktion eine gewisse Datei zurückgegeben, welche in der Main Methode weiterverwendet werden kann.
Wenn eine Funktion ohne Rückgabewert verwendet wird bedeutet das, dass man die Funktion ausführt und wenn diese beendet ist forfährt, jedoch dieses Mal keine Daten mitnimmt.
Es ist darauf zu achten, dass die Funktion ausserhalb der Main Methode erstellt wird.
Da dieses Portfolio nur die Grundlagen von Funktionen erklären soll, werde ich nicht auf die Details wie ``static`` und ``pubilc``oder Parameter eingehen.


### Anleitung
#### Funktion mit Rückgabewert
Um eine Funktion mit Rückegabewert zu erstellen, geht man wie folgt vor. Als erstes wählt man die Art der Funktion, für unser Beispiel verwenden wir die ``static`` Funktion. 
Da wir hier mit einem Rückgabewert arbeiten, muss man nun einen Datentyp für die Rückgabe wählen, ich entscheide mich für ein ``string``. Für den nächsten Schritt geben wir der Funktion einen Namen, zum Beispiel ``AlterErweitern``. Als letztes fügt man noch ``()`` ein, in diese Klammern könnte man Parameter eingeben.
Hinter diese Angaben setzt man noch ``{}``, darin wird der Code geschrieben. Ein sehr wichtiger Punkt bei einer solchen Funktion ist, dass man in den {} am Schluss mit dem Befehl ``return()`` einen Wert zurückgibt, weil sonst ein Fehler ensteht.
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
Bei einer Funktion ohne Rückgabewert ist das Ganze etwa gleich, nur zwei Punkte unterscheiden sich. Anstatt dass man einen Datentyp wählt, gibt man hier einfach nur ``void`` ein und in den ``{}`` wird kein ``return`` verwendet.
#### Ein Beispiel für diese Art von Funktion wäre also:
```csharp
static void string AlterErweitern()
{
string Alter;
Alter = Alter + 1;
Console.WriteLine(Alter);
}
```
#### Um diese Funktion in der Main Funktion zu verwenden, kann man diese so aufrufen und einem Wert zuweisen (Beispiel ist im Main):
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
Mit der Anleitung sollten die LeserInnen wissen, wie man eine Funktion in C# erstellt und was der Unterschied zwischen Funktionen mit und ohne Rückgabewert ist.


## Reflexion
Das Projekt LA_1300 war das erstes Projekt in C#, welches ich in einer Gruppe bearbeitete. Auf dem Weg zum fertigen Produkt gab es immer wieder Probleme, einmal war ein Kollege krank und die Woche darauf habe ich mich erkältet. Aufgrund dessen musste wir versuchen, digital miteinander zu kommunizieren und so das Projekt voranzutreiben. Auch wenn dies manchmal ein wenig stressig war, bin ich froh über diese Erfahrung. Nach einiger Zeit haben wir gute Wege gefunden, um miteinander zu arbeiten. Mein VBV (Verbesserungsvorschlag) für das nächste Projekt wäre Personen, welche physisch nicht dabei sein können, besser in das Projekt einzubinden. Ich habe selbst gemerkt, dass es störend sein kann, wenn man wenig Informationen bekommt.
