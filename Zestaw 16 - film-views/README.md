# Zestaw 16 – film-views

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)  
Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – logi odsłon filmów (views)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `view_id` – unikalny identyfikator odsłony (UUID)  
1. `film_id` – identyfikator filmu (`film_id` ze zbioru filmów)  
2. `user_id` – identyfikator użytkownika w formacie `USERxxxxxxx`  
3. `start_time` – czas rozpoczęcia oglądania (`yyyy-MM-dd'T'HH:mm`)  
4. `duration_seconds` – czas oglądania w sekundach  
5. `watch_percentage` – procent obejrzanego filmu (0–100)  
6. `platform` – platforma oglądania (`StreamOne`, `BingeNow`, `WatchHub`, `PlayZone`)  
7. `device` – urządzenie oglądania (`Mobile`, `Tablet`, `SmartTV`, `Desktop`)  
8. `country` – kraj, w którym oglądano film  
9. `rating` – ocena wystawiona przez użytkownika (1–5) lub puste pole, jeśli brak oceny  

### `datasource4` – informacje o filmach (films)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `film_id` – identyfikator filmu (np. `FILM0001`)  
1. `title` – tytuł filmu  
2. `director` – imię i nazwisko reżysera  
3. `year` – rok produkcji (1980–bieżący rok + 1)  
4. `genre` – gatunek filmu (`Drama`, `Comedy`, `Action`, `Thriller`, `Horror`, `Documentary`, `Romance`, `Sci-Fi`, `Fantasy`, `Animation`)  
5. `duration_min` – czas trwania filmu w minutach (80–180)  
6. `country` – kraj produkcji  
7. `language` – język filmu (`en`, `pl`, `es`, `fr`, `de`, `it`, `ja`, `zh`)  
