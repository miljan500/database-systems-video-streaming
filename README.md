## Zadatak 16 - Baza podataka VIDEO STREAMING

Potrebno je projektovati relacionu bazu podataka koja će čuvati sve informacije neophodne za rad
platforme za distribuciju video sadržaja.<br><br>
U sistemu se pamte podaci o svim sadržajima. Za svaki **sadržaj** se pamti jedinstveni identifikator, naslov,
originalni naslov, opis, godina produkcije, jezik, zemlja porekla, žanrovi, trajanje, uzrastna oznaka i status
objave. Sadržaji mogu biti _filmovi_, _serije_ i _prenos uživo_. Za **filmove** se dodatno pamte trajanje, režiser,
scenarista i eventualne nagrade. **Serije** se sastoje od sezona i epizoda, pa se za svaku sezonu i epizodu
pamte redni broj, naslov, datum objave, trajanje i opis. **Prenosi uživo** imaju planirano vreme početka i
završetka, kanal emitovanja, status prenosa i eventualnu dostupnost naknadnog gledanja.<br><br>
Korisnici platforme imaju naloge i profile. Za svaki **korisnički nalog** se pamte jedinstveni identifikator,
email, datum registracije, država, način registracije, status i preferisani jezik. Nalog može biti individualni,
porodični, studentski, promotivni ili poslovni. U okviru jednog naloga može postojati više profila, pa se za
svaki profil pamte naziv, tip profila, ograničenja sadržaja, istorija gledanja i preporuke. **Profil** može biti
standardni, dečiji, gostujući ili uređivački profil za korisnike koji kreiraju sopstvene liste i recenzije.<br><br>
Pretplate i paketi pristupa se posebno evidentiraju. Za svaki **paket** se pamte naziv, cena, valuta,
maksimalan broj uređaja, rezolucija, dostupnost preuzimanja i regioni u kojima važi. Paketi mogu biti
osnovni, standardni, premium, sportski, studentski ili promotivni. Korisnik može tokom vremena imati više
**pretplata**, uz istoriju aktivacije, pauziranja, otkazivanja i promena paketa. Plaćanja mogu biti izvršena
karticom, preko mobilnog operatera, vaučerom, bankovnim računom ili preko poslovnog partnera.<br><br>
Za svaki sadržaj se pamte licencna prava i teritorijalna ograničenja. Za svaku **licencu** se pamte nosilac
prava, period važenja, regioni pokrivanja, tip prava i ograničenja distribucije. Prava mogu biti ekskluzivna,
neekskluzivna, vremenski ograničena, prava za streaming, prava za preuzimanje ili prava za emitovanje
uživo. Jedan sadržaj može imati različite licence za različite regione, različite jezike ili različite tipove
distribucije. Takođe se beleže audio i tekstualne trake, titlovi, sinhronizacije i njihove verzije.<br><br>
Sistem vodi evidenciju o gledanju i interakciji korisnika sa sadržajem. Za svako **gledanje** se pamte profil,
sadržaj, datum i vreme početka, datum i vreme završetka, uređaj, lokacija pristupa, kvalitet reprodukcije
i procenat odgledanog sadržaja. Uređaji mogu biti telefon, tablet, računar, smart TV, set-top box ili igračka
konzola. Takođe se beleže događaji kao što su pauza, nastavak, premotavanje, prekid reprodukcije,
promena kvaliteta i prijava problema.
