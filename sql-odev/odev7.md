## Ödev 7

##### film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.
1. select rating, COUNT(*) from film GROUP by rating;

##### film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.
2. select replacement_cost, COUNT(*) from film GROUP by replacement_cost HAVING COUNT(*) > 50;

#####  customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir?
3. select store_id, COUNT(*) from customer group by store_id;

#####  city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.
4. select country_id, MAX(city) from city GROUP BY country_id ORDER BY MAX(city) DESC LIMIT 1;
