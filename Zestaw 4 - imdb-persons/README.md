# Zestaw 4 – imdb-persons

Pochodzenie danych to `https://www.imdb.com/interfaces/`

Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych 

### `datasource1` – informacje na temat najważniejszych osób zaangażowanych w poszczególne filmy (1)

Dane mają format `TSV`, pliki nie posiadają nagłówka.

Pola w pliku:

0. `tconst` – identyfikator filmu
1. `ordering` - numer kolejny osoby w filmie
2. `nconst` - identyfikator osoby
3. `role` - rola osoby w filmie
4. `job` - nazwa zawodu (jeśli dotyczy, w przeciwnym wypadku `\N`)
5. `characters` - nazwa postaci jaką grała osoba (jeśli dotyczy, w przeciwnym wypadku `\N`)

### `datasource4` – informacje na temat osób zaangażowanych w filmach (4)

Dane mają format `TSV`, każdy z plików posiada nagłówek.

Pola w pliku:

0. `nconst` – identyfikator osoby
1. `primaryName` – nazwa (imię i nazwisko) osoby
2. `birthYear` – rok urodzenia
3. `deathYear` – rok śmierci (`\N`, jeśli nie dotyczy)
4. `primaryProfession` – główne profesje osoby
5. `knownForTitles` – identyfikatory filmów, z których ta osoba jest znana