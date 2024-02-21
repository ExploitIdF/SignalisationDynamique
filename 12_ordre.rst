Ordres de travail
===================
.. toctree::
   :hidden:
   :maxdepth: 3

   122_OTPMV
   123_OTCAC
   124_OTSAV

CosWin présente 2 tables différentes sur les **Ordres de travail** : les *OT en cours* et les *OT archivés*. 
Les champs des 2 tables ne sont pas les mêmes. La table des OT en cours comporte des champs permettant de faire le lien avec Sucombe (Prestation et Bon de commande) qui ne sont pas dans la table des OT archivés.

En février 2024, pour la signalisation dynamique, il y a 380 lignes dans la table des *OT en cours* et 2240 lignes dans la table des *OT archivés*.

Pour les analyses de données, la table  des *OT archivés* est la plus pertinente.
Les dates des OT remontent à 2020 mais ce n'est qu'à partir de 2021 que les nombres d'OT archivés sont significatifs.

Les ordres de travail comportent un champ *Equipement* qui prend 860 valeurs différentes donc 70 sont absentes de la 
:doc:`table des équipements de CosWin<11_equipement>`. **La raison de cette absence appelle une explication.**

OT Père ou Fils
^^^^^^^^^^^^^^^^
On observe que certains OT ont une valeur renseignée du champ *OT_P*. On dira qu'ils sont des OT Fils et qu'ils ont un père.
Les OT qui apparaissent dans le champ OT_P d'un autre OT seront désignés des OT pères.
Les OT qui ne sont ni père ni fils seront qualifiées d'isolées.

On constate que le champ OT_P prend 111 valeurs différentes mais 35 de ces valeurs ne se retrouvent pas dans les numéros d'OT de la table.
Seulement 76 OT père sont présentes dans la table.

1900 OT sont des OT Fils et 250 OT sont des OT isolées.














