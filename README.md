# Basic Recap

## Beantworte folgende Fragen

- Was ist das besondere an einem `block` Element?

  Antwort: Block Elemente nutzen immer die komplette Fensterbreite.

- Was ist das besondere an einem `inline` Element?

  Antwort:Inline-Elemente sind immer nur so breit wie ihr Inhalt, es wird daher auch kein Zeilenumbruch erzeugt, solange die Breite der Zeile ausreicht, um mehrere Inline-Elemente nebeinander zu positionieren. Zu der Kategorie der Inline-Element gehören beispielsweise: span. strong.

- Was ist das besondere an einem `inline-block` Element?

  Antwort:Im Gegensatz zu reinen Blockelementen erzwingen sie jedoch keinen Zeilenumbruch vor und nach sich. Breite und Höhe: Im Gegensatz zu reinen Inline-Elementen können Elemente mit "display: inline-block" eine explizit festgelegte Breite und Höhe haben.

- Welche Art von Element ist ein `input` Element?

  Antwort:Die Art des Eingabefeldes wird über das type -Attribut festgelegt.

- Welche Art von Element ist ein `table` Element?

  Antwort:Das <table> HTML Element repräsentiert tabellarische Daten – also Informationen, die in einer zweidimensionalen Tabelle dargestellt sind, bestehend aus Zeilen und Spalten mit Zellen, die Daten enthalten.

- Welche Art von Element ist ein `div` Element?

  Antwort:DIV ist ein Block-Element.

- Welche Art von Element ist ein `a` Element?

  Antwort:Das a-Element stellt einen Verweis, (Hyper-)Link auf eine (andere) Web-Adresse dar.

- Welche Art von Element ist ein `body` Element?

  Antwort:HTML <body> is ein HTML-Element, mit dessen Hilfe Inhalte eines Dokuments dargestellt werden.

- Welche Art von Element ist ein `form` Element?

  Antwort:Das Element <form>
  Alles was innerhalb des Elements steht gehört zu einem Formular.

- Wann funktioniert `text-aline: center`?

  Antwort:Wenn Block-Elemente als Inline-Elemente deklariert werden, kann text-align nicht wirken. left richtet Text links aus, right rechts, center zentriert einen Text und justify setzt den Text als Blocksatz.

- Wie kann man ein `block` Element zentrieren?

  Antwort: Bei einem Block-Element (wie einem div ), das eine spezifische Breite hat, kannst Du margin-left: auto; margin-right: auto; anwenden, um es horizontal zu zentrieren.

- Wie kennzeichnet man eine `id` im CSS?

  Antwort: IDs mit einer Raute + ID-Name (#idname).

## Aufgaben

Die Hauptaufgabe wird es sein eine Webseite zu bauen, die dem Bild so ähnlich wie möglich kommt. Beachte hierbei folgende Punkte:

1. Der Header hat eine Höhe von 10% der Höhe des Viewports

2. Die Navigation hat eine Höhe von `40px`, allerdings in `rem` und bleibt oben am Fenster kleben (KLEBEN!).

   - Richte die Links rechts aus. **Benutze KEIN position!**

3. Alle Sections sind Zentriert, mindestens 30% der Höhe des Viewports hocht und haben haben `1.5rem` abstand zueinander.

   - Section 1
     - in dieser Section sind zwei Cards (`div`), die `400px` Breit und `300px` Hoch sind. **Benutze KEIN position!**
   - Section 2
     - Das Formular soll mittig ausgerechtet sein und eine Breite von `15rem` haben.

![Beispielbild Oben](./images/recap_exmaple01.png)

- Section 3
  - richte das Hintergrundbild so gut wie möglich aus
  - sorge dafür, dass das Hintergrundbild nur noch `60%` der ursprünglichen Helligkeit (`brightness`) hat.

4. Der Footer hat eine Höhe von `160px` in `rem`
   - Richte die Icons rechts und die Links links aus. **Nutze KEINE position!**

![Beispielbild Unten](./images/recap_exmaple02.png)

## Hilfestellung

[Klassen und ID´s](https://github.com/dci-fbw-wd-24-d07-a/resources/tree/main/02-UIB/01-fundamentals/02-UI-styles-classes-id#classes-vs-idś)

[Margin und Padding](https://github.com/dci-fbw-wd-24-d07-a/resources/tree/main/02-UIB/04-data/02-forms#formular)

[block, inline und inline-block](https://github.com/dci-fbw-wd-24-d07-a/resources/tree/main/02-UIB/02-Boxes/01-UI-Box-Model#ändern-der-eigenschaften-eines-elementes)

[Background Image vs Image](https://github.com/dci-fbw-wd-24-d07-a/resources/tree/main/02-UIB/02-Boxes/02-ui-bg#background-image-vs-image)

[Forms](https://github.com/dci-fbw-wd-24-d07-a/resources/tree/main/02-UIB/04-data/02-forms#formular)
