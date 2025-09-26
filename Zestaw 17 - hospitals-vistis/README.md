# Zestaw 17 – hospital-visits

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)  
Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – wizyty pacjentów (visits)

Dane mają format CSV, pliki posiadają nagłówek.  
Każdy zestaw zawiera 10 000 wierszy, a plików jest 100.  

Pola w pliku:

0. `visit_id` – unikalny identyfikator wizyty (UUID)  
1. `hospital_id` – identyfikator szpitala (`hospital_id` ze słownika szpitali)  
2. `patient_name` – imię i nazwisko pacjenta  
3. `disease` – kod choroby (ICD-10, z biblioteki Faker)  
4. `medication` – nazwa leku  
5. `date` – data i godzina wizyty (`yyyy-MM-dd'T'HH:mm`), losowo z ostatnich 5 lat, w godzinach 8:00–18:45  
6. `age` – wiek pacjenta (0–100)  
7. `gender` – płeć pacjenta (`Male`, `Female`, `Other`)  

---

### `datasource4` – informacje o szpitalach (hospitals)

Dane mają format CSV, plik posiada nagłówek.  

Pola w pliku:

0. `hospital_id` – unikalny identyfikator szpitala (UUID)  
1. `name` – nazwa szpitala (np. *Acme Corp Hospital*)  
2. `city` – miasto  
3. `country` – kraj  
4. `type` – typ szpitala (`General`, `Specialist`, `Clinic`)  
