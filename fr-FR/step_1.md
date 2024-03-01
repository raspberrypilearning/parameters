Lorsque tu **appelles** ou **définis** une fonction, tu ajoutes toujours des parenthèses après son nom. Tout comme dans cet exemple ci-dessous :

```python
def menu(): # Définit une fonction
  print('Bonjour')

menu() # Appelle une fonction
```

Ces parenthèses peuvent être utilisées pour **transmettre** des données à une fonction à partir d'une autre section de ton code. Ces données peuvent ensuite être utilisées par la fonction pour réaliser certaines tâches.

Les libellés entre parenthèses sont appelés **paramètres**. Une fonction peut avoir plusieurs paramètres, selon son objectif.

L'exemple de fonction ci-dessous a **deux paramètres**, qui sont `nom` et `id_joueur`.

```python
def menu(nom, id_joueur):
  print(f'Bonjour {nom}, ton identifiant de joueur est {id_joueur}')
```

Une autre partie de ton code peut demander le nom d'un joueur ou générer un identifiant de joueur. Ceux-ci peuvent ensuite être **transmis à** la fonction `menu()` pour être utilisés dans un message de bienvenue.

Les **valeurs** qui sont transmises à une fonction sont appelées **arguments**.

Dans l'exemple de code ci-dessous, tu peux voir la fonction `menu()` en cours de définition. Tu peux également voir le nom et l'identifiant du joueur transmis à la fonction sous forme d'**arguments**.

--- code ---
---
language: python
filename: 
line_numbers: true
line_number_start: 
line_highlights: 
---
def menu(nom, id_joueur):

  print(f'Bonjour {nom}, ton identifiant de joueur est {id_joueur}') # La fonction utilise les valeurs

nom_utilisateur = 'Hayden'
id = 3215

menu(nom_utilisateur, id) # 'Hayden' et '3215' sont transmis comme arguments à la fonction
--- /code ---
