Ordres de travail sur les PMV
==============================
La table des OT archivés contient 1300 lignes avec la mention 'PMV' dans la description de l'équipement.

40 équipements présents dans cette table, correspondant à environ 140 OT ne sont pas présents dans la tables CosWin des équipements.
En examinant des exemples, on constate que ces équipements correspondent pour une partie à des PMV qui ont été remplacés 
car la table des équipements contient un PMV *Full Matrice* situé au même endroit.
Cela semble vouloir dire que les équipements remplacés ne sont pas concervés dans la table des équipements. 
Ils auraient pu l'être avec une valeur du champ Etat telle que *DECONF* ou  *RESERV*.

Dans l'autre sens, 70 PMV de la tables CosWin des équipements n'apparaissent pas dans la table des OT.
Dans certains cas, il s'agit de PMV présents sur le réseau d'un autre exploitant (BP, Cofiroute, SANEF).
Leur absence peut également signifier qu'ils n'ont pas fait l'objet d'une maintenance enregistée dans CosWIn pendant la durée du marché.

Le tableau ci-dessous fournit quelques exemples de ces PMV invisibles dans la table des OT.

.. csv-table::
   :header: Identifiant,Axe,Description
   :widths: 10, 10, 80
   :width: 90%

   E60.676H,N118NORD,PMVD Full Matrice sur N118 Y 04+0920
   E60.284S,N118NORD,"PMVHA sur D57 W à Vélizy-Villacoublay (N118, Ech n°3)"
   E60.723N,N118SUD,PMVD Full Matrice sur N118 Y 1+0370
   E60.724P,N118SUD,PMVS Full Matrice sur N118 I 05+0770
   E60.722M,N118SUD,PMVD Full Matrice sur N118 W 1+0370
   E60.731X,N184NORD,PMVD Full Matrice sur N184 E 11+0340
   E60.391U,N186,PMVHA sur D986 La Courneuve
   E60.214J,N6SUD,"PMVD sur N6 Y 10+0830 à Tigery (N104, Ech n°26)"
   E60.646W,N7,PMV Info sur N7 Y 02+0550 - Tunnel d’Orly
   E60.643T,N7,PMV Picto sur N7 W 03+0970 - Présignal Tunnel d’Orly

Nombre d'OT par entité et par type
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Le tableau suivant présente les nombres d'OT par entité et par type.

.. csv-table::
   :header: Entité, Curatif,Préventif
   :widths: 50, 20, 20
   :width: 90%

   AGER_EST,207,381
   AGER_NORD,78,66
   AGER_OUEST_B,137,24
   AGER_OUEST_N,88,131
   AGER_SUD,88,73







