# Objectifs journaliers

## Mardi 27/08/2019

- [x] Javascript :

  - [x] Comprendre le fonctionnement des opérateurs logiques `||`, `&&` et `!` (https://javascript.info/logical-operators)

    - [x] Faire les 9 exercices

          ### Exercice 1 :

          `alert( null || 2 || undefined );` cet alert nous affichera 2 car || recherche la première valeur qui est vraie.

          ### Exercice 2 :

          `alert( alert(1) || 2 || alert(3) );` cet alert nous retounera d'abord 1, puis undefined car la fonction alert ne retourne aucune valeur, puis nous affichera 2 qui est la première valeur qui est vraie.

          ### Exercice 3 :

          `alert( 1 && null && 2 );` cet alert nous retournera null car && recherche la première valeur qui est fausse.

          ### Exercice 4 :

          `alert( alert(1) && alert(2) );` cet alert nous retournera d'abord 1, et ensuite undefined car la fonction alert ne retourne aucune valeur.

          ### Exercice 5 :

          `alert( null || 2 && 3 || 4 );` cet alert nous retournera 3 : tout d'abord en terme de précédence le && est supérieur et donc s'éxécute en premier 2 && 3, 3 étant la première valeur fausse cela nous donne `alert( null || 3 || 4)` et ici la première valeur qui est vraie est 3.

          ### Exercice 6 :

          ```
          let age = +prompt("Quel est votre âge ?", 0);

          if (age >=14 && age <=90){
              alert("Vous avez bien entre 14 et 90 ans d'âge");
          }
          else{
              alert("Vous n'avez pas entre 14 et 90 ans d'âge)";
          }

          ```

          ### Exercice 7 :

          `if (!(age>=14 && age<=90))`
          `if (age < 14 || age > 90)`

          ### Exercice 8 :

          L'alert 1 et l'alert 3 vont s'afficher.

          Le premier alert va s'afficher car le || cherche la première valeur vraie : - 1.
          Le deuxième alert ne va pas s'afficher car le && cherche la première condition de fausse est 0 équivaut à false de ce fait il n'affichera rien.
          Le troisième alert va s'afficher : tout d'abord le && va être vérifier en premier (précédence supérieur au ||) ne trouvant pas de valeur fausse il va nous retourner la dernière valeur, et il s'agit de 1, il ne reste qu'à la fin null || 1 sachant le ou cherche la première valeur qui est vraie, dans notre cas 1, il affiche donc l'alert.

          ### Exercice 9 :

          ```
            let userName;

            userName = prompt("Quel est votre nom ?");

            if (userName == "Admin"){
                let passWord;
                passWord = prompt("Quel est votre mot de passe ?");

                if (passWord == "TheMaster"){
                    alert("Welcome !");
                }
                else if (passWord =="" || passWord == null){
                    alert("Canceled !");
                }
                else{
                    alert("Wrong PassWord");
                }
            }
            else if (userName == "" || userName == null){
                alert("Canceled !");
            }
            else{
                alert("I don't know you !");
            }

      ```

      ```

* [x] Algo :

  - [x] Ecrire en pseudocode le Bubble Sort (création pure)
  - [x] Faire valider son code par un "élève" qui joue le rôle de l'ordinateur

* [x] CSS :
  - [x] Découvrir l'architecture `7-1` :
    - [x] Comprendre l'intérêt de cette architecture
    - [ ] Construire son propre boilerplate SASS 7-1
