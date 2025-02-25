Une fonction est un bloc de code réutilisable qui exécute une tâche spécifique.

Les fonctions décomposent ton code en tâches particulières pour qu'il soit plus facile à comprendre.

C'est surtout pratique lorsque tu dois effectuer des tâches plusieurs fois. Ce sont comme des outils que tu peux réutiliser dans différentes parties de ton code.

### Écrire une fonction :

- Commence par le mot-clé `function` pour indiquer la création d'une fonction.
- Donne un nom à ta fonction (par exemple `ajouterNombres`).
- Inclue des parenthèses `()` après le nom de la fonction. Elles peuvent contenir des paramètres (entrées) dont ta fonction a besoin.
- Utilise des accolades ouvertes `{` pour définir le bloc de code que la fonction va exécuter.
- Ferme les accolades `}` pour indiquer la fin de la fonction.

Voici un exemple :

--- code ---
---
language: js
filename:
line_numbers:
line_number_start:
line_highlights:
---

function addNumbers(a, b) {
  return a + b;
}
    
--- /code ---

Ici, `ajouterNombres` est une fonction qui prend deux entrées `a` et `b` et renvoie leur somme.

### Utiliser une fonction :

Pour utiliser une fonction, tu dois l'**appeler**.

Ici, la fonction `ajouterNombres()` est appelée avec les valeurs 5 et 8.

Elle renvoie la somme de ces nombres, que tu peux ensuite utiliser. Dans cet exemple, la somme de 5 et 8 est attribuée à la variable `resultat`, et `resultat` est ensuite affiché dans la console.

--- code ---
---
language: js
filename:
line_numbers: 
line_number_start:
line_highlights:
---

let resultat = addNumbers(5, 8);
console.log(resultat); // Sorties: 13
    
--- /code ---
