Enkele wiskundige functies die makkelijk te gebruiken zijn.

### Type casting

Ik heb al gesproken over type casting functies in hoofdstuk
5,
maar nu ik meer details van functies heb gegeven, kan ik de beschrijving
completeren.

-   `float() : geeft een kommagetal bij ingeven van een int, float of string van cijfers

-   `int()` geeft een geheel getal terug bij ingeven van een int, float of string van cijfers

-   `str()` geeft de string representatie van de waarde van de parameter.

Wat denk je dat de volgende code doet? Als je het niet weet, test dan de
code.

```python
float('10') #resultaat is 10.0
float(10) #resultaat is 10.0
int(5.65) #resultaat is 5
int('5.65') #resultaat is 5
str(5.65) #resultaat is tekst "5.65"
```

### Standaard berekeningen

Een paar basis Python functies helpen met berekeningen.

-   `abs(getal)`geeft absolute waarde van input

-   `max(a,b,c,...)` geeft het maximum van 2 of meer parameters
-   
-   `min(a,b,c,...)` geeft het minimum van 2 of meer parameters

-   `pow(a,b) geeft  a tot de b-de macht.` 

-   `round(a,b)   rondt getal a af tot b cijfers achter de komma.` 


```python
abs(-4.545)         #geeft resultaat 4.545
max(1,2,3,4)        #geeft resultaat 4
min(1,2,3,4)        #geeft resultaat 1
pow(2,3)            #geeft resultaat 8
round(5.45735,2)    #geeft resultaat 5.46
```

### Vierkantswortel

Voor de vierkantswortel heb je een speciale module nodig. Dit leer je verder dit hoofdstuk.
