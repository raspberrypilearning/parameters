## Using parameters in functions

When you **call** or **define** a function you always add curved brackets after its name. Just like this example below:

```python
def menu(): # Defines a function
  print('Hello')

menu() # Calls a function
```

Those brackets can be used to **pass** data into a function from another section of your code. This data can then be used by the function to carry out some tasks. 

The labels inside the brackets are called **parameters**. A function can have multiple parameters depending on the purpose of the function. 

The example function below has **two parameters**, which are `name` and `player_id`. 

```python
def menu(name, player_id):
  print(f'Hello {name}, your player ID is {player_id}')
```

Another part of your code might ask for a players name or generate a player ID. These can then be **passed into** the `menu()` function to be used to display a welcome message. 

**Values** that are passed into a function are called **arguments**. 

In the example code below you can see the `menu` function being defined. You can also see the player's name and ID being passed into the function as arguments. 

--- code ---
---
language: python
filename: 
line_numbers: true
line_number_start: 
line_highlights: 
---
def menu(name, player_id):
    
  print(f'Hello {name}, your player ID is {player_id}') # The function uses the values 

name = 'Hayden'
player_id = 3215

menu(name, player_id) # 'Hayden' and '3215' are passed as arguments into the function
--- /code ---
