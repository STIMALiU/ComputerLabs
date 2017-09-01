# R p� Stima, IDA, Link�pings Universitet

Nedan finns information hantering av R-versioner och olika paket i PC-Pularna p� IDA.

## Olika R versioner i PC-Pularna

Det finns flera parallella versioner av R p� datorerna i PC-Pularna. De finns som egna ikoner i startmenyn. I R-Studio kan man v�lja vilken version vi vill anv�nda p� f�ljande [s�tt](https://support.rstudio.com/hc/en-us/articles/200486138-Using-Different-Versions-of-R). Det g�r att en uppdatering kan g�ras utan att det blir problem f�r de andra l�rarna.

Som default anv�nds den senaste versionen av R i R-Studio.

R-Studio uppdateras n�r en ny version kommer. 


## R-paket i olika kurser

Det finns ett antal olika R paket som anv�nds p� olika kurser. Oleg Sysoev har ett Google Spreedsheet d�r respektive l�rare anger vilka R-paket som anv�nds i respektive kurs. 

F�r att installera de R-paket som anv�nds i olika kurser har ett mindre R paket tagits fram f�r att f�renkla f�r l�rare och studenter. 

F�r att installera paketet ```stimaRpackages``` k�r f�ljande kod:
```
> install.packages("devtools") # If not installed
> devtools::install_github("STIMALiU/ComputerLabs", subdir = "RPackage")
```

F�r att installera samtliga R paket som anv�nds vid Stima, k�r:
```
> stimaRpackages::install_stima_packages()
```

Det �r ocks� m�jligt att installera paketen som beh�vs f�r en enskild kurs. De kurser som anv�nder R plockas fram med
```
> stimaRpackages::get_stima_r_courses()
[1] "732A98 Oleg Sysoev"         "732A94 Krzysztof Bartoszek" "732G17 Krzysztof Bartoszek"
[4] "732A90 Krzysztof Bartoszek" "732G31 Isak Hietala"        "732G30 Isak Hietala"       
[7] "732G12 Isak Hietala"        "732G38 Isak Hietala"        "732G39 Isak Hietala" 
```

F�r att installer paketen som kr�vs f�r en given kurs �r det bara att k�ra (exempelvis):
```
> stimaRpackages::install_stima_packages(course = "732G30 Isak Hietala")
```

## Tentamina

Vid datortentor anger l�raren vilken R-version som ska anv�ndas.

## F�r TUS (installera alla R-paket)
F�r att installera samtliga paket fr�n bash, k�r:
```
bash R/bash/install_all_packages.sh
```