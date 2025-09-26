# Zestaw 18 – esports-heroes

Dane sztuczne wygenerowane z użyciem biblioteki DataFaker (https://www.datafaker.net/)  
Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – dane rozgrywek (matches)

Dane mają format CSV, pliki posiadają nagłówek.  

Pola w pliku:

0. `event_id` – identyfikator wydarzenia (UUID, powtarza się dla meczów w ramach tego samego eventu)  
1. `player_id` – identyfikator gracza (odniesienie do słownika graczy)  
2. `event_date` – data i godzina rozegrania meczu (`yyyy-MM-dd'T'HH:mm`)  
   - spójna w ramach `event_id`  
   - godziny w zakresie 12:00–21:45 (kwadranse)  
3. `heroes_used` – bohaterowie użyci przez gracza w meczu (lista rozdzielona `;`, w cudzysłowie `"..."`)  
   - źródła: Superhero, Witcher, Zelda, Overwatch, League of Legends  
4. `kills` – liczba zabójstw (0–19)  
5. `deaths` – liczba śmierci (0–19)  
6. `assists` – liczba asyst (0–19)  
7. `match_result` – wynik meczu (`Win`, `Lose`, `Draw`)  

---

### `datasource4` – słownik graczy (players)

Dane mają format CSV, plik posiada nagłówek.  

Pola w pliku:

0. `player_id` – identyfikator gracza (UUID)  
1. `nickname` – pseudonim gracza (Faker – esports player)  
2. `region` – region rozgrywek (`NA`, `EU`, `ASIA`, `SA`, `OCE`)  
3. `team` – drużyna (losowa nazwa zespołu)  
