# shahryars-git-research

![Alternativ text för bild](https://i.chzbgr.com/full/4950563328/h94EA3F61/hipster-internet-husband)

## Kommandon jag har lärt mig under undervisningarna

- `pwd`: Förkortning för **print working directory**, låter dig veta var i terminalen du befinner dig.
- `ls`: Står för **list source**, låter dig veta vad innehållet är i en mapp.
- `cd`: Står för **change directory**, du skriver det följt av namnet på den önskade mappen du vill öppna.
- `mkdir`: Kort för **make directory**, med detta kommando skapar du en ny directory, vare sig det är en mapp, fil, osv.
- `mv`: Detta kommando är en förkortning för ordet **move** och kommandot flyttar en fil från a till b. Mitt minne är lite suddigt vad gäller om vi gick igenom detta under en av föreläsningarna eller inte.

- `clear`: Detta kommando rensar det som har skrivits i terminalen och loopar tillbaka till början.

## Git-kommandon som jag har lärt mig under undervisningarna.

- `git init`: Förkortning för engelskans **initialize**, detta kommando skapar en ny git repository från start.

- `git clone`: Detta kommando gör att användaren kan "klona" en github repository in i VSCode via terminalen så att man kan jobba på den där.

- `git commit`: Skapar ny commit, alltså en ny version, för repositoryn.

- `git status`: Som namnet föreslårommandot används kommandot för att inspektera statusen av repositoryn, exempelvis ifall den har commitats/behöver commitas eller inte.

- `git branch`: Kommandot i sig själv visar användaren de branches de har, dylikt pwd som gör sammma med datorns innehåll. Kategoriserar arbetet på sätt och vis.

    - `git branch branchname`: När man lägger till branchname bredvid det existerande kommandot så skapar man en ny branch. Bra ifall man är osäker på ifall man vill experimentera med en kod utan att löpa risken att förstöra ens framsteg. 

    - `git switch branchname`: Detta kommando låter användaren växla mellan branches.

- `git fetch`: Hämtar data från ett utomstående repository in till ens lokala repository.

    - `git pull`: Inte bara gör pull-kommandot samma sak som fetch gör, utan pull kopierar även ändringar från ett utomstående repository in i det lokala.

    - `git push`: Gör motsatsen till de ovanstående då push-kommandot används till att ladda upp innehållet i ens lokala repository till ett utomstående.

- `git merge`: Som kommandots namn föeslår, sammanfogar man en branch till huvudbranchen.

## Kommandon jag har lärt mig på egen hand/andra källor

- `git config`: Låter dig konfiguera saker som namn, mejladresser, osv. in till Git. Medan jag installerade Git/VSCode helgen innan vår första föreläsning så lärde jag mig detta kommando via en tutorial på YouTube. (https://www.youtube.com/watch?v=B4qsvQ5IqWk&pp=ygUQZ2l0IGhvbWVicmV3IG1hYw%3D%3D)

    - ...` --global user.name "..."`: Användaren kan med hjälp av detta kommando skapa ett användarnamn för sig själv för att associera till Git.
    
    - ...` --global user.email "..."`: Samma funktion, fast för ens e-postadress.

    - ... `get ...`: Att skriva get framför antingen user.name eller user.email gör att terminalen hämtar användarens användarnamn respektive hens e-postadress.