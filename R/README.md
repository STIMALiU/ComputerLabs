# R i PC-Pularna p� IDA

Nedan finns information hantering av R-versioner och olika paket i PC-Pularna p� IDA.

## Olika R versioner

Det finns flera parallella versioner av R p� datorerna i PC-Pularna. De finns som egna ikoner i startmenyn. I R-Studio kan man v�lja vilken version vi vill anv�nda p� f�ljande [s�tt](https://support.rstudio.com/hc/en-us/articles/200486138-Using-Different-Versions-of-R). Det g�r att en uppdatering kan g�ras utan att det blir problem f�r de andra l�rarna.

Som default anv�nds den senaste versionen av R i R-Studio.

R-Studio uppdateras n�r en ny version kommer. 

## R-paket
De R-paket som finns f�rinstallerade p� alla PC-Pular fr�n CRAN finns [h�r](https://github.com/STIMALiU/ComputerLabs/blob/master/R/Packages/cran_packages.csv) och de paket som finns installerade fr�n github finns [h�r](https://github.com/STIMALiU/ComputerLabs/blob/master/R/Packages/github_packages.csv).

Under 'user' i csv-filerna finns de l�rare som anv�nder paketen som TUS kan kontakta om det �r n�gra problem vid uppdateringar.

Studenter kan alltid sj�lva installera paket om de vill - dock ej under tentor.

F�r att se versionerna f�r de paket som finns installerade f�r en given R-version:
```
installed.packages()
```

## Tentamina

Vid datortentor anger l�raren vilken R-version som ska anv�ndas.

## F�r TUS
F�r att installera samtliga paket som beh�vs k�rs [f�ljande](https://github.com/STIMALiU/ComputerLabs/blob/master/R/install_all_packages.R) skriptfil i R.
F�r att testa om pakten g�r att ladda in i en R-session, �ppna R/RStudio och k�r [f�ljande](https://raw.githubusercontent.com/STIMALiU/ComputerLabs/master/R/check_R_packages.R) skriptfil. 

