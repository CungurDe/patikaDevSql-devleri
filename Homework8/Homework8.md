# Homework 8
**1.** **test** veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
 ```sql
 CREATE TABLE employee(
	id INTEGER,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100));
 ```
**2.** Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
 ```sql
 insert into employee (id, name, birthday, email) values (1, 'Ephrayim Shillinglaw', '1967-03-14', 'eshillinglaw0@netlog.com');
insert into employee (id, name, birthday, email) values (2, 'Gerik Gookes', '1959-12-31', 'ggookes1@seesaa.net');
insert into employee (id, name, birthday, email) values (3, 'Onfroi Sola', '1987-03-11', 'osola2@aol.com');
insert into employee (id, name, birthday, email) values (4, 'Lothario Ickovicz', '1964-02-03', null);
insert into employee (id, name, birthday, email) values (5, 'Ike Cotter', '1969-10-02', 'icotter4@w3.org');
insert into employee (id, name, birthday, email) values (6, 'Chelsae Carlick', '1993-08-15', 'ccarlick5@bigcartel.com');
insert into employee (id, name, birthday, email) values (7, 'Cordy Amdohr', '1967-10-07', 'camdohr6@ebay.com');
insert into employee (id, name, birthday, email) values (8, 'Cyb Lampkin', '1961-01-21', 'clampkin7@who.int');
insert into employee (id, name, birthday, email) values (9, 'Uriah Hullins', '1994-12-04', 'uhullins8@time.com');
insert into employee (id, name, birthday, email) values (10, 'Gabie Babalola', '1953-11-09', 'gbabalola9@phpbb.com');
insert into employee (id, name, birthday, email) values (11, 'Hastings Franchioni', '1960-10-23', 'hfranchionia@yelp.com');
insert into employee (id, name, birthday, email) values (12, 'Philomena Turneaux', '1967-09-27', 'pturneauxb@epa.gov');
insert into employee (id, name, birthday, email) values (13, 'Ekaterina Beakes', '1955-03-08', 'ebeakesc@ebay.co.uk');
insert into employee (id, name, birthday, email) values (14, 'Tomkin Mancer', '1996-10-03', 'tmancerd@twitpic.com');
insert into employee (id, name, birthday, email) values (15, 'Herminia Riceards', '1996-08-08', 'hriceardse@meetup.com');
insert into employee (id, name, birthday, email) values (16, 'Sonni Maty', '1986-04-13', 'smatyf@rediff.com');
insert into employee (id, name, birthday, email) values (17, 'Barny Fishburn', '1958-02-25', 'bfishburng@google.pl');
insert into employee (id, name, birthday, email) values (18, 'Katlin Iacobacci', '1993-11-22', 'kiacobaccih@yellowpages.com');
insert into employee (id, name, birthday, email) values (19, 'Louise Hallows', '1995-01-10', 'lhallowsi@acquirethisname.com');
insert into employee (id, name, birthday, email) values (20, 'Tom Thominga', '1987-08-20', 'tthomingaj@nps.gov');
insert into employee (id, name, birthday, email) values (21, 'Hussein Winskill', '1962-08-11', 'hwinskillk@cbsnews.com');
insert into employee (id, name, birthday, email) values (22, 'Bridie Odom', '1955-07-27', 'bodoml@google.com.hk');
insert into employee (id, name, birthday, email) values (23, 'Everett Peepall', '1957-01-03', 'epeepallm@blogs.com');
insert into employee (id, name, birthday, email) values (24, 'Jacynth Pybus', '1977-04-02', 'jpybusn@scientificamerican.com');
insert into employee (id, name, birthday, email) values (25, 'Selena Pietrusiak', '1951-03-20', 'spietrusiako@slideshare.net');
insert into employee (id, name, birthday, email) values (26, 'Sollie Wegner', '1969-08-20', 'swegnerp@squidoo.com');
insert into employee (id, name, birthday, email) values (27, 'Jany Gonzalo', '1996-03-12', 'jgonzaloq@redcross.org');
insert into employee (id, name, birthday, email) values (28, 'Jenifer Avo', '1999-12-11', 'javor@alexa.com');
insert into employee (id, name, birthday, email) values (29, 'Eadmund Yakob', '1950-12-13', 'eyakobs@woothemes.com');
insert into employee (id, name, birthday, email) values (30, 'Lonee Cockson', '1990-11-27', 'lcocksont@abc.net.au');
insert into employee (id, name, birthday, email) values (31, 'Nil Guppie', '1967-07-21', 'nguppieu@columbia.edu');
insert into employee (id, name, birthday, email) values (32, 'Jenilee McGuire', '1974-07-15', 'jmcguirev@domainmarket.com');
insert into employee (id, name, birthday, email) values (33, 'Sheryl McElhinney', '1981-02-07', 'smcelhinneyw@plala.or.jp');
insert into employee (id, name, birthday, email) values (34, 'Boycey Bilney', '1972-02-05', 'bbilneyx@paypal.com');
insert into employee (id, name, birthday, email) values (35, 'Eirena Myrkus', '1993-02-03', 'emyrkusy@moonfruit.com');
insert into employee (id, name, birthday, email) values (36, 'Ivett Duckit', '1970-11-02', 'iduckitz@artisteer.com');
insert into employee (id, name, birthday, email) values (37, 'Sandy Clowton', '1967-07-19', 'sclowton10@bing.com');
insert into employee (id, name, birthday, email) values (38, 'Gaston Searchwell', '1960-09-26', 'gsearchwell11@sitemeter.com');
insert into employee (id, name, birthday, email) values (39, 'Rosemary Brownsey', '1961-06-03', 'rbrownsey12@reuters.com');
insert into employee (id, name, birthday, email) values (40, 'Hamnet Bigland', '1968-11-05', 'hbigland13@usda.gov');
insert into employee (id, name, birthday, email) values (41, 'Derek Siely', '1966-11-20', 'dsiely14@w3.org');
insert into employee (id, name, birthday, email) values (42, 'Luella Waiting', '1983-01-24', 'lwaiting15@usda.gov');
insert into employee (id, name, birthday, email) values (43, 'Gardie Danat', '1958-12-25', 'gdanat16@columbia.edu');
insert into employee (id, name, birthday, email) values (44, 'Eileen Yeomans', '1968-03-23', 'eyeomans17@fastcompany.com');
insert into employee (id, name, birthday, email) values (45, 'Robby Methingam', '1953-12-04', 'rmethingam18@jalbum.net');
insert into employee (id, name, birthday, email) values (46, 'Felic Jutson', '1996-03-17', 'fjutson19@cbslocal.com');
insert into employee (id, name, birthday, email) values (47, 'Peggy Jolin', '1952-03-03', 'pjolin1a@foxnews.com');
insert into employee (id, name, birthday, email) values (48, 'Roderic MacGaughie', '1992-03-06', 'rmacgaughie1b@mediafire.com');
insert into employee (id, name, birthday, email) values (49, 'Cindee Consadine', '1964-12-22', 'cconsadine1c@java.com');
insert into employee (id, name, birthday, email) values (50, 'Lonna Cinnamond', '1957-05-29', 'lcinnamond1d@army.mil');
 ``` 
**3.** Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
 UPDATE employee
 SET 
	name='Joseph Conrad',
	email='conrad@joseph.com'
 WHERE id = '1';	
```
```sql
UPDATE employee
SET 
	name='Kemal Sayar',
	birthday='1945-10-25'
WHERE email LIKE 'rmac%';	
```
```sql
UPDATE employee
SET 
	birthday='1700-12-14'
WHERE name LIKE 'Peg%';	
```
```sql
UPDATE employee
SET 
	name='Ali Yaşar'
WHERE birthday='1955-07-27';	
```
```sql
UPDATE employee
SET 
    name='Mehmet Mert',
    birthday='2010-01-01',
    email= 'mehmetttt@mertttt.com' 
WHERE id='10';	
```

**4.** Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee 
WHERE id='3';
```
```sql
DELETE FROM employee 
WHERE name='Mehmet Mert';
```
```sql
DELETE FROM employee 
WHERE email='"epeepallm@blogs.com"';
```
```sql
DELETE FROM employee 
WHERE birthday='1955-07-27';
```
```sql
DELETE FROM employee 
WHERE id>'40';
```