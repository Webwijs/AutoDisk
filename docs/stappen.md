Stappen
=====

Ophalen XML bestanden
------------
De AutoDisk PricingManager levert de producten die toegevoegd zijn aan profielen aan in losse XML bestanden per profiel. 

Deze XML bestanden worden door de ADPM koppeling van de AutoDisk FTP gehaald en klaargezet voor database import op de website server. 

`Het ophalen van de XML bestanden wordt 2x per dag uitgevoerd.`

Welke profiel id's verwerkt worden door de koppeling kan gevonden worden op de volgende plek in het Webwijs Wordpress thema:

```console
Beheeromgeving -> Thema instellingen -> AutoDisk instellingen -> Geaccepteerde label ID's
```

Door de waarde van het veld 'Geaccepteerde label ID's' te wijzigen kunnen er profielen toegevoegd of verwijderd worden.

Importeren naar Database
----------------
Het importeren van de producten vanuit de XML bestanden naar de database gebeurd elke 5 minuten. Dit houdt in dat er elke 5 minuten gekeken wordt of er een XML bestand klaar staat op de website server.

For example:

```python
>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']
```
Importeren naar Wordpress
----------------

Opschonen na import
----------------
