### Modules
Python biedt basis functies, waarvan ik er een aantal hierboven
besproken heb. Naast die basis functies biedt Python ook een groot
aantal zogeheten "modules," waarin zich vele nuttige functies bevinden.
Functies uit modules importeren doe je als volgt.

Als alternatief kun je ook specifieke functies vanuit een module
importeren, via:

```python
from <module> import <functie1>, <functie2>, <functie3>, …
```
### Vierkanstswortel
De vierkantswortel zit in de module math onder de naam sqrt (squareroot)

sqrt(a) geeft de vierkantswortel van het getal a

Bijvoorbeeld:

```python
from math import sqrt
print(sqrt( 4 ) )
```

### `random`

De `random` module bevat functies die toevalsgetallen genereert.

-   `random()` krijgt geen parameters, en retourneert een toevalsgetal
    als een float binnen het bereik $$[0,1)$$, dat wil zeggen een bereik
    tussen nul en 1, waarbij 0.0 wel meedoet maar 1.0 niet.

-   `randint(a,b)` krijgt twee parameters, beide integers, waarbij de
    eerste kleiner dan of gelijk aan de tweede moet zijn. Het
    retourneert een toevalsgetal dat een integer is dat ligt binnen het
    bereik dat begrensd wordt door deze twee parameters, inclusief beide
    parameters. Bijvoorbeeld, `randint(2,5)` retourneert 2, 3, 4, of 5,
    elk met een gelijke kans.

For example:

```python
from random import random, randint, seed

seed()
print( "Een toevalsgetal tussen 1 en 10 is", randint( 1, 10 ) )
print( "Een ander is", randint( 1, 10 ) )
print( "3 toevalsgetallen zijn:", random(), random(), random() )
```

### `pcinput`

`pcinput` is een makkelijke module van Pieter Spruyt. Je kan hem terugvinden bij smartschool documenten. 
Plaats hem in dezelfde map als waar je al je scripts opslaat (bvb. Mijn Documenten -> Informatica) .
De module bevat vier handige functies, die de gebruiker op een veilige manier om specifieke input
vragen. De functies zijn de volgende:

-   `getInteger()` veilig input-commando voor integers. De functie eindigt pas als de gebruiker een correcte integer heeft ingegeven. De returnwaarde is dus ook een integer.

-   `getFloat()` veilig input-commando voor floats. De functie eindigt pas als de gebruiker een correcte float heeft ingegeven. De returnwaarde is dus ook een float.

-   `getString()` equivalent aan input. Geeft dezelfde string terug als de gebruiker ingeeft.

-   `getLetter()` Pas als de gebruiker precies één letter heeft ingegeven eindigt de functie, en de letter wordt dan
    als een hoofdletter geretourneerd.

Deze functies helpen je dus om code te schrijven die de gebruiker vraagt
om input met een specifiek data type te verstrekken, omdat ze garanderen
dat het programma inderdaad iets binnenkrijgt dat van het gevraagde data
type is. De code geeft geen runtime error als de gebruiker iets anders
ingeeft.

Als je het .py-bestand in de juiste map geplaatst hebt, voer dan even volgende code uit in een python-file.

```python
from pcinput import getInteger

num1 = getInteger( "Geef een geheel getal: " )
num2 = getInteger( "Geef een ander geheel getal: " )

print( num1, "+", num2, "=", num1 + num2 )
```
