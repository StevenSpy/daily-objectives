# Objectifs journaliers

## Mercredi 21/08/2019

- [x] Javascript :

  - [x] Comprendre le fonctionnement des opérateurs conditionnels `if` et `?` (https://javascript.info/ifelse)

    - [x] Faire les 5 exercices

      ### Exercice 1 :

      Oui, car la condition est un string non vide, il y' a 0 dedans, donc la condition nous retourne True et de ce fait affiche Hello.

      ### Exercice 2 :

    ```

      let jsOfficialName = prompt("Quel est le vrai nom de JavaScript ?");

      if (jsOfficialName == "ECMAScript"){
      alert("Right");
      }
      else{
      alert("You don't know ECMAScript !");
      }

    ```

    ### Exercice 3 :

    ```

    let number = +prompt("Entrez un nombre", 0);

    if (number > 0){
        alert(1);
    }
    else if (number < 0){
        alert(-1);
    }
    else{
        alert(0);
    }

    ```

    ### Exercice 4 :

    `let result = (a + b < 4)? "Below" : "Over";`

    ### Exercice 5 :

    `let message = (login == "Employee") ? "Hello" : (login == "Director") ? "Grettings" : (login == "") ? "No login" : "";`

* [x] Algo :

  - [x] Ecrire en pseudocode le Insertion Sort (création pure)
  - [x] Faire valider son code par un "élève" qui joue le rôle de l'ordinateur

* [x] CSS :
  - [x] Comprendre l'utilité et le fonctionnement des `mixins` dans SASS
  - [x] Comprendre l'utilité et le fonctionnement de l'`extend` dans SASS
