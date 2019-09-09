# Objectifs journaliers

## Mercredi 28/08/2019

- [x] Javascript :

  - [x] Comprendre le fonctionnement des boucles `while` et `for` (https://javascript.info/while-for)

        - [x] Faire les 7 exercices

          ### Exercice 1 :

          Ce code nous retournera 1 car while(i) équivaut à dire while(i !=0) de ce fait le body décrémantera autant de fois qu'il le faut tant que i est différent de 0.

          ### Exercice 2 :

          Non, ils n'afficheront pas les mêmes valeurs.

          Le premier code affichera : 4, car arriver à 5 la condition n'est plus vérifié et de ce fait plus rien ne nous sera retourner.

          Le deuxième code affichera : 5 car on demande d'abord d'afficher i puis de l'incrémenter de ce fait il nous affichera 5.

          ### Exercice 3 :

          Ces deux codes afficheront la même chose, car le body est exécuté après la verification de la condition de ce fait dans les deux cas, on nous affichera i de 0 à 4.

          ### Exercice 4 :

          ```

          for(let i = 2; i<= 10; i++){
            if (i % 2 == 0){
              alert(i);
            }
          }

          ```

          ### Exercice 5 :

          ```
          let i = 0;

          while(i<3){
            alert(`number ${i}`);
            i++;
          }

          ```

          ### Exercice 6 :

          ```
          let num;

          do{
            num = +prompt("Entrez un nombre", 0);
          }while(num <= 100 && num)

          ```

          ### Exercice 7 :

          ```

          let n = 10;

          Prime : for (let i = 2; i <= 10; i++){
            for (let j = 2; j < i; j++){
              if (i % j == 0){
                continue Prime;
              }
            }

           alert (i);

    }

          ```

* [ ] Algo :

  - [ ] Ecrire en pseudocode le Merge Sort (création pure)
  - [ ] Faire valider son code par un "élève" qui joue le rôle de l'ordinateur

* [ ] CSS :
  - [ ] Découvrir l'approche `BEM` en CSS (https://en.bem.info/methodology/quick-start/)
    - [ ] Comprendre l'intérêt de cette convention
