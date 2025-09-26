# Zestaw 23 – cars-rentals

### datasource1 – dane dotyczące wypożyczeń samochodów (rentals)

Dane mają format CSV, pliki posiadają nagłówki.

Pola w pliku:

0. `rental_id` – unikalny identyfikator wypożyczenia (UUID)  
1. `car_id` – identyfikator samochodu powiązanego z wypożyczeniem  
2. `customer_id` – unikalny identyfikator klienta (np. `CUST0000001`)  
3. `rental_start` – data i godzina rozpoczęcia wypożyczenia (`yyyy-MM-dd'T'HH:mm`)  
4. `rental_end` – data i godzina zakończenia wypożyczenia (`yyyy-MM-dd'T'HH:mm`)  
5. `price` – cena wypożyczenia  
6. `status` – status wypożyczenia (`Completed`, `Ongoing`, `Cancelled`)  

---

### datasource4 – dane dotyczące samochodów (cars)

Dane mają format CSV, pliki posiadają nagłówki.

Pola w pliku:

0. `car_id` – unikalny identyfikator samochodu (np. `CAR0001`)  
1. `make` – marka samochodu  
2. `model` – model samochodu  
3. `year` – rok produkcji  
4. `features` – lista cech samochodu, rozdzielana średnikiem (np. `GPS;Bluetooth;Sunroof`)  
5. `category` – kategoria samochodu (`Sedan`, `SUV`, `Hatchback`, `Convertible`, `Pickup`, `Van`)  
