Een functie is een blok herbruikbare code dat een bepaalde actie uitvoert.
Hij bestaat uit volgende onderdelen:

```python
def functieNaam(parameter1,parameter2,...):
  instructies
  return resultaat
```

### Functienamen

Iedere functie heeft een naam. Net als variabele namen, mogen functie
namen alleen bestaan uit letters, cijfers, en underscores, en mogen ze
niet starten met een cijfer. Vrijwel alle standaard Python functies
bestaan alleen uit kleine letters. Gewoonlijk is de naam van een functie
een korte beschrijving van wat de functie doet.

### Parameters

Sommige functies worden aangeroepen met parameters ("argumenten"), die
meestal verplicht zijn. De parameters worden geplaatst tussen de haakjes
die achter de functienaam staan. Als er meerdere parameters zijn, moet
je er komma's tussen zetten.

Als je een functie aanroept met verkeerde parameters, krijg je "runtime errors" (fouten
tijdens de uitvoering van code). Bijvoorbeeld, beide regels in de
volgende code leiden tot runtime errors.

```python
x = pow( 3, "2" )               #pow(a,b) geeft a tot de b-de macht
y = int( "twee-en-een-half" )
```
### Instructies

Via instructies ga je met je parameters aan de slag om tot een resultaat te komen. 
Een eenvoudig voorbeeld is een som.

```python
def som(getal1,getal2):
  som=getal1+getal2
  return som
```

### Returnwaarde

Een functie heeft vaak een returnwaarde. Als een functie een waarde
retourneert, kun je die in je code gebruiken. In onderstaande code zal 
de functie de som van 2 getallen teruggeven.

```python
def som(getal1,getal2):
  som=getal1+getal2
  return som

```

Niet alle functies retourneren een waarde. Bijvoorbeeld, `print()` geeft
geen waarde terug, maar geeft zijn parameter weer in de Python Shell.

