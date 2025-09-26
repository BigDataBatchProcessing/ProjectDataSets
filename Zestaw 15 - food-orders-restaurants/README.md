# Zestaw 15 – food-orders

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)  
Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – informacje o zamówieniach (orders)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `order_id` – unikalny identyfikator zamówienia (UUID)  
1. `restaurant_id` – identyfikator restauracji (`restaurant_id` z pliku restauracji)  
2. `order_date` – data i godzina złożenia zamówienia (`yyyy-MM-dd'T'HH:mm`)  
3. `items_count` – liczba pozycji w zamówieniu  
4. `total_price_usd` – łączna cena zamówienia w USD  
5. `payment_type` – forma płatności (`Cash`, `Card`, `Online`)  
6. `status` – status zamówienia (`Completed`, `Cancelled`, `Pending`)  

### `datasource4` – informacje o restauracjach (restaurants)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `restaurant_id` – unikalny identyfikator restauracji (UUID)  
1. `name` – nazwa restauracji  
2. `city` – miasto, w którym działa restauracja  
3. `country` – kraj, w którym działa restauracja  
4. `cuisine` – typ kuchni (`Italian`, `Chinese`, `Mexican`, `Polish`, `Indian`, `Japanese`, `American`, `Greek`, `French`, `Thai`)  
