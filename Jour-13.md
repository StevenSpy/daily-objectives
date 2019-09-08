# Objectifs journaliers

## Mercredi 07/08/2019

- [x] Javascript :

  - [x] Comprendre le fonctionnement des opérateurs en Javascript (https://javascript.info/operators#operator-precedence)

    - [x] Comprendre la différence entre unaire, binaire et opérande
    - [x] Comprendre la concaténation
    - [x] Comprendre la précédence des opérateurs
    - [x] Comprendre le modulo
    - [x] Comprendre l'incrémentation, la différence entre préfix et postfix

      ### Exercice 1 :

      `let a = 1, b = 1; let c = ++a; let d = b++;`

      a = 2 --> a vaut initialement 1 mais arrivé à la variable c nous l'incrémentons de 1 de ce fait la valeur assignée à a est 2.
      b = 2 --> b vaut initialement 1 mais arrivé à la variable d nous l'incrémentons de 1 et de ce fait la valeur assignée à b est 2.
      c = 2 --> c vaut 2 car nous avons la forme préfixe de l'incrémentation, c'est à dire que nous incrémentons de 1 a avant de l'afficher.
      d = 1 --> d vaut 1 car nous avons la forme postfixe de l'incrémentation, c'est à dire que nous affichons d'abord b qui vaut 1 et seulement ensuite la valeur de b est incrémentée, de ce fait d nous retourne 1, et derrière b prend pour nouvelle valeur 2.

      ### Exercice 2 :

      `let a = 2; let x = 1 + (a *=2);`

      a = 4; () = précédence de 20 de ce fait on fait d'abord cette partie du calcul, ensuite a _=2 équivaut à dire a = a _ 2; de ce fait a = 2 _ 2, ce qui donne 4.
      x = 5; () = précédence de 20 de ce fait on fait d'abord cette partie du calcul, ensuite a _=2 équivaut à dire a = a _ 2; de ce fait a = 2 _ 2, ce qui donne 4, et ensuite on lui ajoute 1 ce qui donne 5 puis on assigne à x la résultat du calcul.

* [x] Algo :

  - [x] Découvrir le tri fusion (Merge Sort)

* [x] CSS :
  - [x] Comprendre le fonctionnement de Flexbox
    - [x] Faire le parcours Flexbox Froggy (https://flexboxfroggy.com/#fr)
  - [x] Comprendre le fonctionnement de CSS Grid
    - [x] Faire le parcours Grid Garden (https://cssgridgarden.com/#fr)
