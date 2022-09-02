## Ödev 6

##### film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?
1. select round(avg(rental_rate), 2) from film;

##### film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?
2. select count(title) from film where title like 'C%';

##### film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?
3. select MAX(length) from film where rental_rate = 0.99;

##### film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?
4. select COUNT(DISTINCT replacement_cost) from film where length > 150;