# Benennung

Bei der Benennung von Variablen und Methoden sollte auf die folgende Punkte geachtet werden

## Variablen

Camel Case:
- Verwende Camel Case für Variablennamen
- Beispiel: myVariable, anotherVariable

Deskriptive Namen:
- Wähle aussagekräftige und beschreibende Namen für Variablen
- Vermeide einzeichenlange Variablennamen, es sei denn, sie sind Schleifenindizes

## Methoden
Camel Case:
- Verwende Camel Case für Methodennamen
- Beispiel: calculateTotal(), getUserData()

Aussagekräftige Namen:
- Benutze aussagekräftige und klare Namen für Methoden, die ihre Funktion leicht verständlich machen
- Beispiel: getUserName(), calculateTotalPrice()

## Boolesche Variablen:
Aussagekräftige Namen:
- Verwende prägnante Namen für boolesche Variablen, die ihre Bedeutung klar machen
- Beispiel: isReady, hasPermission

## Datentypen

### Interfaces

- Verwende Pascal Case für Interface-Namen
- Beispiel: Person, CarOptions

```
interface Person {
  name: string;
  age: number;
}
```

### Typealias
- Verwende Pascal Case für den Namen von Typaliasen
- Beispiel: User, ProductInfo

```
type User = {
  id: string;
  username: string;
};
```

### Enumarations:
- Verwende Pascal Case für Namen von Enumerations und Singular für Enumerationswerte
- Beispiel: Color, Direction

```
enum Color {
  Red,
  Green,
  Blue,
}
```

## Module
- Verwende Pascal Case für Namen von Namespace und Modulen
- Beispiel: MyModule, MyNamespace

