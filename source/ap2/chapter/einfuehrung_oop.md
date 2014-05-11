# Einführung in die objektorientierte Programmierung

### Aufgabenstellung

Schreiben Sie eine Java Klasse, welche die Eigenschaften von einem Haus verkörpert. Ein Haus soll zunächst zur Vereinfachung durch seine Grundfläche beschrieben werden.

  1. Welche Instanzvariablen werden bis zu diesem Punkt benötigt?
  2. Wie könnte ein sinnvoller Konstruktor aussehen?

Später soll die Klasse so erweitert werden, dass beliebig viele Personen in das Haus einziehen können. Schreiben sie für den Typ `Person` ebenfalls eine eigene Klasse, welche `Vornamen`, `Nachnamen` und `Alter` speichert.

  3. Wie können nun mehrere Objekte vom Typ `Person` innerhalb `Haus` gespeichert werden?

Die fertige Klasse `Person` sollte folgende Methoden aufweisen:

```java
int getAlter()
void setAlter(int alter)
```

Die fertige Klasse `Haus` sollte folgende Methoden aufweisen:

```java
public double getFlaeche() // Berechnet die Fläche des Hauses
public void setPersonen(Person[] person) // Lässt Personen in das Haus einziehen
```

### Zusatzaufgabe

Schreiben sie eine Methode, die die älteste Person im Haushalt berechnet.

```java
public Person getAeltestePerson() // Gibt die älteste Person des Haushalts zurück
```

In welcher Klasse sollte diese Methode sinnvollerweise implementiert werden?
