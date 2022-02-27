# Homework 12 
**1.** **film** tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
```sql
SELECT COUNT(*) FROM film
WHERE length>
(SELECT AVG(length)FROM film);
```

**2.** **film** tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
```sql
SELECT COUNT(*) FROM film
WHERE rental_rate = 
(SELECT MAX(rental_rate) FROM film);
```
**3.** **film** tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
```sql
SELECT * FROM film
WHERE  rental_rate=
(SELECT MIN(rental_rate) FROM film)
AND replacement_cost=
(SELECT MIN(replacement_cost) FROM film);
```
**4.** payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
```sql
SELECT  customer.customer_id,first_name, last_name, (COUNT(*)) AS shopping_count FROM customer
JOIN payment ON payment.customer_id=customer.customer_id
GROUP BY customer.customer_id,first_name, last_name
ORDER BY shopping_count DESC;
```