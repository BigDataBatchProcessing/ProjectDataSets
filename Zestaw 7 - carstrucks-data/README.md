# Zestaw 7 – carstrucks-data

Pochodzenie danych to `https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/`

Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – informacje na temat sprzedawanych samochodów (1)

Dane mają format `CSV` (separatorem jest znak `^`), pliki nie posiadają nagłówka.

Pola w pliku:

0. `price`
1. `year`
2. `manufacturer`
3. `model`
4. `condition`
5. `cylinders`
6. `fuel`
7. `odometer`
8. `title_status`
9. `transmission`
10. `VIN`
11. `drive`
12. `size`
13. `type`
14. `paint_color`
15. `image_url`
16. `posting_date`
17. `geo_id` – identyfikator regionu

### `datasource4` – informacje na temat regionów geograficznych, w ramach których dokonywano sprzedaży (4)

Dane mają format `CSV` (separatorem jest znak `^`), pliki nie posiadają nagłówka.

Pola w pliku:

0. `id` - identyfikator regionu
1. `region` – nazwa regionu
2. `region_url` – url regionu
3. `county` – powiat (hrabstwo)
4. `state` – symbol stanu