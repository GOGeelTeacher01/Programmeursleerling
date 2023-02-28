In hoofdstuk
4
heb ik strings kort geïntroduceerd. Ik heb uitgelegd dat een string een
tekst is, die omsloten is door enkele of dubbele aanhalingstekens, en
dat een string iedere lengte mag hebben, inclusief nul tekens lang. Het
hoofdstuk legde ook uit dat je twee strings aan elkaar kunt plakken met
behulp van de `+`, en dat je een string zichzelf kunt laten herhalen
door middel van de `*`. Bijvoorbeeld:

```python
s1 = "appel"
s2 = 'banaan'
print( s1 )
print( s2 )
print( s1 + s2 )
print( 3 * s1 )
print( s2 * 3 )
print( 2 * s1 + 2 * s2 )
```

Hoofdstuk
6
introduceerde de `format()` functie die strings op allerlei manieren kan
formatteren. Ik gaf ook aan dat je de lengte van een string kunt bepalen
met de `len()` functie.

String vergelijkingen heb ik uitgelegd in hoofdstuk
7;
ik noemde specifiek het feit dat bij vergelijkingen tussen strings de
alfabetische regels worden aangehouden, waarbij hoofdletters altijd
eerder in het alfabet staan dan kleine letters. Ik zal hier in dit
hoofdstuk meer over zeggen. In hoofdstuk
7
gaf ik ook aan dat de `in` operator gebruikt kan worden om te testen of
tekens of substrings voorkomen in een string.

Hoofdstuk
8
legde uit hoe je met een `for` loop alle tekens in een string kunt
doorlopen.

```python
s1 = "mango"
s2 = "banaan"
for letter in s1:
    if letter in s2:
        print( s1, "en", s2, "bevatten beide de letter", letter )
```
