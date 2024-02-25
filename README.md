# sqlodev10
sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

1-)city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
select  country, city from city LEFT JOIN country ON country.country_id = city.country_id;
2-)customer tablosu ile payment tablosunda bulunan  payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
select first_name, last_name from  customer RIGHT JOIN payment ON customer.payment_id = payment.payment_id;
3-)customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.
select  first_name, last_name from customer FULL OUTHER JOIN rental ON customer.rental_id= rental.rental_id;
