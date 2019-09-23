# Objectifs journaliers

## Lundi 23/09/2019

- [x] Javascript :

  - [x] Découvrir `Map` et `Set` (https://javascript.info/map-set)
        _ [x] Comprendre la principale différence entre les deux.
        _ [x] Faire les exercices

          ### Exercice 1 :

          ```
          function unique(arr) {

          return Array.from(new Set(arr));

    }```

    ### Exercice 2 :

    ```
    function aclean (arr){
    let map = new Map ()
    ```

  for (let words of arr){
  let obtain = words.toLowerCase().split('').sort().join('');
  map.set(obtain, words);
  }
  return Array.from(map.values());
  }```

  ### Exerice 3 :

  Cela ne fonctionne pas car map ne retourne pas un Array et push est une méthode propre aux Array !

* [ ] DOM :

  - [ ] Comprendre le `Bubbling` et le `Capturing` (https://javascript.info/bubbling-and-capturing)

  - [ ] Comprendre la délégation d'évènements (https://javascript.info/event-delegation)
    - [ ] Faire les exercices

```

```
