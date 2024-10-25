# Etude_Statistique_Delinquance
Etude statistique sur la délinquance en France (régions, départements, villes)

Cette étude se base sur des bases statistiques communales, départementales et régionales de la délinquance enregistrée par la police et la gendarmerie nationale.
Les données diffusées sont limitées aux communes pour lesquelles plus de 5 faits ont été enregistrés pendant 3 années successives.  

Les données sont issues du site data.gouv.fr et sont disponibles sous l'url suivant: https://www.data.gouv.fr/fr/datasets/bases-statistiques-communale-departementale-et-regionale-de-la-delinquance-enregistree-par-la-police-et-la-gendarmerie-nationales/#/resources

Les données de cette étude ont été récupérées le 30 septembre 2024. 

BRAINSTORMING
Idées de ce qui peut être étudié : 
- Pour une ville / département / région donnée il peut être intéressant de comparer les proportions de crimes et délits (exemple : on va chercher à voir avec un graphique les proportions de vols avec armes, meurtres, etc. dans un diagramme circulaire)
- Pour une ville donnée, il peut être intéressant de mesurer les crimes et délits par rapport au reste de la France (histogramme ou barplot à voir). L'idée est de plus tard faire un streamlit pour que l'utilisateur puisse sélectionner de manière dynamique
- Classement des régions / départements / villes les plus dangereuses en fonction du type de crime / délit 
- Est-ce que les villes les plus dangereuses se trouvent dans les départements les plus dangeureux ?
- Il serait intéressant d'avoir une carte permettant de visualiser la dangerosité / le volume de crimes et délits (soit par des points de différentes tailles et couleurs soit par des applats de couleur)
- Evolution de la délinquance au fil du temps : par type de crime et délits (donc par dangerosité)
- Est-ce qu'il y a une évolution de la délinquance ? 

Un autre objectif sous-jacent pourra être d'étudier l'évolution de la délinquance par type de crime et délit au fil du temps. 
Il serait intéressant d'effectuer des prédictions sur leurs évolutions grâce à différents algorithmes de machine-learning si aplicable 


Etudes des liens :
  En préambule, il faudra récupérer le parti du maire de la ville
  - Est-ce qu'il y a un lien / corrélation entre le parti du maire de la ville et la dangerosité de la ville ?
  L'idée sera de compléter les datasets par d'autres disponibles sur le site data.gouv.fr

Ressources : 
Tableau de correspondance anciennes - nouvelles régions 