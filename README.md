# Patika_PostgreSQL_odev8
## [Patika.dev](www.patika.dev)

### 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
`CREATE TABLE employee (` <br>
`	id SERIAL PRIMARY KEY,` <br>
`	name VARCHAR(50) NOT NULL,` <br>
`	birthday DATE,` <br>
`	email VARCHAR(100) `	
`)`
### 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
`insert into employee (id, name, birthday, email) ` <br>
`              values (1, 'Lian', '4/16/1982', 'lhartop0@paypal.com')`<br>
`                 ... ;`

### 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
`UPDATE employee` <br>
`SET name = 'LotfiZadeh' `<br>
`WHERE name = 'Nedi'` <br>
` ..................... ;`
### 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
`DELETE FROM employee` <br>
`WHERE id = 5 `<br>
'............. ;`
