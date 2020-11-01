# Mini Framework CSS
Framewok CSS by Thib

## Options de grille

|         | Mobile | tablet | desktop | large desktop  |
|---      |:-:     |:-:     |:-:      |:-:     |
| largeur | auto   | 601px  | 993px   | 1201px |
| Préfixe | s      | m      | l       | xl     |
| colonnes |  12   |        |         |        |
| gutter |  20px   |        |         |        |
-------

**Exemple**

    <div class="container">
        <div class="row">
            <div class="col m6">text</div>
            <div class="col m6">text</div>
            <div class="col m12">text</div>
        </div>
    </div>

## Les Colonnes de Décalages

**offset**
> Déplacez les colonnes vers la droite en utilisant les `.offset-m-*colonnes`. Ces classes augmentent la marge gauche de *colonne

* **offset-s**
* **offset-m**
* **offset-l**
* **offset-xl**

**Exemple**

    <div class="row">
        <div class="col offset-m-2">.col m-4</div>
        <div class="col m-8">.col m-4 .ml-auto</div>
    </div>


