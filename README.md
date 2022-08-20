# javascript-map-printNames

# Überblick
Zum Einstieg wollen wir ein einfaches Beispiel mit `map()` machen.

Aus einer Liste mit Personen soll für jede Person eine Begrüßung in der Konsole ausgegeben werden.

## Aufgabenstellung - Teil 1
Zunächst brauchen wir eine Liste mit Personen. Dazu verwenden wir ein Array.

Deklariere ein Array mit den Namen: John, Chuck, Henry, Oscar, Ryan, Bob, Pete.

## Aufgabenstellung - Teil 2
Nun müssen wir die Personen aus dem Array einzeln begrüßen.

Wende `map()` auf das Array an. 

## Aufgabenstellung - Teil 3
`map()` muss jetzt noch eine Aufgabe erledigen.

Dazu verwenden wir folgende Syntax:

```
(element) => {
    // mache etwas mit element
}
```

Konktet ist `element` die Person nacheinander im Array.

Sie soll beispielsweise für John mit der Begrüßung `Willkommen! Wie geht es Ihnen, John?` begrüßt werden.

## Bonus
Findest du einen Weg, die Funktion aus der `map()` auszulagern?

D.h. die Funktion wird in `map()` nur noch aufgerufen, aber dort nicht definiert.
