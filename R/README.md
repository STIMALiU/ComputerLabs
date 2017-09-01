# R i PC-Pularna p� IDA

Nedan finns information hantering av R-versioner och olika paket i PC-Pularna p� IDA.

## Olika R versioner

Det finns flera parallella versioner av R p� datorerna i PC-Pularna. De finns som egna ikoner i startmenyn. I R-Studio kan man v�lja vilken version vi vill anv�nda p� f�ljande [s�tt](https://support.rstudio.com/hc/en-us/articles/200486138-Using-Different-Versions-of-R). Det g�r att en uppdatering kan g�ras utan att det blir problem f�r de andra l�rarna.

Som default anv�nds den senaste versionen av R i R-Studio.

R-Studio uppdateras n�r en ny version kommer. 

## R-paket
Det finns ett antal olika R paket som anv�nds p� olika kurser. Oleg Sysoev har ett Google Spreedsheet d�r respektive l�rare anger vilka R-paket som anv�nds i respektive kurs. 

F�r att installera de R-paket som anv�nds i olika kurser har ett mindre R paket tagits fram f�r att f�renkla f�r l�rare och studenter. 

F�r att installera paketet ```stimaRpackages``` k�r f�ljande kod:
```
install.packages("devtools") # If not installed
devtools::install_github("STIMALiU/ComputerLabs", subdir = "RPackage")
```



## Tentamina

Vid datortentor anger l�raren vilken R-version som ska anv�ndas.

## F�r TUS
F�r att installera samtliga paket som beh�vs k�rs [f�ljande](https://raw.githubusercontent.com/STIMALiU/ComputerLabs/master/R/install_all_packages.R) skriptfil i R.
F�r att testa om pakten g�r att ladda in i en R-session, �ppna R/RStudio och k�r [f�ljande](https://raw.githubusercontent.com/STIMALiU/ComputerLabs/master/R/check_R_packages.R) skriptfil. 

