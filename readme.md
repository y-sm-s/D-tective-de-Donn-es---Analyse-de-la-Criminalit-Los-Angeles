[# Projet 5 : Détective de Données - Analyse de la Criminalité à Los Angeles](https://github.com/y-sm-s/D-tective-de-Donn-es---Analyse-de-la-Criminalit-Los-Angeles/blob/main/Analyse%20de%20la%20Criminalite%20a%20Los%20Angeles.ipynb)

## Description  
Ce projet a pour objectif d'analyser les données criminelles à Los Angeles, Californie, afin d'aider le Département de Police de Los Angeles (LAPD) à allouer de manière optimale ses ressources pour protéger les citoyens de la ville. À travers l'exploration du fichier `crimes.csv`, nous cherchons à identifier des tendances et des informations clés sur la criminalité dans la région.

## Contexte  
Los Angeles, Californie. La Cité des Anges. Tinseltown. La Capitale du Divertissement du Monde ! Connue pour son climat chaud, ses palmiers, sa vaste côte et Hollywood, Los Angeles fait face à des défis en matière de sécurité, notamment un volume important de criminalité. Nous avons été sollicités pour analyser les données criminelles afin d'identifier des schémas de comportement criminel et ainsi aider la LAPD à allouer efficacement ses ressources.

## Données  
Le fichier utilisé dans ce projet :
- `crimes.csv` : Contient des informations sur les crimes commis à Los Angeles, incluant les dates, heures, types de crimes, zones géographiques et données sur les victimes.

## Questions de Recherche  
Les questions auxquelles ce projet vise à répondre sont les suivantes :
1. Quelle heure présente la plus haute fréquence de crimes ?
2. Quelle zone présente la plus grande fréquence de crimes nocturnes (crimes commis entre 22h00 et 03h59) ?
3. Identifier le nombre de crimes commis contre des victimes de différents groupes d'âge.

## Méthodologie  
Voici les étapes suivies pour réaliser cette analyse :

1. **Nettoyage des Données**  
   - Chargement du jeu de données et conversion des colonnes nécessaires.
   - Application de la méthode IQR pour détecter et éliminer les valeurs aberrantes dans les heures de crime.

2. **Analyse des Crimes par Heure**  
   - Catégorisation des crimes en fonction de leur type et analyse de la fréquence des crimes par heure.

3. **Analyse des Crimes Nocturnes**  
   - Filtrage des crimes commis entre 22h00 et 03h59, puis analyse des zones les plus touchées.

4. **Analyse des Âges des Victimes**  
   - Création de catégories d'âge et calcul de la fréquence des crimes selon ces catégories.

## Résultats  
Voici les résultats clés de l'analyse :
- **Heure de Pic de Criminalité** : La fréquence des crimes est la plus élevée à 12h00.
- **Zone avec le Plus de Crimes Nocturnes** : La zone avec le plus de crimes nocturnes est Central.
- **Fréquence des Crimes par Groupe d'Âge** : Une analyse détaillée des âges des victimes a été réalisée.
