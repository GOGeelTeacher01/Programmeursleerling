### `input()`

Om de gebruiker een input te vragen, gebruik je de functie input(). Dit is een functie die zeer vaak gebruikt wordt in voorbeelden.

Hier is een voorbeeld:

```python
tekst = input( "Geef een tekst in: " )
print( "Je hebt het volgende ingetypt:", tekst )
```

Realiseer je dat `input()` altijd een string teruggeeft. Als je de codes als getal wil gebruiken,
dan moet je zelf typecasten naar het gewenste datatype. Momenteel is het niet erg als je code 
vastloopt als de gebruiker een fout maakt. Op smartschool staat een module waarbij je inputs
kan vragen op een veilige manier. Hierover meer info verderop bij Modules.

```python
nummer = float(input( "Geef een getal: " ))
print( "Je getal in het kwadraat is", nummer * nummer )

geheelGetal=int(input("Geef en getal in: ")
print("Het dubbel van je getal is", nummer * 2 )
```
