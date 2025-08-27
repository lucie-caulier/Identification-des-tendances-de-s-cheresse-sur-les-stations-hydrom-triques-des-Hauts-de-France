## rapports_identification_tend_sech_HdF

# Objectif
Ce projet permet,  grâce à Rmarkdown,  de créer des rapports automatisés de l'identification des tendances de sécheresse par département des Hauts-de-France. Les analyses sont menées à partir des débits influencés récupérés sur Naiade via l'API Hub'eau. 

# Arborescence du projet

**assets**
Un document world servant de modèle pour le knit sous world. R recopie sa mise en page. 

**function**
Deux fichier R, chargés dans le programme principal, et contenant les fonctions dont nous avons besoin.

**output**
Un sous-dossiers geopackage tendance, contenant tous les geopackage de tendance durée de sécheresse et vcn10 pour chaque département des Hauts-de-France. Ainsi, ils peuvent être réutilisés pour créer des cartes sur QGIS.
Deux sous-dossiers avec les premières versions des rapports. 
Le excell VCN.

**script**
Peut contenir des dossiers geopackage, car lancer les chunks de création de geopackage dans le programme principal les fait automatiquement enregistrer dans ce dossier.
Le dossier Rmarkdown principal, contenant les scrips et les textes à l'origine des rapports automatisés. 

