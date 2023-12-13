# LET OP! Verwijder deze repository niet, tenzij...

Deze repository bevat 2 folders die met hun inhoud van belang zijn bij het renderen van Respec documentatie in andere repositories:
* js
* media

De eerste folder bevat het bestand 'organisation-config.js' met de eerder genoemde configuration properties. Aanpassing van deze properties leidt tot andere resultaten bij het renderen van Respec documentatie. Vanuit alle repositories die m.b.v. de VNG-R-Respec-Template repository zijn aangemaakt wordt hiernaar verwezen. 
De tweede folder bevat 'logo-VNG-Realisatie.ico' en 'logo-VNG-Realisatie.jpg', images met het VNG Realisatie logo die eveneens bij het renderen van Respec documentatie in andere repositories worden gebruikt.

Verwijderen van deze repositoy leidt tot andere resultaten bij het renderen van de Respec documentatie in de andere repositories. Verwijder deze repository dan ook alleen als het renderen van Respec documentatie niet meer van toepassing is of als dit op een andere wijze wordt gedaan.

Waarschijnlijk kan het 'build.yml' action script in de folder '.github/workflows/' van deze repository nog worden verwijderd aangezien het renderen van Respec documentatie voor deze repository niet van belang is. Vooralsnog laten we die echter nog even staan.
