# SQL_Traine1

#Query 1
select * from customers;
<img width="766" alt="image" src="https://user-images.githubusercontent.com/78079556/236471841-cd0ee5d9-96e8-40ec-aff2-5d6d87620388.png">
keterangan: Memunculkan seluruh data yang ada pada table customers.

#Query 2
SELECT creditLimit FROM customers ORDER BY creditLimit DESC;
<img width="449" alt="image" src="https://user-images.githubusercontent.com/78079556/236475817-39dbc1e3-a7c5-4529-b08b-1f3e08682914.png">
keterangan: Dari table customers untuk Memunculkan data credit limit customer dari terbawah / Menurun.

#Query 3
SELECT customerName,phone,addressLine1,city,country FROM customers WHERE country = 'USA' ORDER BY customerName;
<img width="468" alt="image" src="https://user-images.githubusercontent.com/78079556/236474448-c6c26718-90b9-4abb-907b-c75e7f0c8509.png">
keterangan: Dari table customers untuk memunculkan data kolom customerName, phone, addressLine1,City,country dengan kolom country yang berisikan USA.

#Query4
SELECT customerName, phone, addressLine2, city, country, creditLimit FROM customers WHERE creditLimit > 90000 AND country = 'USA' ORDER BY creditLimit DESC;
<img width="677" alt="image" src="https://user-images.githubusercontent.com/78079556/236477885-5435c5fe-473e-453a-9ebe-ffbfd4ca0835.png">
keterangan: Dari table customers untuk memunculkan data kolom customerName, phone, addressLine2,City,country, creditLimit dengan nilai creditlimit diatas 90000,
county = USA dan dari kolom creditlimt dengan data terbesar.
