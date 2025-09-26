# Zestaw 12 – sales-products

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)  
Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – informacje o transakcjach (transactions)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `transaction_id` – unikalny identyfikator transakcji (UUID)  
1. `product_id` – identyfikator produktu (`product_id` z `datasource4`)  
2. `quantity` – liczba sztuk sprzedanych w ramach transakcji  
3. `unit_price` – cena jednostkowa produktu w dolarach amerykańskich  
4. `payment_type` – metoda płatności (`Card`, `Cash`, `Transfer`, `Mobile`)  
5. `transaction_time` – data i godzina transakcji (`yyyy-MM-dd'T'HH:mm`)

### `datasource4` – informacje na temat produktów (products)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `product_id` – unikalny identyfikator produktu (UUID)  
1. `name` – nazwa produktu  
2. `category` – kategoria produktu (`Electronics`, `Clothing`, `Food`, `Books`, `Sports`, `Toys`, `Home`, `Beauty`)  
3. `brand` – nazwa marki produktu  
4. `supplier` – branża dostawcy
