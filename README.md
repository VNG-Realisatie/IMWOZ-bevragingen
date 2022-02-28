# IMWOZ-bevragingen

Deze repository ondersteunt de ontwikkeling van de binnengemeentelijk IMWOZ-bevragingen.
Een set API's die naast de nieuwe versie van StUFWoz worden ontwikkeld om vanuit vak-applicaties gegevens op te kunnen vragen bij de WOZ-registratie, de taxatie-registratie of een andere relevante binnengemeentelijke gegevensopslag in het kader van de WOZ.

**Deze API's zijn in ontwikkeling !! Op dit ogenblik zijn de API's nog niet volwassen genoeg om ingebouwd te worden in productie-software.**
**Proef-implementaties (en terugkoppeling van de bevindingen daaruit) zijn uiteraard wel mogelijk, maar de specificatie kan op dag-basis wijzigen.**
**Als er een eerste stabiele versie is wordt daar een release van aangemaakt en wordt dit op deze plek (en via andere communicatie-lijnen) gedeeld.**

De Specificatie van de betreffende API's zijn op de volgende locaties te bekijken :
 - Aanslagregel in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/ASL-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/ASL-redoc) --- [technische specificaties](specificatie/ASL/openapi.yaml)
 - Biljetten in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/BLJ-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/BLJ-redoc) --- [technische specificaties](specificatie/BLJ/openapi.yaml)
 - BAG-objecten in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/BAG-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/BAG-redoc) --- [technische specificaties](specificatie/BAG/openapi.yaml)
 - Controleobjectkenmerken in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/CTL-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/CTL-redoc) --- [technische specificaties](specificatie/CTL/openapi.yaml)
 - Erfpacht in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/Erfpacht-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/Erfpacht-redoc) --- [technische specificaties](specificatie/Erfpacht/openapi.yaml)
 - Kadastraal Onroerende Zaken in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/KOZ-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/KOZ-redoc) --- [technische specificaties](specificatie/KOZ/openapi.yaml)
 - Personen in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/PRS-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/PRS-redoc) --- [technische specificaties](specificatie/PRS/openapi.yaml)
 - Resultaten Marktanalyse in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/RMA-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/RMA-redoc) --- [technische specificaties](specificatie/RMA/openapi.yaml)
 - Taxaties in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/TAX-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/TAX-redoc) --- [technische specificaties](specificatie/TAX/openapi.yaml)
 - Transacties in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/TRN-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/TRN-redoc) --- [technische specificaties](specificatie/TRN/openapi.yaml)
 - Taxatieverslagen in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/TVS-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/TVS-redoc) --- [technische specificaties](specificatie/TVS/openapi.yaml)
 - Waardebepalingen in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/WBP-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/WBP-redoc) --- [technische specificaties](specificatie/WBP /openapi.yaml)
 - WOZDeelobjecten in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/WDO-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/WDO-redoc) --- [technische specificaties](specificatie/WDO/openapi.yaml)
 - WOZobjecten in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/WOZ-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/WOZ-redoc) --- [technische specificaties](specificatie/WOZ/openapi.yaml)
 - Waarden in [Swagger-UI](https://vng-realisatie.github.io/IMWOZ-bevragingen/WRD-swagger-ui) of [Redoc](https://vng-realisatie.github.io/IMWOZ-bevragingen/WRD-redoc) --- [technische specificaties](specificatie/WRD/openapi.yaml)

## Documentatie

Voor de volgende onderwerpen is documentatie over de bedoelde werking van de API opgesteld:
 - [Toepassen van de parameter PeilTijdstipMaterieel](/gebruikPeiltijdstipMaterieel.md)
 - [Overzicht-queryparameters](./overzicht-queryparameters.md)

## Meedenken met de ontwikkelingen?

* Bekijk de specificaties
* Download de technische specificaties.

Bekijk de bestaande [issues](https://github.com/VNG-Realisatie/IMWOZ-bevragingen/issues) en lever een bijdrage aan de discussie. Breng eventeel een nieuw issue in als een onderwerp nog niet geadresseerd is.

## Bronnen

* [Informatiemodel IMWOZ](https://rkathman.home.xs4all.nl/IMWOZ/IMWOZ.html)
* [REST API Design Rules](https://docs.geostandaarden.nl/api/API-Designrules/)
* [Landelijke API strategie voor de overheid](https://geonovum.github.io/KP-APIs/)
* [Stelselcatalogus](https://www.stelselcatalogus.nl/registraties/registratie?id=http://opendata.stelselcatalogus.nl/id/registratie/WOZ)


## Licentie

Copyright &copy; Waarderingskamer 2021
Licensed under the [EUPL](https://github.com/VNG-Realisatie/IMWOZ-bevragingen/blob/master/LICENCE.md)
