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

    ````
    function aclean (arr){
    let map = new Map ()
    for (let words of arr){
    let wordsInArr = words.toLowerCase().split('').sort().join('');
    map.set(wordsInArr, words);
    }
    return Array.from(map.values());
    }```
    ````

  ### Exerice 3 :

  Cela ne fonctionne pas car map ne retourne pas un Array et push est une méthode propre aux Array !

  Il faut donc concertir le map en Array : `let arr = Array.From(map.keys())`

* [ ] DOM :

  - [x] Comprendre le `Bubbling` et le `Capturing` (https://javascript.info/bubbling-and-capturing)

  - [x] Comprendre la délégation d'évènements (https://javascript.info/event-delegation)

    - [ ] Faire les exercices

    ### Exercice 1 :

    ```
    container.onclick = function(event){
      if(event.target.className != 'remove-button')return;

      let pane = event.target.closest ('.pane');
      pane.remove();
    };
    ```

    ### Exercice 2 :

    ```
      <script>

    for (let li of tree.querySelectorAll('li')) {
      let span = document.createElement('span');
      li.prepend(span);
      span.append(span.nextSibling);
    }
    ```

  tree.onclick = function(event) {

      if (event.target.tagName != 'SPAN') {
        return;
      }

      let container = event.target.parentNode.querySelector('ul');
      if (!container) return;

  container.hidden = !container.hidden;
  }
  </script>```

### Exercice 3 :
