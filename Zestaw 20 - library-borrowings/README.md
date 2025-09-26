# Zestaw 20 – library-borrowings

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)

## Dwa zbiory danych

### `datasource1` – wypożyczenia książek (borrowings)

Dane mają format CSV, pliki posiadają nagłówek.

Pola w pliku:

0. `borrow_id` – unikalny identyfikator wypożyczenia (UUID)  
1. `book_id` – identyfikator książki (odniesienie do słownika książek)  
2. `reader_id` – unikalny identyfikator czytelnika (np. READER0000001)  
3. `borrow_date` – data wypożyczenia (`yyyy-MM-dd`)  
4. `return_date` – data zwrotu (`yyyy-MM-dd`)  
5. `status` – status wypożyczenia (`RETURNED` lub `NOT_RETURNED`)  

---

### `datasource4` – dane dotyczące książek (books)

Dane mają format CSV, pliki posiadają nagłówek.

Pola w pliku:

0. `book_id` – unikalny identyfikator książki (np. BOOK00001)  
1. `title` – tytuł książki  
2. `author` – autor książki  
3. `genres` – gatunki książki (lista rozdzielana średnikiem, np. Fantasy;Thriller)  
4. `languages` – języki dostępności książki (lista rozdzielana średnikiem, np. en;pl)  
5. `publisher` – wydawnictwo  
6. `year` – rok wydania (1950–bieżący rok)  


