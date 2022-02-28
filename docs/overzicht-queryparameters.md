---
layout: page-with-side-nav
title: Ontwikkelversie IMWOZ-bevragingen
---

# Overzicht queryparameters en relaties in antwoorden

## ASL
Queryparameters:
belastingsoort
statusAanslag
statusBetaling
groep: heffingsTijdvak (begindatum; einddatum)
isGebaseerdOp
isVoor
communiceertVia (ASLPRSVES)

In antwoord opnemen relaties:
isGebaseerdOp
isVoor (inclusief de ASLPRSVES)


## BLJ
Queryparameters:
statusBiljet
groep brondocument (identificatie, datum)
heeftAanslagregel
isVoor
communiceertVia (BLJPRSVES)
heeftBeschikkingsregel

In antwoord opnemen relaties:
heeftAanslagregel
isVoor (inclusief de BLJPRSVES)
heeftBeschikkingsregel

## BSK
queryparameters:
volgnummer
status­Beschikking
brondocument (identificatie, datum)
steltVast
isVoor
communiceertVia (BSKPRSVES)

In antwoord opnemen relaties:
steltVast
isVoor (inclusief de BSKWRDVES)


## BZW
Queryparameters:
statusBezwaar
groep brondocument (identificatie, datum)
isTegenBiljet
wordtBehandeldDoorGemachtigde
isTegenAanslagregel
isIngediendDoor
communiceertVia (BZWPRSVES)
isTegenBeschikking

In antwoord opnemen relaties:
isTegenBiljet
wordtBehandeldDoorGemachtigde (inclusief de BZWPRSGMCVES)
isTegenAanslagregel
isIngediendDoor (inclusief de BZWPRSANVVES)
isTegenBeschikking


## CTL
Queryparameters:
identificatieUitvoerder
taxateur
methodiekControle
datumControle
redenControle
gecontroleerdeWOZDeelObjecten
gecontroleerdeObjectKenmerken
isVoor

In antwoord opnemen relaties:
isVoor

## Erfpacht
queryparameters:
overeenkomstnummer
adres
eigendomnummer
groep soort­Overeenkomst (code­Soort­Overeenkomst)
betreft

In antwoord opnemen relaties:
betreft


## KOZ
queryparameters:
kadastraleAanduiding

In antwoord opnemen relaties:
geen


## LIG
queryparameters:
statusLigplaats
en uit AOT:
groep adres (identificatieNummeraanduiding)
groep adres (woonplaatsnaam, openbareRuimteNaam, straatnaam, huisnummer, huisletter huisnummertoevoeging)
groep adres (postcode,	huisnummer, huisletter	, huisnummertoevoeging)

In antwoord opnemen relaties:
geen


## NNP
queryparameters:
statutaire­Naam
kvk­Nummer
en uit PRS:
verantwoordelijkeGemeente
identificatieBRK
groep adresAanduiding (identificatieNummeraanduiding)
groep adresAanduiding (woonplaatsnaam, openbareRuimteNaam, straatnaam, huisnummer, huisletter, huisnummertoevoeging, locatieomschrijving	)
groep adresAanduiding (postcode, huisnummer, huisletter, huisnummertoevoeging)
groep adresBuitenland (land, adresBuitenland1, adresBuitenland2, adresBuitenland3)
groep adresPostbusAntwoordnummer (woonplaatsnaam, postbusOfAntwoordnummer)
groep adresPostbusAntwoordnummer (postcode, postbusOfAntwoordnummer)

In antwoord opnemen relaties:
geen


## NPS
queryparameters:
geslachtsnaam
voorvoegsel­Geslachtsnaam
geslachtsaanduiding
aanduidingNaamgebruik
aanhefAanschrijving
voorvoegselNaamAanschrijving
naamAanschrijving
geboortedatum
kvk­Nummer
verblijftIn
en uit PRS:
verantwoordelijkeGemeente
identificatieBRK
groep adresAanduiding (identificatieNummeraanduiding)
groep adresAanduiding (woonplaatsnaam, openbareRuimteNaam, straatnaam, huisnummer, huisletter, huisnummertoevoeging, locatieomschrijving	)
groep adresAanduiding (postcode, huisnummer, huisletter, huisnummertoevoeging)
groep adresBuitenland (land, adresBuitenland1, adresBuitenland2, adresBuitenland3)
groep adresPostbusAntwoordnummer (woonplaatsnaam, postbusOfAntwoordnummer)
groep adresPostbusAntwoordnummer (postcode, postbusOfAntwoordnummer)

