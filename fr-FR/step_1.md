Lorsque tu **appelles** ou **définis** une fonction, tu ajoutes toujours des parenthèses après son nom. Tout comme dans cet exemple ci-dessous :

```python
def menu(): # Defines a function
  print('Hello')

menu() # Calls a function
```

Ces parenthèses peuvent être utilisées pour **transmettre** des données à une fonction à partir d'une autre section de ton code. Ces données peuvent ensuite être utilisées par la fonction pour réaliser certaines tâches.

Les libellés entre parenthèses sont appelés **paramètres**. Une fonction peut avoir plusieurs paramètres, selon son objectif.

L'exemple de fonction ci-dessous a **deux paramètres**, qui sont `nom` et `id_joueur`.

```python
def menu(name, player_id):
  print(f'Hello {name}, your player ID is {player_id}')
```

Une autre partie de ton code peut demander le nom d'un joueur ou générer un identifiant de joueur. Ceux-ci peuvent ensuite être **transmis à** la fonction `menu()` pour être utilisés dans un message de bienvenue.

Les **valeurs** qui sont transmises à une fonction sont appelées **arguments**.

Dans l'exemple de code ci-dessous, tu peux voir la fonction `menu()` en cours de définition. Tu peux également voir le nom et l'identifiant du joueur transmis à la fonction sous forme d'**arguments**.

--- code ---
---
language: python filename: line_numbers: true line_number_start:
line_highlights:
---
def menu(name, player_id):

  print(f'Hello {name}, your player ID is {player_id}') # The function uses the values

username = 'Hayden' id = 3215

menu(username, id) # 'Hayden' and '3215' are passed as arguments into the function --- /code ---
