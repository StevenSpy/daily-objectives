# Objectifs journaliers

## lundi 30/09/2019

### Javascript :

- [x] Comprendre la `recursion` et le `stack` en Javascript (https://javascript.info/recursion)

  - [x] Faire les exercices

  ### Exercice 1 :

  function sumTo(n){
  let sum = 0;
  for (let i = 0; i < n; i++ ){
  sum += i;
  }
  return sum;
  }

  function sumTo(n){
  if (n == 1){
  return 1;
  }
  return n + sumTo (n -1);
  }

  function sumTo(n){
  return n ? (n+1) / 2;
  }

  ### Exercice 2 :

  function factorial(n){
  return (n!=1) ? n ? factiorial (n-1) : 1;
  }

  ### Exercice 3 :

  function fibanatie(n){
  return n <= 1 ? n : fibanatie(n-1) + fibanatie(n-2);
  }

  Ma version longue

  function fib(n) {
  let a = 1;
  let b = 1;
  for (let i = 3; i <= n; i++) {
  let c = a + b;
  a = b;
  b = c;
  }
  return b;
  }

### Frameworks JS :

- [ ] Découvrir ce que sont les frameworks et leur utilité (recherche personnelle)

- [ ] Comprendre l'utilité des frameworks JS frontend (recherche en groupe)

- [ ] Comprendre la différence entre un framework et une librairie

- [ ] Découvrir Vue JS (https://fr.vuejs.org/v2/guide/)

- [ ] Installer `Vue CLI` (https://cli.vuejs.org/)
- [ ] Créer ses premiers projets (répétitions créations / suppression, au moins une dizaine de fois)
