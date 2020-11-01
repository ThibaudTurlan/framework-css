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

-------
## Navbar
> Les barres de navigation sont fluid par défaut, ne nécessite que une stucture d'une liste classique

**Option de couleur** 

* **.navbar-white**
* **.navbar-dark**

        <div class="navbar-white">
            <nav>
                <ul>
                    <li><a href="#">maison</a></li>
                    <li><a href="#">niche</a></li>
                    <li><a href="#">garage</a></li>
                    <li><a href="#">bistrot</a></li>
                </ul>
            </nav>
        </div>

## Les Boutons
> La classe `.btn` est conçues pour être utilisées avec la balise  `<button>`. Vous pouvez également utiliser cette classe sur des balise `<a>`.

    <a class="btn btn-primary" href="#" role="button">Link</a>
    <button class="btn btn-primary" type="submit">Button</button>
----
**bouton outline** 
**btn-outline**
**Exemple** 
    `<button class="btn-outline">button</button>`
---- 
**les tailles bouton**

* **.btn-xl**
* **.btn-s** 

**Exemple**

    <button class="btn btn-s">button</button>
    <button class="btn btn-xl">button</button>
----
## Les Ombres

**.shadow-s**

## Alert

**.alert**


