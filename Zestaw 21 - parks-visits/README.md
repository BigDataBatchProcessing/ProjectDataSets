# Zestaw 21 – parks-visits

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)

## Dwa zbiory danych

### `datasource1` – wizyty w parkach (visits)

Dane mają format CSV, pliki posiadają nagłówek.

Pola w pliku:

0. `visit_id` – unikalny identyfikator wizyty (UUID)  
1. `park_id` – identyfikator parku (odniesienie do słownika parków)  
2. `visitor_id` – unikalny identyfikator odwiedzającego (np. VISITOR0000001)  
3. `entry_time` – czas wejścia (`yyyy-MM-dd'T'HH:mm`)  
4. `exit_time` – czas wyjścia (`yyyy-MM-dd'T'HH:mm`)  
5. `group_size` – liczba osób w grupie  
6. `activity` – aktywność podczas wizyty (np. Hiking, Picnic, Camping, Birdwatching)  

---

### `datasource4` – dane na temat parków (parks)

Dane mają format CSV, pliki posiadają nagłówek.

Pola w pliku:

0. `park_id` – unikalny identyfikator parku (np. PARK0001)  
1. `name` – nazwa parku  
2. `region` – region geograficzny (North, South, East, West, Central)  
3. `facilities` – dostępne udogodnienia (lista rozdzielana średnikiem, np. Playground;Picnic Area)  
4. `attractions` – atrakcje w parku (lista rozdzielana średnikiem, np. Lake;Monument)  
5. `nature_types` – typy przyrody (lista rozdzielana średnikiem, np. Forest;River)  
6. `established_year` – rok utworzenia parku  
