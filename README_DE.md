# Erkunden der CSS Kaskade

Diese Übung besteht aus einer Reihe von CSS Kaskaden- und Vererbungsrätseln.

## Aufgaben

### Aufgabe 1

Öffne [task_1.html](./task_1.html)

- Bearbeite nicht das `<style>` Element!
- Bearbeite das **HTML**, sodass das innere Feld quadratisch ist und eine `hotpink` Hintergrundfarbe mit einem gestrichelten `lightblue` Rand hat

### Aufgabe 2

Öffne [task_2.html](./task_2.html)

- Bearbeite nicht das `<style>` Element!
- Bearbeite das **HTML**, sodass das Feld eine `hotpink` Hintergrundfarbe hat

### Aufgabe 3

Öffne [task_3.html](./task_3.html)

Beantworte die folgenden Fragen direkt hier in der README:

- Warum ist der Text des `<span>` Elements fett?
- *Weil das <span> Element nimmt das Atribute von Elternelement main.*
<span>main {
        font-weight: bold;
           }
</span>
- Warum ist der Text der `<h2>` und `<p>` Elemente rot?
- *Weil die Elemente `<h2>`  und `<p>` nehmen das Atribute von Elternelement main.*
<span>main {
        color: red;
           }
</span>
- Warum ist der Text des `<span>` Elements nicht rot?
- *Weil die `<p>` Elemente sind im gleichen Ebene und im style wird die letzte Programmierzeile übernommen.*
- Warum haben `<h2>`, `<p>` und `<span>` jeweils keinen Rand?
- *Weil nur die Äußere Rand gegeben ist.*
- Wenn du Zeile 17 auskommentierst, warum bleibt das `<span>` blau?
- *Weil die `<p>` Elemente sind im gleichen Ebene und im style wird die letzte Programmierzeile übernommen.*
- Wenn du Zeile 18 auskommentierst, warum wird das `<span>` grün?
- *Weil !important wird ALLE vorherigen Stilregeln für diese bestimmte Eigenschaft dieses Elements überschrieben!*

### Aufgabe 4

Öffne [task_4.html](task_4.html)

- Bearbeite die **HTML** Datei überhaupt nicht!
- Erstelle und bearbeite `task_4.css`, sodass jedes Mal, wenn das Wort **Cucumbers** auf der Seite erscheint, es die Schriftfarbe `greenyellow` hat
- Alle anderen Wörter müssen die Schriftfarbe `palegoldenrod` haben

### Aufgabe 5

Öffne [task5.html](task_5.html)

Diese ist fast identisch mit Aufgabe 4! Die Anweisungen sind die gleichen, aber _dieses Mal_ ist etwas anders... 🤫

- Bearbeite die **HTML** Datei überhaupt nicht!
- Erstelle und bearbeite `task_5.css`, sodass jedes Mal, wenn das Wort **Cucumbers** auf der Seite erscheint, es die Schriftfarbe `greenyellow` hat
- Alle anderen Wörter müssen die Schriftfarbe `palegoldenrod` haben

> Tipp: Vergleiche das HTML mit `task_4.html`, um zu sehen, was sich geändert hat!
