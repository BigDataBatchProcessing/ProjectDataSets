# Zestaw 14 – bus-trips

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)  
Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – informacje o przejazdach autobusowych (trips)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `trip_id` – unikalny identyfikator przejazdu (UUID)  
1. `operator_id` – identyfikator operatora (`operator_id` z pliku operatorów)  
2. `departure_city` – miasto początkowe przejazdu  
3. `arrival_city` – miasto docelowe przejazdu  
4. `departure_time` – planowana data i godzina odjazdu (`yyyy-MM-dd'T'HH:mm`)  
5. `arrival_time` – planowana data i godzina przyjazdu (`yyyy-MM-dd'T'HH:mm`)  
6. `passengers` – liczba pasażerów w danym przejeździe  
7. `ticket_price` – cena biletu w USD  
8. `status` – status przejazdu (`On time`, `Delayed`, `Cancelled`)  

### `datasource4` – informacje o operatorach autobusowych (operators)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `operator_id` – unikalny identyfikator operatora (UUID)  
1. `operator_name` – nazwa operatora  
2. `region` – region działania operatora (`North`, `South`, `East`, `West`, `Central`)  
3. `service_type` – rodzaj usług świadczonych przez operatora (`Express`, `Local`, `Intercity`)  
