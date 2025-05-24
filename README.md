The First Generator will export each pokemon entry for one said custom pokedex like the following for example:  
(this generator can also add in mega and gmax forms for each pokemon entry)
```json
{
  "id": "cobblemon:slitherwing_aspect",
  "speciesId": "cobblemon:slitherwing",
  "displayAspects": ["aspect"],
  "conditionAspects": ["aspect"],
  "forms": [
    {
      "displayForm": "Normal",
      "unlockForms": ["Normal"]
    }
  ],
  "variations": [
    {
      "displayName": "slitherwing_aspect",
      "aspects": ["aspect"]
    }
  ]
}
```

The Second Generator will form the main pokedex file like so:
```json
{
"type": "cobblemon:simple_pokedex_def",
"id": "frontier:aspect",
"sortOrder": 12,
"entries": ["cobblemon:bulbasaur_aspect"]
}
```

The 3rd and final generator will generate the dex additions file for you:
```json
{
  "dexId": "cobblemon:aspect",
  "entries": [
    "name:aspect"
  ]
}
```

notes:
* where it says aspect will be replaced with what your own aspect is
* where it says name will be what you have placed as what your name is, in my files i used our server name
