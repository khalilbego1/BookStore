# Book Store
ETF UNSA DRAOS project 2019/2020
Da bi projekat funkcionisao, potrebno je instalirati:
[Mongo DB](https://www.mongodb.com/try/download/community)
[NodeJS](https://nodejs.org/en/download/) 

Projekat se sastoji iz dva dijela: klijent i server. 

Potrebno je prvo pokrenuti server (može se jednostavno ostvariti pokretanjem sljedecih skripti u sljedećem redoslijedu):
1. pokrenuti bazu podataka (pokretanje skripte *1-startDB*)
2. instalirati sve potrebne library-e (pokretanje skripte *2-npm install*)
3. pokrenuti server (pokretanje skripte *3-start server*)

Ove skripte se nalaze u folderu server.

Nakon toga, potrebno je pokrenuti klijenta (kao i iznad, može se ostvariti pokretanjem skripti):
1. instalirati sve potrebne library-e (pokretanje skripte *2-npm install*)
2. pokrenuti klijenta (pokretanje skripte *3-start client*)

Baza podataka je po defaultu prazna, i sadrži dva već kreirana korisnika:
username:user
password:user

username:admin
password:admin

Funkcionalnosti:

Neregistrovani korisnik ima sljedeće funkcionalnosti:
- login/register
- pregled knjiga, detalja o knjigama i komentara
Registrovani korisnik ima sljedeće funkcionalnosti:
- kupovanje knjiga
- davanje ratinga knjigama
- komentarisanje knjiga
- pregled profila korisnika
- historija kupovine
- kreiranje liste favorita knjiga
- promjena avatara
Administrator ima sljedeće funkcionalnosti:
- Dodavanje, izmjena i brisanje knjiga iz aplikacije
- izmjena ili brisanje komentara korisnika
- mogucnost blokiranja korisnika
- promjena neprimjenjljivih korisnickih avatara
