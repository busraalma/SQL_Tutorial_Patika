1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
	id int,
	name varchar(50),
	birthday date,
	email varchar(100)
);
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, name, birthday, email) values (1, 'Nata Clemmen', '1984-09-07', 'nclemmen0@rakuten.co.jp');
insert into employee (id, name, birthday, email) values (2, 'Penelopa Whimpenny', '1978-07-13', 'pwhimpenny1@chron.com');
insert into employee (id, name, birthday, email) values (3, 'Fredek Kinrade', '1980-09-20', 'fkinrade2@blogs.com');
insert into employee (id, name, birthday, email) values (4, 'Ermina Morcomb', '1955-09-01', 'emorcomb3@apache.org');
insert into employee (id, name, birthday, email) values (5, 'Roobbie Isoldi', '1951-06-03', 'risoldi4@barnesandnoble.com');
insert into employee (id, name, birthday, email) values (6, 'Elaina Phoenix', '1975-06-07', 'ephoenix5@huffingtonpost.com');
insert into employee (id, name, birthday, email) values (7, 'Christan Langthorne', '1994-04-12', 'clangthorne6@reverbnation.com');
insert into employee (id, name, birthday, email) values (8, 'Asa Giacomucci', '1978-09-16', 'agiacomucci7@ibm.com');
insert into employee (id, name, birthday, email) values (9, 'Annie Steed', '1997-08-02', 'asteed8@businessinsider.com');
insert into employee (id, name, birthday, email) values (10, 'Lynett Gouthier', '1966-12-24', 'lgouthier9@time.com');
insert into employee (id, name, birthday, email) values (11, 'Harley MacDonald', '1951-01-27', 'hmacdonalda@mtv.com');
insert into employee (id, name, birthday, email) values (12, 'Dorotea Vasyutin', '1970-10-27', 'dvasyutinb@wordpress.org');
insert into employee (id, name, birthday, email) values (13, 'Marcello Dunbar', '1951-10-24', 'mdunbarc@wired.com');
insert into employee (id, name, birthday, email) values (14, 'Katlin Slaughter', '1995-10-22', 'kslaughterd@ning.com');
insert into employee (id, name, birthday, email) values (15, 'Gaylor Metzing', '1958-05-16', 'gmetzinge@amazonaws.com');
insert into employee (id, name, birthday, email) values (16, 'Mac Sivier', '1958-06-30', 'msivierf@youtube.com');
insert into employee (id, name, birthday, email) values (17, 'Terrell Madill', '1977-04-28', 'tmadillg@sphinn.com');
insert into employee (id, name, birthday, email) values (18, 'Krishnah Jurick', '1950-06-15', 'kjurickh@rediff.com');
insert into employee (id, name, birthday, email) values (19, 'Egon Habbershon', '1991-10-20', 'ehabbershoni@studiopress.com');
insert into employee (id, name, birthday, email) values (20, 'Felicio Goring', '2004-07-17', 'fgoringj@unicef.org');
insert into employee (id, name, birthday, email) values (21, 'Jamison Norres', '1977-01-14', 'jnorresk@reverbnation.com');
insert into employee (id, name, birthday, email) values (22, 'Ketti Gwynn', '1965-06-05', 'kgwynnl@weibo.com');
insert into employee (id, name, birthday, email) values (23, 'Craig Wyche', '2003-12-12', 'cwychem@ca.gov');
insert into employee (id, name, birthday, email) values (24, 'Cathlene Edgehill', '1978-10-09', 'cedgehilln@fotki.com');
insert into employee (id, name, birthday, email) values (25, 'Sybille Kleen', '1962-04-22', 'skleeno@tripadvisor.com');
insert into employee (id, name, birthday, email) values (26, 'Ambrosi Willshere', '2000-06-27', 'awillsherep@usda.gov');
insert into employee (id, name, birthday, email) values (27, 'Anatollo Riddel', '1979-11-10', 'ariddelq@php.net');
insert into employee (id, name, birthday, email) values (28, 'Erin Mixhel', '1959-11-16', 'emixhelr@ehow.com');
insert into employee (id, name, birthday, email) values (29, 'Raul McSwan', '1968-12-05', 'rmcswans@google.fr');
insert into employee (id, name, birthday, email) values (30, 'Laryssa Wildbore', '1979-05-21', 'lwildboret@nhs.uk');
insert into employee (id, name, birthday, email) values (31, 'Dilan Sill', '2002-07-24', 'dsillu@shinystat.com');
insert into employee (id, name, birthday, email) values (32, 'Wendy Gook', '1952-08-01', 'wgookv@twitter.com');
insert into employee (id, name, birthday, email) values (33, 'Hakeem Lording', '2002-10-09', 'hlordingw@engadget.com');
insert into employee (id, name, birthday, email) values (34, 'Latisha Joe', '1964-06-09', 'ljoex@deliciousdays.com');
insert into employee (id, name, birthday, email) values (35, 'Antonina Viggars', '1969-03-13', 'aviggarsy@google.fr');
insert into employee (id, name, birthday, email) values (36, 'Gil Jenkerson', '1994-03-25', 'gjenkersonz@clickbank.net');
insert into employee (id, name, birthday, email) values (37, 'Kissie Jillings', '1987-12-01', 'kjillings10@blogger.com');
insert into employee (id, name, birthday, email) values (38, 'Christiana Tamlett', '1968-01-01', 'ctamlett11@cafepress.com');
insert into employee (id, name, birthday, email) values (39, 'Cristina Jelk', '1956-08-02', 'cjelk12@ning.com');
insert into employee (id, name, birthday, email) values (40, 'Rebeca Shorbrook', '1953-09-04', 'rshorbrook13@yale.edu');
insert into employee (id, name, birthday, email) values (41, 'Gennifer Sudy', '1971-11-26', 'gsudy14@dmoz.org');
insert into employee (id, name, birthday, email) values (42, 'Annabella Aslam', '1971-06-21', 'aaslam15@google.de');
insert into employee (id, name, birthday, email) values (43, 'Cassondra Itskovitz', '1995-08-06', 'citskovitz16@vk.com');
insert into employee (id, name, birthday, email) values (44, 'Stirling Clerke', '1992-09-06', 'sclerke17@pbs.org');
insert into employee (id, name, birthday, email) values (45, 'Linea Jonke', '1985-08-03', 'ljonke18@youku.com');
insert into employee (id, name, birthday, email) values (46, 'Dawn Kasparski', '1961-07-17', 'dkasparski19@biglobe.ne.jp');
insert into employee (id, name, birthday, email) values (47, 'Paten Etienne', '1951-05-09', 'petienne1a@acquirethisname.com');
insert into employee (id, name, birthday, email) values (48, 'Inesita Fontes', '1968-07-15', 'ifontes1b@livejournal.com');
insert into employee (id, name, birthday, email) values (49, 'Bart Gaine', '1966-04-06', 'bgaine1c@theguardian.com');
insert into employee (id, name, birthday, email) values (50, 'Eden Paschek', '1951-09-14', 'epaschek1d@prweb.com');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'Ted Mosby',
	birthday = '1980-01-01',
	email = 'ted@mosby.com'
WHERE id = 1;

UPDATE employee
SET name = 'Penelope Whimpenny'
WHERE name = 'Penelopa Whimpenny';

UPDATE employee
SET email = 'annie@steed.com'
WHERE id = '9';

UPDATE employee
SET birthday = '2000-01-01'
WHERE birthday < '2000-01-01';

UPDATE employee
SET email = 'employee@test.org'
WHERE email LIKE '%.org';
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee WHERE email LIKE '%.org';

DELETE FROM employee WHERE birthday = '2000-01-01';

DELETE FROM employee WHERE name LIKE 'Dilan%';

DELETE FROM employee WHERE id = 33;

DELETE FROM employee WHERE id > 25;
```
