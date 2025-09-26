# Zestaw 19 - stations-weather

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)  
Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – pomiary pogodowe (measurements)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `measurement_id` – unikalny identyfikator pomiaru (UUID)  
1. `station_id` – identyfikator stacji pogodowej (odniesienie do słownika stacji)  
2. `measurement_date` – data i godzina pomiaru (`yyyy-MM-dd'T'HH:mm`)  
   - losowa w ciągu ostatnich 5 lat, godziny co pełną godzinę  
3. `temperature_c` – temperatura w stopniach Celsjusza (-25..38)  
4. `humidity_pct` – wilgotność powietrza w procentach (20–100)  
5. `wind_speed_kmh` – prędkość wiatru w km/h (0–100)  
6. `precipitation_mm` – opad w mm (0–50)  
7. `condition` – warunki pogodowe (`Sunny`, `Rainy`, `Cloudy`, `Snowy`, `Stormy`, `Foggy`)  

---

### `datasource4` – stacje pogodowe (stations)

Dane mają format CSV, plik posiada nagłówek.  

Pola w pliku:

0. `station_id` – unikalny identyfikator stacji (UUID)  
1. `station_name` – nazwa stacji (miasto–ulica)  
2. `region` – województwo (`Mazowieckie`, `Śląskie`, `Małopolskie`, `Dolnośląskie`, `Wielkopolskie`, `Pomorskie`, `Lubelskie`, `Podkarpackie`, `Łódzkie`, `Kujawsko-Pomorskie`)  
3. `latitude` – szerokość geograficzna (49–55 N)  
4. `longitude` – długość geograficzna (14–24 E)  
