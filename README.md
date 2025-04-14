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

**Za instalaciju i učitavanje paketa potrebnih za rad na radionici preuzmite sljedeće skripte**
Paketi_instalacija.R - svi potrebni paketi koje ćemo trebati pri analizi
Paketi_ucitavanje.R - naredbe za učitavanje instaliranih paketa prije početka rada

Paket je skup funkcija koji su grupirani zajedno radi lakšeg korištenja. Primjerice paket „plotly” sadrži funkcije za izradu grafičkih prikaza u programskom jeziku R.

***Otvorite skriptu "Paketi_instalacija.R" u R Studiou, te pokrenuti naredbe "install.packages()" klikom na ctrl + enter kako bi instalirali pakete u vaš sustav.***

**PODACI**
Podaci koje ćemo obraditi na praktikumu nalaze se u komprimiranoj datoteci Zrmanja.zip, gdje ćete pronaći csv. datoteke sa vrijednostima intenziteta svjetlosti (LUX) na površini i 8 m dubine. Mjerenja su uzimana u periodu od 30.04 do 03.05.2024. godine. Senzori su mjerili u intervalu od svake minute i svakih 5 minuta.


