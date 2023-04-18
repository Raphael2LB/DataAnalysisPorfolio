Bike sales analysis :

Cette analyse a pour vocation d’explorer de nouvelles pistes marketing pour une entreprise actrice de l’industrie du vélo. 
Pour ce faire, nous utiliserons le dataset « bike_buyers » provenant de https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx This is information pertaining to bike buyers from all over the world.

Compte tenu du type de données purement démographique à notre disposition, nous devrions être en mesure de dressé un « persona » qui permettra d’élaborer un premier socle utile à la prise de décision stratégique pour l’entreprise intéressée.

L’ensemble du projet a été mené sur Excel.
Le résultat final consiste en un dashboard dynamique filtrable par continent grâce à un segment. 
Pour consulter le dashboard dynamique, rendez-vous sur « Bike_Sales.xlsx » présent dans ce dossier.

![image](https://user-images.githubusercontent.com/130085381/232844588-38305eb6-4782-4f70-b3cd-bc9010efb951.png)

1/ NETTOAYGE :

La première étape de ce projet a consisté en un nettoyage du dataset.

-Suppression des doublons
-Transformation des colonnes « Marital status » et « gender » afin de montrer leurs signification complète plutôt que les initiales.
-Création d’une nouvelle colonne « Age Bracket » qui regroupe les âges en 3 groupes principaux, dans le but de faciliter la lecture des futurs graphiques.

2/ INVESTIGATIONS :

La seconde étape était la recherche d’informations intéressantes à mettre en évidence dans le dashboard final.

Premièrement, j’ai décidé de créer un bar chart qui montre la répartition des ventes de vélo selon le niveau d’étude des acheteurs. On constate que plus le niveau augmente, plus les individus achètent. Néanmoins, la tendance s’inverse lorsque les acheteurs ont un niveau « graduate ».

![image](https://user-images.githubusercontent.com/130085381/232845796-94a0cf39-ff99-4700-8e23-6a06eb104e95.png)

Ensuite, j’ai dressé un line chart qui montre la tendance d’achat de vélo selon les groupes d'âge suivants :
Young : 25-30 
Middle- age : 31-54
Old : 55+
On constate qu’indépendamment de la région, la plupart des acheteurs ont un âge intermédiaire.

![image](https://user-images.githubusercontent.com/130085381/232845597-f7a47efc-4562-4c3d-8c99-298862483abf.png)

 Ensuite j’ai décidé de créer deux Pie chart afin de visualiser la répartition d’acheteurs de vélo par statut marital d’une part, et par genre d’autre part. 
Il en ressort que sur l’ensemble des régions, il y a légèrement plus d’acheteurs seuls (52%) que d’acheteurs mariés. 
Et il y a parité entre hommes et femmes. 50/50.

![image](https://user-images.githubusercontent.com/130085381/232847499-b512f620-a5b0-4c53-9512-f9f105fb8e5d.png)
![image](https://user-images.githubusercontent.com/130085381/232847651-25239cfa-b108-4d8d-8a97-c2060193c709.png)

Ensuite, le paramètre des enfants me semblait intéressant à investiguer. Nous avons donc créer un histogramme afin de visualiser les achats de vélo selon le nombre d’enfants par foyer.
Le graphique est représenté avec une courbe de tendance indiquant qu’au niveau international la tendance est que plus il y a d’enfants au sein d’un foyer, moins il y a achat de vélo. Notons que les individus célibataires ont étés écartés afin de rendre le graphique viable.
Nous constatons que les individus mariés achètent lorsqu’ils ont entre 0 et 1 enfants, la tendance est la baisse à mesure que le nombre d’enfants par foyer augmente.
 
![image](https://user-images.githubusercontent.com/130085381/232847729-c57273da-09ba-4e3c-ba75-94fd0fcf9692.png)


Enfin, nous avons mis en lumière la distance domicile/travail parcourrue par les différents individus, la plupart font entre 0 et 1 Miles, la tendance est constante et moindre par la suite. 
 
![image](https://user-images.githubusercontent.com/130085381/232847766-20ff29de-711e-4e56-ae2a-d234a18166b5.png)

 
3/ CONCLUSIONS :

A l’issue de cette analyse, nous pouvons dresser une persona pour une entreprise de vente de vélo : le/la cadre marié(e) d’une grande ville avec un enfant.

![image](https://user-images.githubusercontent.com/130085381/232847789-9995f0b6-e973-4f7e-84ca-b814c4feb8a0.png)

Nous faisons cette conclusion suite à l’analyse des données internationales, en revanche, il n’est pas exclu que notre persona varie d’un continent à l’autre.
C’est pour cette raison que nous mettons à disposition un filtre par continent, afin de permettre l’affinage des investigations.
