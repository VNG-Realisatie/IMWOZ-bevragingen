# Toepassen van parameter PeilTijdstipMaterieel

In deze API-specifcatie zijn voor de meeste resource 2 manieren van opvragen gedefinieerd.
 - Opvragen op basis van de unieke identificatie
 - Opvragen op basis van zoek-criteria

Hieronder wordt beschreven hoe deze verschillende manieren van opvragen worden gebruikt om
actuele danwel historische voorkomens op te vragen.

## Opvragen op basis van alleen de unieke identificatie

Het opvragen op basis van een unieke identificatie is vormgegeven door het gebruik van een path-prameter.
Daarmee wordt 1 unieke resource gedefinieerd. Aangezien er sprake is van historie zullen er meerder voorkomens in de registratie opgenomen zijn met deze unieke identificatie waarbij met verschillende geldigheidsdatums de historie is opgebouwd.
Als de opvraging op basis van de unieke identificatie gedaan wordt dan wordt het actuele voorkomen geretourneerd.

Een voorbeeld van een bevraging van een actueel biljet op basis van de unieke identificatie :

**https://virtserver.swaggerhub.com/VNGRealisatie/api/bg_imwoz_biljetten/v1/biljetten/123456789**

Eventuele links naar gerelateerde voorkomens zullen op vergelijkbare wijze (met path-parameters) worden geleverd in de response.

## Opvragen op basis van de unieke identificatie in combinatie met PeilTijdstipMaterieel

Voor het opvragen van een voorkomen op een specifiek moment in de tijd is de parameter PeiltijdstipMaterieel toegevoegd.
Het karakter van de zoekactie is dan anders omdat je niet meer op 1 unieke identificatie zoekt, maar met 2 parameters. Dat wordt opgelost met het gebruik van query-parameters.
Het opvragen op van een biljet op basis van de unieke identificatie op een bepaald moment in het verleden ziet er dan als volgt uit :

**https://virtserver.swaggerhub.com/VNGRealisatie/api/bg_imwoz_biljetten/v1/biljetten?peiltijdstipMaterieel=2021-02-01&identificatie=123456789**

Eventuele links naar gerelateerde voorkomens zullen op vergelijkbare wijze (dus inclusief dezelfde PeilTijdstipMaterieel) worden geleverd in de response.
