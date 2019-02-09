# Wzorce projektowe

### Czym są wzorce projektowe?

Wzorce projektowe to typowe rozwiązania często powtarzających się problemów w projektowaniu oprogramowania. Wzorce są jak plany, które bierzesz i dostosowujesz do problemu z jakim się spotykasz w swoim kodzie.

Wzorzec to nie jest kawałek kodu który zwyczajnie wstawiasz do swojego programu. Wzorzec to koncept mówiący o tym jak rozwiązywać dany problem. Wzorce są jak plany, widzisz jaki ma być rezultat, ale to w jaki sposób go osiągniesz zależy tylko i wyłącznie od ciebie.

### Co możemy znaleść we wzorcu?

Większość wzorców opisana jest bardzo formalnie co pozwala programistom odtworzyć je w wielu kontekstach. Każdy opis wzorca powinien zawierć następujące elementy:

1. Opis
- do jakiej klasy wzorców należy i dlaczego,
- cel stosowania wzorca,
- wyjaśnienie problemu i sposobu jego rozwiązania.
2. Zastosowanie
- w jakich przypadkach zastosujemy dany wzorzec,
- zalety i wady wzorca.
3. Podobne wzorce
- dlaczego są podobne,
- jakie różnice występują,
- jakie przewagi posiadają,
- dlaczego ten wzorzec jest lepszy/gorszy od innych.
4. Diagramy UML
- struktura wzorca,
- "co czym jest, i za co odpowiada",
- jakie odpowiedzialności posiadają poszczególne elementy.
5. Kod źródłowy
- przykład(y) implementacji wzorca,
- omówienie, który kawałek kodu mapuje się na dany element UMLa,
- ogólne omówienie wzorca.

## Spis treści

### Wzorce kreacyjne 

Inne nazwy: konstrukcyjne, creational design patterns. Opisują elastyczne sposoby tworzenia obiektów. Uniezależniają system od sposobu tworzenia obektów. Wzpomagają ponowne użycie istniejącego kodu.

#### [Budowniczy (Builder)](designpattern/builder/info.md)

#### [Fabryka abstrakcyjna (Abstract factory)](designpattern/abstractfactory/info.md)

#### [Metoda wytwórcza (Factory method)](designpattern/factorymethod/info.md)

#### [Prototyp (Prototype)](designpattern/prototype/info.md)

#### [Singleton](designpattern/singleton/info.md)

### Wzorce strukturalne

Inna nazwa: structural design patterns. Opisują sposob konstrukcji struktur obiektowych. Korzystają z dziedziczenia i delegacji. Mówią nam w jaki sposób składać obiekty i klasy w większe struktury, zachowując jednocześnie elastyczność i wydajność struktur.

#### [Adapter](designpattern/singleton/info.md)

#### [Dekorator](designpattern/singleton/info.md)

#### [Fasada](designpattern/singleton/info.md)

#### [Kompozyt](designpattern/singleton/info.md)

#### [Most](designpattern/singleton/info.md)

#### [Pełnomocnik](designpattern/singleton/info.md)

#### [Pyłek](designpattern/singleton/info.md)

### Wzorce behawioralne

Inne nazwy: czynnościowe, behavioral design patterns. Opisują algorytmy i przydział odpowiedzialności. Charakteryzują sposob interakcji między obiektami. Dbają o skuteczno komunikację i podział odpowiedzialności między obiektami.

#### [Interpreter](designpattern/singleton/info.md)

#### [Iterator](designpattern/singleton/info.md)

#### [Łańcuch zobowiązań](designpattern/singleton/info.md)

#### [Mediator](designpattern/singleton/info.md)

#### [Metoda szablonowa](designpattern/singleton/info.md)

#### [Obserwator](designpattern/singleton/info.md)

#### [Odwiedzający](designpattern/singleton/info.md)

#### [Pamiątka](designpattern/singleton/info.md)

#### [Polecenie](designpattern/singleton/info.md)

#### [Stan](designpattern/singleton/info.md)

#### [Strategia](designpattern/singleton/info.md)

### Wzorce mapowania zachowań i mapowanie obiektowo-relacyjne

#### [Klucz główny/identyfikator](designpattern/singleton/info.md)

#### [Mapowanie klucza obcego](designpattern/singleton/info.md)

#### [Tabela asocjacji](designpattern/singleton/info.md)

#### [Odwzorowanie składowych](designpattern/singleton/info.md)

#### [Wartość wbudowana](designpattern/singleton/info.md)

#### [Duży obiekt serializowany](designpattern/singleton/info.md)

#### [Dziedziczenie do pojedyńczej tabeli](designpattern/singleton/info.md)

#### [Dziedziczenie do tabel klas](designpattern/singleton/info.md)

#### [Dziedziczenie do tabel konkretnych](designpattern/singleton/info.md)

#### [Odwzorowanie dziedziczenia](designpattern/singleton/info.md)

#### [Jednostka pracy](designpattern/singleton/info.md)

#### [Mapa identyfikacji](designpattern/singleton/info.md)

#### [Odczyt na rządanie](designpattern/singleton/info.md)

#### [Odwzorowanie metadanych](designpattern/singleton/info.md)

#### [Obiekt zapytania](designpattern/singleton/info.md)

#### [Repozytorium](designpattern/singleton/info.md)

#### [Brama danych tabeli (Table data gateway)](designpattern/tabledatagateway/info.md)

#### [Brama danych wiersza (Row data gateway)](designpattern/rowdatagateway/info.md)

#### [Rekord aktywny](designpattern/singleton/info.md)

#### [Odwzorowanie danych](designpattern/singleton/info.md)

## Informacje

#### Autorzy

[Grzegorz Kolano](https://github.com/grzechukol)

#### Opis

Projekt skupia się na możliwie krótkim i kompletnym opisaniu wybranych wzorców projektowych. Każdy opis powinien zawierać wszystko co trzeba wiedzieć, aby wyjaśnić, jak działa wzorzec, kiedy go zastosujemy, i dlaczego zastosujemy właśnie ten wzorzec. Więcej informacji można znaleźć w źródłach z których korzystano przy tworzeniu niniejszego podsumowania.

Niniejsze opracownie dostępne jest na [licencji MIT](LICENSE).

#### Źródła

Przy tworzeniu niniejszego opracowania korzystano z poniższych źródeł. Dziękuje się autorom za trud poświęcony w przygotowanie materiałów, których użyto podczas przygotowywaniu tego opracowania.

- [Wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern)
- [lukasz-socha.pl](https://lukasz-socha.pl/php/wzorce-projektowe-spis-tresci/)
- [kobietydokodu.pl](https://kobietydokodu.pl/21-wzorce-projektowe/)
- [edu.pjwstk.edu.pl](http://edu.pjwstk.edu.pl/wyklady/zap/scb/W5/W5.htm)
- [algorytm.org](http://www.algorytm.org/wzorce-projektowe/)
- [open.agh.edu.pl](http://zasoby.open.agh.edu.pl/~09sbfraczek/wzorce-projektowe-wstep%2C1%2C57.html)
- [refactoring.guru](http://refactoring.guru/)
- [sourcemaking.com](https://sourcemaking.com/)