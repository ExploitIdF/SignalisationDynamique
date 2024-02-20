Equipements dans CosWin
=========================  
.. toctree::
   :hidden:
   :maxdepth: 3

     112_PMV
     113_CAC
     114_SAV

CosWin contient une table des équipements dans laquelle les équipements dynamiques peuvent être identifiés par le champ ``Famille`` qui prend les valeurs : ``SAV, PMV & CAC``.

Champ Etat
""""""""""""
La table des équipements contient environ 3300 lignes dont  3100 pour lesquelles le champ ``Etat`` prend la valeur : ``EXPLOI``. 
Les autres valeurs du champ Etat sont :
* PROJET     105 (l'équipement n'est pas encore acquis)
* DECONF      42  ( ?)
* DEPPRO      21  (?)
* RESERV      11
* H_EXPL       2

La signification de ces valeurs reste à éclaircir, elle dépend parfois de la nature de l'équipement. 

La catégorie EXPLOI semble assez large, elle intègre même 4 CAC de la plateforme de test par exemple.
Dans la suite, on se limitera aux équipement dont l'Etat est EXPLOI.

Niveaux (Parent, Enfant, Isolés)
""""""""""""""""""""""""""""""""""
Il existe 2 niveaux d'équipements :

* les équipements parents dont le tatouage apparait dans le champ Parent d'un autre équipement
* les autres équipements qui ont un parent et que l'on appelle les enfants et 
les équipements isolés qui n'ont ni parent ni enfant

Il y donc 3 catégories : les 600 parents, les 2040 enfants et les 650 isolés.

On détail dans des feuilles séparés comment sont enregistrés dans CosWin :
* les `PMV<112_PMV>`
* les `CAC<113_CAC>`
* les `SAV<114_SAV>`

Présence des équipements dans la table des OT
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Les équipements qui font l'objet d'une intervention sont identifiés dans la table des OT 

* soit directement (leur tatouage est dans le champ Equipement de l'OT) 
* soit indirectement (le tatouage de leur parent est dans le champ Equipement de l'OT) 

On peut distinguer les effectifs selon les catégories d'équipements :

* La moitié (327/650) des isolés font l'objet d'un OT.
* 137/2040 enfants font directement l'objet d'un OT.
* 1370/2040 enfants font indirectement (via leur parent) l'objet d'un OT.
* 325/600 parents font l'objet d'un OT.




