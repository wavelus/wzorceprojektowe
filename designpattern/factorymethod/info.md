# Metoda wytwórcza (Factory method, Virtual constructor)

## Opis

Metoda wytwórcza to kreacyjny wzorzec projektowy, który udostępnia nam interfejs do tworzenia obiektów w superklasie, jednocześnie zezwala subklasom na zmianę typów obiektów które będą tworzone. Tworzeniem egzemplarzy obiektów zajmują się podklasy.

## Zastosowanie

### Przykładowy problem do rozwiązania [Wikipedia]

Tworzysz aplikację do zarządzania logistyką. Początkowo założyłeś iż jedynym obsługiwanym środkiem transportu będzie transport lądowy - ciężarówkami. Większość kodu, obsługującego znajduje się w klasie ``Ciężarówka``. Pewnego dnia postanawiasz dodać do programu obsługę logistyki morskiej - statkami, do swojej aplikacji.

**Problem:** 

### Jak zastosujemy wzorzec?

### Zalety

## Podobne wzorce

## Diagramy UML

## Kod źródłowy

## Źródła

- [Wikipedia](https://pl.wikipedia.org/wiki/Metoda_wytw%C3%B3rcza_(wzorzec_projektowy))
- [algorytm.org](http://www.algorytm.org/wzorce-projektowe/metoda-wytworcza-factory-method.html)
- [open.agh.edu.pl](http://zasoby.open.agh.edu.pl/~09sbfraczek/metoda-wytworcza%2C1%2C29.html)
- [refactoring.guru](https://refactoring.guru/design-patterns/factory-method)