In antwoord opnemen relaties:
verblijftIn


## NSWLandgoedTAX
queryparameters:
uit TAX:
waardepeildatum
toestandspeildatum
betrokkenWOZOobject

In antwoord opnemen relaties:
uit TAX:
wordtOpgebouwdUit (TXK)
vergelekenWOZOobject
betrokkenWOZObject
onderbouwendeTransacties
wordtOpgebouwdUit (TDO)


## NSWLandgoedTDO
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## NUM
queryparameters:
woonplaatsnaam
postcode
openbareRuimteNaam
straatnaam
huisnummer
huisletter
huisnummertoevoeging

In antwoord opnemen relaties:
geen


## OPR
queryparameters:
geen (dus alleen selecteren op basis van identificatie)

In antwoord opnemen relaties:
geen


## PND
queryparameters:
geen (dus alleen selecteren op basis van identificatie)

In antwoord opnemen relaties:
geen


## RMA
queryparameters:
waardepeildatum
toestandspeildatum
wordtVergelekenMet
analyseert
heeftBetrekkingOp

In antwoord opnemen relaties:
wordtVergelekenMet
analyseert
heeftBetrekkingOp


## SOC
queryparameters:
geen (dus alleen selecteren op basis van identificatie)

In antwoord opnemen relaties:
geen


## STA
queryparameters:
statusStandplaats
en uit AOT:
groep adres (identificatieNummeraanduiding)
groep adres (woonplaatsnaam, openbareRuimteNaam, straatnaam, huisnummer, huisletter huisnummertoevoeging)
groep adres (postcode,	huisnummer, huisletter	, huisnummertoevoeging)

In antwoord opnemen relaties:
geen


## SWO
queryparameters:
statusWozObject
codeGebouwdOngebouwd
documentIdentificatie
verantwoordelijkeGemeente
bevatKadastraleObjecten
ligtIn (WSP)

In antwoord opnemen relaties:
bevatKadastraleObjecten
ligtIn (WSP)


## TAX
queryparameters:
waardepeildatum
toestandspeildatum
betrokkenWOZOobject

In antwoord opnemen relaties:
wordtOpgebouwdUit (TXK)
vergelekenWOZOobject
betrokkenWOZObject
onderbouwendeTransacties
wordtOpgebouwdUit (TDO)


## TDOAgrarischeAsbest
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TDOAgrarischeGebouw
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

## TDOAgrarischeGrond
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TDOBijzonderOmstandigheid
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TDOGecorrigeerdeVervangingswaarde
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TDOGrond
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TDOHuurwaardeKapitalisatie
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TDOMotorbrandstofverkooppunt
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TDOStuksprijs
queryparameters:
uit TDO:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
uit TDO:
geeftWaardeVan
hoortBijTaxatie


## TRN
queryparameters:
aardMarktinformatie
soortTransactie
datumTransactie
aanduidingBruikbaarheid
omstandighedenTransactie
documentIdentificatie
heeftBetrekkingOp
wordtGeanalyseerdIn
isBetrokkenIn

In antwoord opnemen relaties:
heeftBetrekkingOp
wordtGeanalyseerdIn
isBetrokkenIn


## TTK
queryparameters:
geeftWaardeVan
hoortBijTaxatie

In antwoord opnemen relaties:
geeftWaardeVan
hoortBijTaxatie


## TVN
queryparameters:
uit TVS:
waardepeildatum
toestandspeildatum
datumVaststelling
urlPersoonlijkeWOZpagina
documentIdentificatie
onderbouwt
isVoor
isGebaseerdOp

In antwoord opnemen relaties:
uit TVS
onderbouwt
isVoor
vermeldtVoorBetrokkenObject
isGebaseerdOp


## TVW
queryparameters:
uit TVS:
waardepeildatum
toestandspeildatum
datumVaststelling
urlPersoonlijkeWOZpagina
documentIdentificatie
onderbouwt
isVoor
isGebaseerdOp

In antwoord opnemen relaties:
wordtOnderbouwdMet
gebruiktAlsOnderbouwing
en uit TVS:
onderbouwt
isVoor
vermeldtVoorBetrokkenObject
isGebaseerdOp


## TXK
queryparameters:
nummer­WOZDeelobject
isKenmerkVan

In antwoord opnemen relaties:
isKenmerkVan


