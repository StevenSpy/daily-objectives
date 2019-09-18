# Objectifs journaliers

## Lundi 16/09/2019

- [ ] Javascript :

  - [x] Découvrir le `DOM` :

    - [x] Comprendre la différence entre `DOM`, `CSSOM` et `BOM` (https://javascript.info/browser-environment)

    - [x] Comprendre la différence entre les 3 types de `nodes` dans le `DOM` (https://javascript.info/dom-nodes)

    - [x] Comprendre la navigation du DOM (https://javascript.info/dom-navigation) :
      - [x] Comprendre la différence entre les `Child Nodes` et les `Descendants`
      - [x] Comprendre la différence entre une `collection` et un `array`
      - [x] Comprendre la différence entre un `element` et un `node`
      - [x] Bien comprendre à quoi correspond :
        - [x] `parentElement`
        - [x] `children`
        - [x] `firstElementChild`
        - [x] `lastElementChild`
        - [x] `previousElementSibling`
        - [x] `nextElementSibling`
        - [x] `parentNode`
        - [x] `childNodes`
        - [x] `firstChild`
        - [x] `lastChild`
        - [x] `previousSibling`
        - [x] `nextSibling`
    - [x] Faire les exercices

      ## Exercice 1 :

      Pour le div : `document.body.firstElementChild`
      Pour le ul : `document.body.children[1]`
      Pour le deuxième li : `document.body.lastElementChild.lastElementChild`

      ## Exercice 2 :

      Yes / No

      ## Exercice 3 :

      ```
      <script>
      let table = document.body.firstElementChild;
      for (let i = 0; i < table.rows.length; i++){
      let tableRows = table.rows[i];
      tableRows.cells[i].style.backgroundColor = 'red';
      }
      </script>
      ```

* Codewars :
  - [x] Thinkful - String Drills: Repeater (https://www.codewars.com/kata/585a1a227cb58d8d740001c3)
  - [x] Remove First and Last Character Part Two (https://www.codewars.com/kata/570597e258b58f6edc00230d)
