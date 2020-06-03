# **Definition of Done**

In de Definition of Done (DoD) worden de algemene eisen worden gedefinieerd waar de producten die vanuit het project worden opgeleverd aan moeten voldoen. Onderstaande elementen moeten worden ingevuld.

- Informatiemodel gedefinieerd
- Architectuur gedefinieerd
- Functionele specificatie aanwezig
- API specificatie gedefinieerd
- Testgevallen beschreven
- Geïmplementeerd in referentie-implementatie

Geen onderdeel van de DoD tijdens het project, wel onderdeel van de vastgestelde koppelvlakstandaard zijn:

- Er is een overdrachtsdocument
- Er is een &#39;getting started&#39; beschrijving
- Er is een compliancy- en testvoorziening

**Informatiemodel**

- Conform MIM 1.1
- Opgeslagen in SVN
- Enterprise Architect
- Is gepubliceerd; toegankelijk voor anderen

**Architectuur**

- Modellen conform Archimate 3.x
- Gemodelleerd Archi
- Modellen opgeslagen op GitLab
- Gemodelleerd conform conventies GEMMA

**Functionele specificatie**

- Is gepubliceerd op GEMMAonline als webpagina(s)
- De positionering van de koppelvlakstandaard binnen de GEMMA architectuur is beschreven
- De referentiecomponenten die het koppelvlak moeten realiseren zijn beschreven

**API specificatie**

- Opgesteld in Open API Specification (OAS) 3
- Gepubliceerd op GitHub (link) en beschikbaar via Redoc
- Semantische betekenis van resources en parameters is opgenomen
- Voldoet aan landelijke API strategie dan wel afwijking is beargumenteerd (pas toe of leg uit)

**Testgevallen**

- Er zijn testgevallen beschreven voor alle beschreven opvraagfunctionaliteit
- Er zijn testgevallen beschreven voor elke ontwerpbeslissing
- Elk testgeval beschrijft het logische testgeval, de teststap(pen) (wat wordt gedaan) en het verwachte resultaat
- Voor zover nodig is ook de testdata beschreven die wordt gebruikt in de testgevallen

**Referentie-implementatie**

- Implementeert alle gedefinieerde operaties en functionaliteit
- Is volledig functionele applicatie die de implementatie en gebruik van de koppelvlakken demonstreert
- Implementeert ten minste alle beschreven ontwerpbeslissingen
- Source code is open source beschikbaar (gepubliceerd) op VNG Realisatie Github
- Een testset die de functionaliteit en correcte werking van de referentie-implementatie aantoont
- Implementatie bevat testdata zodat gebruikers van de referentie-implementatie deze gebruiken om hun applicatie te testen
- Documentatie van de referentie-implementatie beschrijft (ten minste) installatie en gebruik van de applicatie

**Overdrachtsdocument**

- Beheerafspraken beschreven
- Er is een lijst met bekende fouten, gewenste verbeteringen, gewenste uitbreidingen

**Getting started**

- Er is een beschrijving die developers op weg helpt om te starten met implementatie van het koppelvlak
- Bevat verwijzing naar relevante koppelvlakproducten en gerelateerde informatie en standaarden
- Er is uitleg en installatie-instructies van de referentie-implementaties
- Er is uitleg over hoe bij te dragen aan de standaard
- Er is uitleg over hoe mee ontwikkeld kan worden aan de referentie-implementatie(s), inclusief gebruik van relevante tooling

**Compliancy en testen**

- Er zijn voorbeeldberichten voor elke service/operatie
- Er zijn compliancy tests beschikbaar voor elke referentie-component (consumers en providers) en alle betreffende services en operaties, zodat leveranciers kunnen testen en aantonen dat hun applicatie voldoet aan de standaard
- De compliancy testvoorziening levert, bij succesvolle uitvoering, een rapport dat kan worden gebruikt om in de Softwarecatalogus de compliancy aan te tonen.
