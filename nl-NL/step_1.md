Wanneer je een functie **aanroept** of **definieert**, voeg je altijd ronde haakjes toe achter de naam ervan. Net als dit voorbeeld hieronder:

```python
def menu(): # Defines a function
  print('Hello')

menu() # Calls a function
```

Deze haakjes kunnen worden gebruikt om gegevens **door te geven** aan een functie uit een ander gedeelte van je code. Deze gegevens kunnen vervolgens door de functie worden gebruikt om bepaalde taken uit te voeren.

De labels tussen de haakjes heten **parameters**. Een functie kan meerdere parameters hebben, afhankelijk van het doel van de functie.

De onderstaande voorbeeldfunctie heeft **twee parameters**, namelijk `naam` en `speler_id`.

```python
def menu(name, player_id):
  print(f'Hello {name}, your player ID is {player_id}')
```

Een ander deel van je code kan om de naam van een speler vragen of een speler-ID genereren. Deze kunnen vervolgens **worden doorgegeven aan** de `menu()` functie om te worden gebruikt om een welkomstbericht weer te geven.

**Waarden** die aan een functie worden doorgegeven, worden **argumenten**genoemd.

In de onderstaande voorbeeldcode zie je dat de functie `menu()` wordt gedefinieerd. Je kunt ook zien dat de naam en het ID van de speler in de functie worden doorgegeven als **argumenten**.

--- code ---
---
language: python filename: line_numbers: true line_number_start:
line_highlights:
---
def menu(name, player_id):

  print(f'Hello {name}, your player ID is {player_id}') # The function uses the values

username = 'Hayden' id = 3215

menu(username, id) # 'Hayden' and '3215' are passed as arguments into the function --- /code ---
