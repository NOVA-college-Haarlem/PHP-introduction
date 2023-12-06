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

![](media/ef402d172ea9972d473464dfc9dc834d.png)


# Inhoud

## [Blok 3](./blok3.md#Blok-3)  


- [Installaties](./blok3.md#Installaties)
- [Visual Studio Code](./blok3.md#Visual-Studio-Code)
- [Docker](./blok3.md#Docker)
- [Git](./blok3.md#Git)
- [Terminal](./blok3.md#Terminal)
- [Github](./blok3.md#Github)
- [Technieken](./blok3.md#Technieken)
- [PHP](./blok3.md#PHP)
- [SQL](./blok3.md#SQL)
- [PHP vs. HTML (CSS)](./blok3.md#PHP-vs-HTML-CSS)
- [URL](./blok3.md#URL)
- [Webserver](./blok3.md#Webserver)
- [Voordat je verder gaat](./blok3.md#Voordat-je-verder-gaat)
- [Een projecten map](./blok3.md#Een-projecten-map)
- [Een project beginnen](./blok3.md#Een-project-beginnen)
- [Project Forken](./blok3.md#Project-Forken)
- [Project Klonen](./blok3.md#Project-Klonen)
- [Aan de slag met het project](./blok3.md#Aan-de-slag-met-het-project)
- [Servers starten](./blok3.md#Servers-starten)
- [Je site bekijken](./blok3.md#Je-site-bekijken)
- [Database beheer](./blok3.md#Database-beheer)
- [Coderen](./blok3.md#Coderen)
- [index.php](./blok3.md#indexphp)
- [PHP Tags](./blok3.md#PHP-Tags)
- [Project bekijken](./blok3.md#Project-bekijken)
- [HTML](./blok3.md#HTML)
- [Variabelen](./blok3.md#Variabelen)
- [Opnieuw declareren](./blok3.md#Opnieuw-declareren)
- [Broncode](./blok3.md#Broncode)
- [HTML in PHP](./blok3.md#HTML-in-PHP)
- [PHP](./blok3.md#PHP)
- [Condities](./blok3.md#Condities)
- [Conditionele operatoren](./blok3.md#Conditionele-operatoren)
- [Arrays](./blok3.md#Arrays)
- [Associatieve arrays](./blok3.md#Associatieve-arrays)
- [Foreach Loops](./blok3.md#Foreach-Loops)
- [Foreach met enkel toegang tot de Waarde (value)](./blok3.md#Foreach-met-enkel-toegang-tot-de-Waarde-value) 
- [Foreach loop met toegang tot Sleutel (key) en Waarde (value)](./blok3.md#Foreach-loop-met-toegang-tot-Sleutel-key-en-Waarde-value)
- [Request Response Cycle](./blok3.md#Request-Response-Cycle)
- [Requests](./blok3.md#Requests)
- [GET request](./blok3.md#GET-request)
- [POST request](./blok3.md#POST-request)
- [Superglobal arrays](./blok3.md#Superglobal-arrays)
- [Ingebouwde PHP functies](./blok3.md#Ingebouwde-PHP-functies)
- [Werken met een Database (SQL)](./blok3.md#Werken-met-een-Database-SQL)
- [Database Connectie](./blok3.md#Database-Connectie)
- [Alle rijen ophalen](./blok3.md#Alle-rijen-ophalen)
- [Enkele Rij ophalen](./blok3.md#Enkele-Rij-ophalen)
- [Dynamische link](./blok3.md#Dynamische-link)
- [Afbeeldingen Toevoegen](./blok3.md#Afbeeldingen-Toevoegen)
- [Nieuw Project](./blok3.md#Nieuw-Project)

## [Blok 4](./blok4.md#Blok-4)

- [Data opslaan](./blok4.md#Data-opslaan)
- [Formulier & POST-request](./blok4.md#Formulier--POST-request)
- [Data controleren](./blok4.md#Data-controleren)
- [Data opslaan](./blok4.md#Data-opslaan-1)
- [Registreren](./blok4.md#Registreren)
- [Inloggen](./blok4.md#Inloggen)
- [Levensduur van een variabele](./blok4.md#Levensduur-van-een-variabele)
- [Levensduur *Normale variabele*](./blok4.md#Levensduur-Normale-variabele)
- [Levensduur Request arrays](./blok4.md#Levensduur-Request-arrays)
- [Levensduur Session array](./blok4.md#Levensduur-Session-array)
- [Authenticatie](./blok4.md#Authenticatie)
- [Autorisatie](./blok4.md#Autorisatie)
- [Zoeken](./blok4.md#Zoeken)
- [Dashboard data](./blok4.md#Dashboard-data)
- [Is ingelogd?](./blok4.md#Is-ingelogd)
- [Tijd weergeven](./blok4.md#Tijd-weergeven)
- [Tool data](./blok4.md#Tool-data)
- [Meerdere tabellen](./blok4.md#Meerdere-tabellen)
- [Herhaling](./blok4.md#Herhaling)

## [Blok 7](./blok7.md#Blok-7)

- [SQL Injections](./blok7.md#SQL-Injections)
- [SQL prepared statements](./blok7.md#SQL-prepared-statements)
- [Database Conenctie](./blok7.md#Database-Conenctie)
- [Prepare SQL](./blok7.md#Prepare-SQL)
- [Bind Params](./blok7.md#Bind-Params)
- [Execute](./blok7.md#Execute)
- [Delete](./blok7.md#Delete)




