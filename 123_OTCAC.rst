Ordres de travail des CAC
===========================
La table des ordre de travail comporte 232 lignes dont l'équipement appartient à la famille 'CAC' selon la table des équipements.

Les équipements dans la table ci-dessous ne font pas l'objet d'un OT.

.. csv-table::
   :header: Tatouage, Axe,Description
   :widths: 10, 10, 80
   :width: 90%

   E21.002D,A13,CAC-TYPE C,Accès A13 Y 8+0000 depuis D182 (Vaucresson)
   E21.083Y,A86NORD,CAC-TYPE C,Accès A86 I 14+0400 depuis D24/D30 (Saint Denis)
   E21.084A,A86NORD,CAC-TYPE A,Accès A86 I 3+0500 depuis D27 (Aubervilliers)
   E21.127C,A86EST,CAC-TYPE C,Virtuel Accès A86 E 37+0740 - Plateforme de Test Sirius-Ouest
   E21.128D,A86EST,CAC-TYPE C,Virtuel Accès A86 E 37+0740 - Plateforme de Test Sirius-Ouest
   E21.131G,A86EST,CAC-TYPE C,Virtuel Accès A86 E 37+0740 - Plateforme de Test Sirius-Est
   E21.132H,A86EST,CAC-TYPE C,Virtuel Accès A86 E 37+0740 - Plateforme de Test Sirius-Ouest


.. csv-table::
   :header: Equipement,Description,axeSens,Entité
   :widths: 10, 40, 20,20
   :width: 90%

   E21.000A,Accès A13 W 8+0000 depuis D182 (Vaucresson),A13W,AGER_OUEST_B
   E21.002D/B1G/R22P,Caisson tricolore (R22) du feux Gauche Bretelle1 du E21.002D,A13Y,AGER_OUEST_B
   E21.129E/B1D/FEUX,Feux de signalisation Droit Bretelle1 du E21.129E,A4Y,AGER_EST
   FORFAIT_CAC_OUEST_B,Code fictif pour forfait CAC Secteur Boulogne,X,AGER_OUEST_B
   FORFAIT_CAC_OUEST_N,Code fictif pour forfait CAC Secteur Nanterre,X,AGER_OUEST_N





Nombre d'OT par entité et par type
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Le tableau suivant présente les nombres d'OT par entité et par type.

.. csv-table::
   :header: Entité, Curatif,Préventif
   :widths: 50, 20, 20
   :width: 90%

    AGER_EST,40,75
    AGER_NORD,31,23
    AGER_OUEST_B,7,3
    AGER_OUEST_N,12,6
    AGER_SUD,16,15

Le PCTT Est est, selon COsWin, à l'origine de plus de la moitié des préventifs et de plus du tiers des curatifs.