## VBO
queryparameters:
statusVerblijfsobject
gebruiksdoel
maaktDeelUitVan
en uit AOT:
groep adres (identificatieNummeraanduiding)
groep adres (woonplaatsnaam, openbareRuimteNaam, straatnaam, huisnummer, huisletter huisnummertoevoeging)
groep adres (postcode,	huisnummer, huisletter	, huisnummertoevoeging)

In antwoord opnemen relaties:
maaktDeelUitVan


## VES
queryparameters:
eersteHandelsnaam
kvkNummer
verantwoordelijkeGemeente
groep adresAanduiding (identificatieNummeraanduiding)
groep adresAanduiding (woonplaatsnaam, openbareRuimteNaam, straatnaam, huisnummer, huisletter, huisnummertoevoeging, locatieomschrijving	)
groep adresAanduiding (postcode, huisnummer, huisletter, huisnummertoevoeging)
groep adresBuitenland (land, adresBuitenland1, adresBuitenland2, adresBuitenland3)
groep adresPostbusAntwoordnummer (woonplaatsnaam, postbusOfAntwoordnummer)
groep adresPostbusAntwoordnummer (postcode, postbusOfAntwoordnummer)

In antwoord opnemen relaties:
geen


## WBP
queryparameters:
waardepeildatum
toestandspeildatum
datumWaardevaststelling
statusWaardevaststelling
statusTaxatie
leidtTot
isVoor
wordtOnderbouwdMet
heeft

In antwoord opnemen relaties:
leidtTot
isVoor
heeft


## WDO
queryparameters:
nummerWOZDeelobject
statusWOZDeelobject
typeWOZDeelobject
typeWOZDeelobjectOptioneel
materiaalCode
aanduidingInAanbouw
codeWOZDeelobject
archetypeAanduiding
bestaatUitPand
isOnderdeelVan
heeftAlsAanduiding
bestaat­Uit


In antwoord opnemen relaties:
bestaatUitPand
isOnderdeelVan
heeftAlsAanduiding
bestaat­Uit


## WOZ
queryparameters:
statusWozObject
gebruikscode
typeWOZObject
functieWOZObject
typeWOZObjectOptioneel
aanduiding­Repeterend
aanduidingInAanbouw
soort­Object­Code
codeGebouwdOngebouwd
ozb­Vrijstelling
aanduiding­Bouwstroom
groepaanduiding
documentIdentificatie
verantwoordelijkeGemeente
groep aanduidingWOZobject (identificatieNummeraanduiding)
groep aanduidingWOZobject (woonplaatsnaam	, openbareRuimteNaam, straatnaam, huisnummer, huisletter, huisnummertoevoeging, locatieomschrijving)
groep aanduidingWOZobject (postcode	huisnummer, huisletter, huisnummertoevoeging)
groep inBewerking (aanduidingMedewerkerOrganisatie, redenInBewerking, statusInBewerking, heeftBetrekkingOpJaar, ingangsdatumInBewerking, einddatumInBewerking)
heeftTransacties
ontleentAanduidingAanAdresseerbaarObject
bevatKadastraleObjecten
heeftSluimerendObject
heeftPand
heeftBelanghebbende
communiceertVia (WOZPRSVES)
ligtIn (WSP)
isVerbondenMet
heeftDeelobject
heeftAlsAanduiding

In antwoord opnemen relaties:
heeftTransacties
ontleentAanduidingAanAdresseerbaarObject
bevatKadastraleObjecten
isGecontroleerd
heeftSluimerendObject
ligtAan
ligtIn (WPL)
heeftTaxatiekenmerken
heeftPand
heeftBelanghebbende (inclusief de WOZPRSVES)
heeftWaarde
heeftTaxatie
ligtIn (WSP)
isVerbondenMet
heeftDeelobject
heeftAlsAanduiding
heeftWaardebepaling


## WPL
queryparameters:
geen (dus alleen selecteren op basis van identificatie)

In antwoord opnemen relaties:
geen


## WRD
queryparameters:
waardepeildatum
toestandspeildatum
isVoor
isBeschiktMet
isBeschiktVoor
communiceertVia (WRDPRSVES)

In antwoord opnemen relaties:
isVoor
wordtVerdeeldNaar
isBeschiktMet
wordtOnderbouwdMet
isBeschiktVoor (inclusief WRDPRSVES)


## WSP
queryparameters:
geen (dus alleen selecteren op basis van identificatie)

In antwoord opnemen relaties:
geen
