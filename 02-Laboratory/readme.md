# Laboratuvar Dersleri

Aşağıdaki programların bilgisayara kurulması tavsiye edilir.
* Dersler sırasında PostgreSQL kullanılacaktır.
```sh
ondergormez@ondergormez:~/Desktop$ sudo apt install postgresql postgresql-contrib
```
Detaylar için  [How To Install and Use PostgreSQL on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04) sayfasına bakabilirsiniz.
* Dersler sırasında PgAdmin yönetim paneli kullanılacaktır. Aşağıdaki web adresinden erişilebilir.  
```sh
http://127.0.0.1/pgadmin4
```
Detaylar için  [PgAdmin Download](https://www.pgadmin.org/download/pgadmin-4-apt/) sayfasına bakabilirsiniz.  

* Database kullanıcı ismi aşağıdaki şekilde güncellenmelidir.  
```sh
ondergormez@ondergormez:~/Desktop$ sudo -u postgres psql
psql (12.8 (Ubuntu 12.8-0ubuntu0.20.04.1))
Type "help" for help.

postgres=$ ALTER USER postgres WITH PASSWORD 'postgres';
ALTER ROLE
postgres=$
```
* Daha sonra [PgAdmin Web UI](http://127.0.0.1/pgadmin4) üzerinden yeni bir server oluşturulabilir.  

__Not: Lab dersinin 3. haftasında ilk quiz yapılacaktır.__

İçerik ile ilgili olarak;
- [ ] : Tekrar edilmedi anlamına gelmektedir.
- [x] : Tekrar edildi anlamına gelmektedir.

## İçerik
- [x] [1. Hafta - 7 Ekim 2021 Perşembe](01_07_10_2021.md)
- [ ] [2. Hafta - 14 Ekim 2021 Perşembe](02_14_10_2021.md)