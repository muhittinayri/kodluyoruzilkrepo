## Ödev 11

##### actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.
* ( 
* select first_name from actor
* )
* union
* (
* select first_name from customer
* )

##### actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.
* ( 
* select first_name from actor
* )
* INTERSECT
* (
* select first_name from customer
* )

##### actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.
* ( 
* select first_name from actor
* )
* EXCEPT
* (
* select first_name from customer
* )

##### İlk 3 sorguyu tekrar eden veriler için de yapalım.
- 1
* ( 
* select first_name from actor
* )
* union all
* (
* select first_name from customer
* )

- 2
* ( 
* select first_name from actor
* )
* INTERSECT all
* (
* select first_name from customer
* )

- 3
* ( 
* select first_name from actor
* )
* EXCEPT all
* (
* select first_name from customer
* )