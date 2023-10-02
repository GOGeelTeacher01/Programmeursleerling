In voorgaande stukken kwamen al enkele eenvoudige functies voor, zoals `print()` en `int()`. 
In dit hoofdstuk worden deze functies in meer detail besproken, samen met enkele nieuwe functies.
Maar waarom gebruiken we functies?

Stel dat je het verschil in inhoud tussen twee kubussen wil weten. Dat kan via
```python
#inhoud kubus = zijde * zijde * zijde
inhoud1 = 5*5*5
inhoud2 = 4*4*4
verschil = inhoud1-inhoud2
print( verschil )
```
Je dat dezelfde formule tweemaal gebruikt wordt. Code die je vaak herhaalt, kan veel efficiënter geprogrammeerd worden met functies. Dezelfde code zou er dan als volgt uitzien.

```python
#inhoud kubus = zijde * zijde * zijde
def inhoudKubus(zijde):
  inhoud = zijde **3
  return inhoud

#zoek het verschil tussen een kubus met zijde 5 cm en een kubus met zijde 3 cm
verschil = inhoudKubus(5)-inhoudKubus(3)
print( verschil )
```
