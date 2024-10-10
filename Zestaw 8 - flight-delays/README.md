# Zestaw 8 – flight-delays

Pochodzenie danych to `https://www.kaggle.com/datasets/usdot/flight-delays`

Uwaga! Dane pobieramy z miejsca wskazanego w ramach Twojego kursu

## Dwa zbiory danych

### `datasource1` – informacje na temat lotów i ich opóźnień (1)

Dane mają format `CSV`, pliki nie posiadają nagłówka.

Pola w pliku:

0. `YEAR`,
1. `MONTH`,
2. `DAY`,
3. `DAY_OF_WEEK`,
4. `AIRLINE`,
5. `FLIGHT_NUMBER`,
6. `TAIL_NUMBER`,
7. `ORIGIN_AIRPORT`,
8. `DESTINATION_AIRPORT`,
9. `SCHEDULED_DEPARTURE`,
10. `DEPARTURE_TIME`,
11. `DEPARTURE_DELAY`,
12. `TAXI_OUT`,
13. `WHEELS_OFF`,
14. `SCHEDULED_TIME`,
15. `ELAPSED_TIME`,
16. `AIR_TIME`,
17. `DISTANCE`,
18. `WHEELS_ON`,
19. `TAXI_IN`,
20. `SCHEDULED_ARRIVAL`,
21. `ARRIVAL_TIME`,
22. `ARRIVAL_DELAY`,
23. `DIVERTED`,
24. `CANCELLED`,
25. `CANCELLATION_REASON`,
26. `AIR_SYSTEM_DELAY`,
27. `SECURITY_DELAY`,
28. `AIRLINE_DELAY`,
29. `LATE_AIRCRAFT_DELAY`,
30. `WEATHER_DELAY`

### `datasource4` – informacje na portów lotniczych (4)

Dane mają format `CSV`, każdy z plików posiada nagłówek.

Pola w pliku:

0. `IATA_CODE`,
1. `AIRPORT`,
2. `CITY`,
3. `STATE`,
4. `COUNTRY`,
5. `LATITUDE`,
6. `LONGITUDE`