# Git Bash Tutorial

## Git op pc clonen (moet maar 1 keer gebeuren)

- Cre�er een map op je pc **Integratieproject1**

- Open de nieuw gemaakte map

- Rechtermuisklik in de map en kies **Git Bash Here**

- typ **git clone https://github.com/SuikerVader/Integratieproject1.git**

- Het project staat nu op je pc!

## Status van je lokale project bekijken

- **git status**

## Up to date project van Github naar pc zetten

- **git pull origin master**

## Aanpassing naar Github pushen

- Eerst pullen van Github om up to date project te hebben -> **git pull origin master**

- Bekijken van bestanden die je hebt aangepast -> **git status**

- **git add .** -> Dit is om alle gewijzigde bestanden klaar te zetten om te pushen

- **git commit -m "<message to specify what yoy have changed>"** -> Dit is om te bevestigen

- **git push origin master**