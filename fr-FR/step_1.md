Une fonction est un bloc de code réutilisable qui exécute une tâche spécifique.

Les fonctions décomposent ton code en tâches particulières pour qu'il soit plus facile à comprendre.

They are especially useful when you have tasks that need to be done multiple times. Ce sont comme des outils que tu peux réutiliser dans différentes parties de ton code.

### Writing a function:

- Commence par le mot-clé `function` pour indiquer la création d'une fonction.
- Donne un nom à ta fonction (par exemple `ajouterNombres`).
- Inclue des parenthèses `()` après le nom de la fonction. These can contain the parameters (inputs) your function needs.
- Utilise des accolades ouvertes `{` pour définir le bloc de code que la fonction va exécuter.
- Ferme les accolades `}` pour indiquer la fin de la fonction.

Voici un exemple :

## --- code ---

language: js
filename:
line_numbers:
line_number_start:
line_highlights:
-----------------------------------------------------

function addNumbers(a, b) {
return a + b;
}

\--- /code ---

Ici, `ajouterNombres` est une fonction qui prend deux entrées `a` et `b` et renvoie leur somme.

### Using a function:

Pour utiliser une fonction, tu dois l'**appeler**.

Ici, la fonction `ajouterNombres()` est appelée avec les valeurs 5 et 8.

It returns the sum of the numbers, which you can then use. In this example, the sum of 5 and 8 is assigned to the variable `result` and then `result` is displayed in the console.

## --- code ---

language: js
filename:
line_numbers:
line_number_start:
line_highlights:
-----------------------------------------------------

let resultat = ajouterNombres(5, 8);
console.log(resultat); // Sorties : 13

\--- /code ---
