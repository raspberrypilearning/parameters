Wanneer je een functie **aanroept** of **definieert**, voeg je altijd ronde haakjes toe achter de naam ervan. Net als dit voorbeeld hieronder:

```python
def menu(): # Definieert een functie
  print('Hallo')

menu() # Roept een functie aan
```

Deze haakjes kunnen worden gebruikt om gegevens **door te geven** aan een functie uit een ander gedeelte van je code. Deze gegevens kunnen vervolgens door de functie worden gebruikt om bepaalde taken uit te voeren.

De labels tussen de haakjes heten **parameters**. Een functie kan meerdere parameters hebben, afhankelijk van het doel van de functie.

De onderstaande voorbeeldfunctie heeft **twee parameters**, namelijk `naam` en `speler_id`.

```python
def menu(naam, speler_id):
  print(f'Hallo {naam}, je speler-ID is {speler_id}')
```

Een ander deel van je code kan om de naam van een speler vragen of een speler-ID genereren. Deze kunnen vervolgens **worden doorgegeven aan** de `menu()` functie om te worden gebruikt om een welkomstbericht weer te geven.

**Waarden** die aan een functie worden doorgegeven, worden **argumenten** genoemd.

In de onderstaande voorbeeldcode zie je dat de functie `menu()` wordt gedefinieerd. Je kunt ook zien dat de naam en het ID van de speler in de functie worden doorgegeven als **argumenten**.

--- code ---
---
language: python
filename: 
line_numbers: true
line_number_start: 
line_highlights: 
---
def menu(naam, speler_id):
    
  print(f'Hallo {naam}, je speler-ID is {speler_id}') # De functie gebruikt de waarden

gebruikersnaam = 'Hayden'
id = 3215

menu(gebruikersnaam, id) # 'Hayden' en '3215' worden als argumenten aan de functie doorgegeven
--- /code ---
