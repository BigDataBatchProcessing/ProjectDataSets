# Zestaw 22 – shops-reviews

### datasource1 – dane dotyczące recenzji klientów (reviews)

Dane mają format CSV, pliki posiadają nagłówki.

Pola w pliku:

0. `review_id` – unikalny identyfikator recenzji (UUID)  
1. `shop_id` – identyfikator sklepu powiązanego z recenzją  
2. `user_id` – unikalny identyfikator użytkownika (np. `USER0000001`)  
3. `review_date` – data i godzina recenzji (`yyyy-MM-dd'T'HH:mm`)  
4. `rating` – ocena w skali 1–5  
5. `comment` – treść komentarza  

---

### datasource4 – dane dotyczące sklepów (shops)

Dane mają format CSV, pliki posiadają nagłówki.

Pola w pliku:

0. `shop_id` – unikalny identyfikator sklepu (np. `SHOP0001`)  
1. `shop_name` – nazwa sklepu  
2. `category` – kategoria sklepu (np. `Electronics`, `Books`, `Clothing`)  
3. `region` – region sklepu (`North`, `South`, `East`, `West`, `Central`)  
4. `products` – lista produktów w sklepie, rozdzielana średnikiem
