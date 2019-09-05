# Objectifs journaliers

## Mercredi 04/09/2019

- [ ] Javascript :

  - [x] Comprendre ce que sont les polyfills et leur utilité (https://javascript.info/polyfills)
    - [x] Comprendre la différence entre "transpilation" et "compilation"
    - [x] Comprendre l'utilité de Babel
  - [x] Découvrir les Objets en JS (https://javascript.info/object)

        - [x] Comprendre le principe de clé/valeur
        - [x] Comprendre la différence entre un objet et une variable
        - [x] Savoir itérer dans un objet
        - [x] Comprendre la copie par référence
        - [x] Savoir copier un objet (cloner)

        ###Exercice 1

        ```
        let user = {};
        user.name : "John";
        user.surname : "Smith";
        user.name : "Pete";
        delete user.name;
        ```

        ###Exercice 2

        ```
        let monObjet = {};

        function isEmpty(monObjet){
            for (let key in monObjet){
                return false;
            }

            return true;
        }

        ```

        ###Exercice 3

        Oui nous pouvons changer ou bien même ajouter du contenu dans un "const objet", cependant on ne peut pas changer le type de l'objet par exemple on ne peut pas faire ceci : ` const monObjet = {}; monObjet = "Yolo";`

        ###Exercice 4

        ```
        let salaries = {
            John: 100,
            Ann: 160,
            Pete: 130

    }

        let sum = 0;

        for (let key in salaries){
            sum +=salaries[key];
        }

        alert(sum);

        ```

* [ ] Algo :
  - [ ] Ecrire en pseudocode le Bubble Sort (création pure)
  - [ ] Faire valider son code par un "élève" qui joue le rôle de l'ordinateur
