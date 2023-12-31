# PHP een introductie

## Inleiding

We gaan met PHP aan de slag. PHP is een programmeertaal waarmee je dynamische websites kunt maken. Je kunt met PHP data opslaan, gebruikers laten inloggen, registreren en uitloggen. Je kunt met PHP data uit een database halen en tonen op je website. Je kunt met PHP data in een database opslaan. Je kunt met PHP data controleren en je kunt met PHP data verwijderen.

Deze handleiding goed lezen en de opdrachten maken. Zijn er onduidelijkheden dan vraag je aan je buurman/vrouw of die het antwoord heeft. Lukt het niet, zoek op internet naar de oplossing of gebruik ChatGPT. Lukt het dan nog steeds niet. Vraag gerust je docent.

Dit cursus is verdeeld over meerdere blokken

## Planning

|Blok| PHP | SQL |ERD|
|---|---|---|---|
|Blok 3| Basis PHP | SELECT, SELECT WHERE | 1 tabel
|Blok 4| Basis PHP | SELECT, INSERT, JOIN | 1-op-1 relatie|
|Blok 7| Basis PHP | DELETE, UPDATE       | 1-op-veel relatie|
|Blok 8| Basis PHP | CRUD, JOINS          | veel-op-veel relatie|

Veel plezier met webdevelopment in PHP.

# Inhoud

## [Blok 3](./blok3.md#Blok-3)  

1. [Installaties](./blok3.md#Installaties)
   1. [Visual Studio Code](./blok3.md#Visual-Studio-Code)
   2. [Docker](./blok3.md#Docker)
   3. [Git](./blok3.md#Git)
   4. [Terminal](./blok3.md#Terminal)
   5. [Github](./blok3.md#Github)
2. [Technieken](./blok3.md#Technieken)
   1. [PHP](./blok3.md#PHP)
   2. [SQL](./blok3.md#SQL)
   3. [PHP vs. HTML (CSS)](./blok3.md#PHP-vs-HTML-CSS)
   4. [URL](./blok3.md#URL)
   5. [Webserver](./blok3.md#Webserver)
3. [Voordat je verder gaat](./blok3.md#Voordat-je-verder-gaat)
   1. [Een projecten map](./blok3.md#Een-projecten-map)
4. [Een project beginnen](./blok3.md#Een-project-beginnen)
   1. [Project Forken](./blok3.md#Project-Forken)
   2. [Project Klonen](./blok3.md#Project-Klonen)
   3. [Aan de slag met het project](./blok3.md#Aan-de-slag-met-het-project)
   4. [Servers starten](./blok3.md#Servers-starten)
   5. [Je site bekijken](./blok3.md#Je-site-bekijken)
   6. [Database beheer](./blok3.md#Database-beheer)
5. [Coderen](./blok3.md#Coderen)
   1. [index.php](./blok3.md#indexphp)
   2. [PHP Tags](./blok3.md#PHP-Tags)
   3. [Project bekijken](./blok3.md#Project-bekijken)
   4. [HTML](./blok3.md#HTML)
   5. [Variabelen](./blok3.md#Variabelen)
   6. [Opnieuw declareren](./blok3.md#Opnieuw-declareren)
   7. [Broncode](./blok3.md#Broncode)
   8. [HTML in PHP](./blok3.md#HTML-in-PHP)
6. [PHP](./blok3.md#PHP)
   1. [Condities](./blok3.md#Condities)
   2. [Conditionele operatoren](./blok3.md#Conditionele-operatoren)
   3. [Arrays](./blok3.md#Arrays)
   4. [Associatieve arrays](./blok3.md#Associatieve-arrays)
   5. [Foreach Loops](./blok3.md#Foreach-Loops)
   6. [Foreach met enkel toegang tot de Waarde (value)](./blok3.md#Foreach-met-enkel-toegang-tot-de-Waarde-value) 
   7. [Foreach loop met toegang tot Sleutel (key) en Waarde (value)](./blok3.md#Foreach-loop-met-toegang-tot-Sleutel-key-en-Waarde-value)
7. [Request Response Cycle](./blok3.md#Request-Response-Cycle)
   1. [Requests](./blok3.md#Requests)
   2. [GET request](./blok3.md#GET-request)
   3. [POST request](./blok3.md#POST-request)
   4. [Superglobal arrays](./blok3.md#Superglobal-arrays)
8. [Ingebouwde PHP functies](./blok3.md#Ingebouwde-PHP-functies)
9. [Werken met een Database (SQL)](./blok3.md#Werken-met-een-Database-SQL)
   1.  [Database Connectie](./blok3.md#Database-Connectie)
   2.  [Alle rijen ophalen](./blok3.md#Alle-rijen-ophalen)
   3.  [Enkele Rij ophalen](./blok3.md#Enkele-Rij-ophalen)
   4.  [Dynamische link](./blok3.md#Dynamische-link)
   5.  [Afbeeldingen Toevoegen](./blok3.md#Afbeeldingen-Toevoegen)
10. [Nieuw Project](./blok3.md#Nieuw-Project)

## [Blok 4](./blok4.md#Blok-4)

1. [Data opslaan](./blok4.md#Data-opslaan)
   1. [Formulier & POST-request](./blok4.md#Formulier--POST-request)
   2. [Data controleren](./blok4.md#Data-controleren)
   3. [Data opslaan](./blok4.md#Data-opslaan-1)
2. [Registreren](./blok4.md#Registreren)
3. [Inloggen](./blok4.md#Inloggen)
4. [Levensduur van een variabele](./blok4.md#Levensduur-van-een-variabele)
   1. [Levensduur *Normale variabele*](./blok4.md#Levensduur-Normale-variabele)
   2. [Levensduur Request arrays](./blok4.md#Levensduur-Request-arrays)
   3. [Levensduur Session array](./blok4.md#Levensduur-Session-array)
5. [Authenticatie](./blok4.md#Authenticatie)
6. [Autorisatie](./blok4.md#Autorisatie)
7. [Zoeken](./blok4.md#Zoeken)
8. [Dashboard data](./blok4.md#Dashboard-data)
   1. [Is ingelogd?](./blok4.md#Is-ingelogd)
   2. [Tijd weergeven](./blok4.md#Tijd-weergeven)
   3. [Tool data](./blok4.md#Tool-data)
9. [Meerdere tabellen](./blok4.md#Meerdere-tabellen)
10. [Herhaling](./blok4.md#Herhaling)

## [Blok 7](./blok7.md#Blok-7)

1. [SQL Injections](./blok7.md#SQL-Injections)
2. [SQL prepared statements](./blok7.md#SQL-prepared-statements)
   1. [Database Conenctie](./blok7.md#Database-Conenctie)
   2. [Prepare SQL](./blok7.md#Prepare-SQL)
   3. [Bind Params](./blok7.md#Bind-Params)
   4. [Execute](./blok7.md#Execute)
3. [Delete](./blok7.md#Delete)
4. [Update](./blok7.md#Update)




