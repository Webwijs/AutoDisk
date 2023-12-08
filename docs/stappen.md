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
Het importeren van 
To retrieve a list of random ingredients, you can use the
`lumache.get_random_ingredients()` function:

::: lumache.get_random_ingredients
    options:
      show_root_heading: true

<br>

The `kind` parameter should be either `"meat"`, `"fish"`, or `"veggies"`.
Otherwise, [`get_random_ingredients`][lumache.get_random_ingredients] will raise an exception [`lumache.InvalidKindError`](/api#lumache.InvalidKindError).

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
