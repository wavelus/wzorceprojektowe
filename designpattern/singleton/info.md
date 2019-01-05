# Singleton

## Opis

Singleton jest jednym z najprostszych wzorców projektowych. Jego celem jest ograniczenie możliwości tworzenia obiektów danej klasy do jednej instancji oraz zapewnienie globalnego dostępu do stworzonego obiektu – jest to obiektowa alternatywa dla zmiennych globalnych.

Singleton implementuje się poprzez stworzenie klasy, która posiada statyczną metodę getInstance(). Metoda ta sprawdza, czy istnieje już instancja tej klasy, jeżeli nie – tworzy ją i przechowuje jej referencję w prywatnym polu. Aby uniemożliwić tworzenie dodatkowych instancji, konstruktor klasy deklaruje się jako prywatny lub chroniony.

## Zalety

- Pobieranie instancji klasy jest niewidoczne dla użytkownika. Nie musi on wiedzieć, czy w chwili wywołania metody instancja istnieje czy dopiero jest tworzona.
- Tworzenie nowej instancji zachodzi dopiero przy pierwszej próbie użycia.
- Klasa zaimplementowana z użyciem wzorca singleton może samodzielnie kontrolować liczbę swoich instancji istniejących w aplikacji.

## Wady

- Brak elastyczności, ponieważ już na poziomie kodu, na „sztywno” określana jest liczba instancji klasy.
- Utrudnia testowanie i usuwanie błędów w aplikacji.
- Jest przestarzałym wzorcem, nie nadaje się do wykorzystania w wielowątkowych aplikacjach.