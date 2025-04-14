# BOCE_praktikum
U ovom repozitoriju nalaze se upute za instalaciju R programskog jezika i R Studio sučelja u kojem ćemo provoditi analizu, te podaci i radne skripte.

**PRIPREMA PROGRAMA**

**1. Instalacija programskog jezika R**
https://cloud.r-project.org/
Izaberi: download R for Linux/macOS/Windows, zatim na "Install R for the first time" i zatim na Download R-4.5.0 for Linux/macOS/Windows.

**2. Instalacija R tools**
https://cran.r-project.org/bin/windows/Rtools/

**3. Instalacija sučelja R studio**
https://posit.co/download/rstudio-desktop/
Niže na stranici nalaze se opcije za različite operacijske sustave. Izaberite RTools, verzija mora biti jednaka onoj R programskog jezika, dakle 4.5.
Zatim ćete biti preusmjereni na stranicu https://cran.r-project.org/bin/windows/Rtools/rtools44/rtools.html 
Izaberete pod RTools for Windows (ili koji god operacijski sustav koristite), odete na "RTools44 installer" i biti ćete preusmjereni na instalaciju.

**PRIPREMA RADNOG OKRUŽENJA**

***Preuzmite komprimiranu datoteku "BOCE_praktikum.zip" u kojoj se nalaze radne skripte i podaci, te je spremite u direktorij: "C:/Korisnik(eng. Users)/Vaše_ime/"**

Radne skripte označene su sa .R i .Rproj.
- Paketi_instalacija.R : Radna skripta u kojoj se nalaze naredbe za instalaciju svih potrebnih paketa koje ćemo trebati za rad u R-u.
- Paketi_ucitavanje.R : Radna skripta u kojoj se nalaze naredbe za učitavanje svih instaliranih paketa prije početka rada u R-u.
*Paket je skup funkcija koji su grupirani zajedno radi lakšeg korištenja. Primjerice paket „plotly” sadrži funkcije za izradu grafičkih prikaza u programskom jeziku R.*

***Otvorite skriptu "Paketi_instalacija.R" u R Studiu, te pokrenuti naredbe "install.packages()" klikom na ctrl + enter iza svakog reda koda, kako bi instalirali pakete u vaš sustav.***

1. Otvorite R Studio.
2. File > Open File > Paketi_instalacija.R
3. Pokrenuti svaki install.packages() klikom na ctrl + enter

**PODACI**

Podaci koje ćemo obraditi na praktikumu nalaze su vrijednosti intenziteta svjetlosti (LUX) na površini (0 m) i 8 m dubine. Mjerenja su uzimana u periodu od 30.04 do 03.05.2024. godine. Senzori su mjerili u intervalu od svake minute i svakih 5 minuta.
Podaci se nalaze u .csv datotekama.

**CHECK LISTA PRIJE PRAKTIKUMA**
1. Uspješno instaliran R i R Tools.
2. Uspješno instaliran R Studio - sučelje u kojem ćemo koristiti R.
3. Uspješno preuzeta BOCE_praktikum.zip datoteka i spremljena u direktorij "C:/Korisnik(eng. Users)/Vaše_ime/"
4. Uspješno instalirani paketi putem naredbi koje se nalaze u Paketi_instalacija.R




