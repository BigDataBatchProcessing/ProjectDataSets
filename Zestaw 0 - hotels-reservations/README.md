# Zestaw 0 – hotels-reservations

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)

## Dwa zbiory danych

### `datasource1` – rezerwacje hotelowe (reservations)

Dane mają format CSV, pliki posiadają nagłówek.

Pola w pliku:

0. `reservation_id` – unikalny identyfikator rezerwacji (UUID)  
1. `hotel_id` – identyfikator hotelu (odniesienie do słownika hoteli)  
2. `guest_id` – unikalny identyfikator gościa (np. GUEST0000001)  
3. `check_in` – data i godzina zameldowania (`yyyy-MM-dd'T'HH:mm`)  
4. `check_out` – data i godzina wymeldowania (`yyyy-MM-dd'T'HH:mm`)  
5. `price` – cena rezerwacji (liczba zmiennoprzecinkowa)  
6. `status` – status rezerwacji (`Completed`, `Cancelled`, `No-show`)  

---

### `datasource4` – dane dotyczące hoteli (hotels)

Dane mają format CSV, pliki posiadają nagłówek.

Pola w pliku:

0. `hotel_id` – unikalny identyfikator hotelu (np. HOTEL0001)  
1. `name` – nazwa hotelu  
2. `region` – region geograficzny (`North`, `South`, `East`, `West`, `Central`)  
3. `category` – kategoria hotelu (`Budget`, `Standard`, `Premium`, `Luxury`)  
4. `rooms` – liczba pokoi w hotelu (50–200)  
