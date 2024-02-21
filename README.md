# what-is-machine-learning

Veille scientifique introduisant aux notions essentielles à la compréhension et la découverte du machine learning.
---

## A. La science des données
En termes simples: c'est l'extraction d'informations exploitable à partir de données brutes. 

Elle consiste à faire l'extraction de grandes quantités de données brutes, à la fois structurées et non structurées, pour identifier des modèles et en extraire des informations exploitables. 

![image](https://github.com/marwan-rouissi/what-is-machine-learning/assets/115158061/9a778f9c-b6ec-4504-b49e-33c2d875130d)


Il s'agit d'un domaine interdisciplinaire et les fondements de la science des données comprennent les statistiques, l'inférence, l'informatique, l'analyse prédictive, le développement d'algorithmes d'apprentissage automatique (ML) et les nouvelles technologies pour obtenir des informations à partir du big data.

## B. L’apprentissage automatique et/ou l’apprentissage profond
- L'apprentissage automatique (ou Machine Learning en anglais) est une branche de l'intelligence artificielle (IA) qui consiste à développer des algorithmes capables d'apprendre à partir de données.   
Grâce à l'utilisation de méthodes statiques, des algorithmes sont entraînés à effectuer des classifications ou des prévisions, permettant ainsi la découverte des informations essentielles dans le cadre de projets d'exploration de données.   
C'est Arthur Samuel qui, dans le cadre de ses recherches sur le jeu de dames "Some studies in machine learning using the game of checkers", invente le terme "apprentissage automatique"(ML).

![image](https://github.com/marwan-rouissi/what-is-machine-learning/assets/115158061/8cebd4ea-1d24-454c-a00c-40e775d42b6c)


- L'apprentissage en profondeur (ou Deep Learning en anglais) est un sous-domaine des réseaux de neurones* qui, eux mêmes, sont un sous-domaine de l'apprentissage automatique.
L'apprentissage en profondeur peut:
    - s'appuyer sur des ensembles de données étiquetées (on parle alors d'apprentissage supervisé) pour alimenter son algorithme
    - ingérer des données non stucturées dans leur forme brute (textes, images, ...) afin de déterminer automatiquement l'ensemble des catactéristiques qui distinguent les différents catégories de données les unes des autres.


La différence principale différence entre les deux est la participation/implication humaine.
En effet, l'apprentissage automatique dépend davantage de l'intervention humaine pour apprendre.   
L'ensemble des caractéristiques pour comprendre les différences entre les entrées de données est determiné en amont par l'humain, ce qui nécessite généralement des données plus structurées pour apprendre.

*Réseaux de neurones: Les réseaux de neurones, ou réseaux de neurones artificiels, sont constitués de couches nodales contenant une couche d'entrée, une ou plusieurs couches cachées et une couche de sortie. Chaque nœud, ou neurone artificiel, se connecte à un autre et possède un poids et un seuil. Si la sortie d'un nœud est supérieure à la valeur de seuil spécifiée, ce nœud est activé et envoie des données à la couche suivante du réseau. Dans le cas contraire, aucune donnée n'est transmise à la couche suivante du réseau. « En profondeur » dans le terme « apprentissage en profondeur » fait simplement référence au nombre de couches d'un réseau de neurones. Un réseau de neurones composé de plus de trois couches (incluant les entrées et les sorties) peut être considéré comme un algorithme d'apprentissage en profondeur ou un réseau de neurones profonds. Un réseau de neurones qui ne comporte que deux ou trois couches est simplement un réseau de neurones de base.

## C. L’apprentissage supervisé,
L'apprentissage supervisé est une sous-catégorie de l'apprentissage automatique et de l'IA.   
Il se caractérise par l'utilisation d'ensembles de données étiquetées pour entraîner des algorithmes qui permettent de classer des données ou de prédire des résultats avec précision.   
Au fur et à mesure que les données en entrée sont introduites dans le modèle, celui-ci ajuste ses pondérations jusqu'à ce que le modèle soit correctement ajusté.   
C'est le processus de validation croisée.   

![image](https://github.com/marwan-rouissi/what-is-machine-learning/assets/115158061/79990a28-ffb6-4380-bc84-b2129ea5dfc3)


Avec l'apprentissage supervisé, les organisations peuvent résoudre divers problèmes du monde réel à grande échelle, comme la classification des courriers indésirables dans un dossier distinct de votre boîte de réception.

## D. L’apprentissage non supervisé,
L'apprentissage non supervisé est l'utilisation d'algorithmes d'apprentissage automatique pour analyser et regrouper des jeux de données non étiquetées.   
Ces algorithmes découvrent des modèles cachés ou des groupements de données sans nécessiter d'intervention humaine.   

Sa capacité à découvrir les similitudes et les différences d'informations en fait la solution idéale pour l'analyse d'exploration des données, les stratégies de vente croisée, la segmentation de la clientèle, la reconnaissance d'images et bien d'autres.

## La Classification
La classification a pour but de regrouper (partitionner, segmenter)  
n observations en un certain nombre de groupes ou de classes homogènes.   
Il existe deux principaux types de classification:

## - E. La classification supervisée
La classification supervisée (souvent appelée simplement classification) consiste à attribuer automatiquement une catégorie (ou une classe) à des données (données d'entrainement) dont on ne connaît pas la catégorie.   
 
    - on connaît déjà le nombre de groupes qui existent dans la population;
    - on connaît le groupe auquel appartient chaque observation de la population;
    - on veut classer les observations dans les bons groupes à partir de différentes variables.


Pour ce faire, un classifieur (algorithme de ML) est entrainé sur des données similaires ou très proches des données que l'on souhaite classer.  
supervisé = données classées en amont par l'humain.
## - F. La classification non supervisée
La classification non supervisée, à l'inverse, concerne ...

En contrepartie en classification non supervisée,

    - on ne connaît souvent pas le nombre de groupes qui existent dans la population;
    - on ne connaît pas le groupe auquel appartient chaque observation de la population;
    - on veut classer les observations dans des groupes homogènes à partir de différentes variables.

## G. La régression
En machine Learning, l'objectif d'un algorithme est de prédire un (ou des) labels. Lorsque ce label est continu, la tâche est appelé "régression".   

![image](https://github.com/marwan-rouissi/what-is-machine-learning/assets/115158061/6926bb6d-cdeb-497c-be12-b76dda2d66ef)


La régression est donc une tâche de ML dans laquelle le praticien doit utiliser les données d'entrées pour prédire une valeur numérique.   
Elle permet de trouver une relation mathématique pour déterminer une valeur en fonction des features d'un dataset.
## H. La validation croisée
La validation croisée (ou cross-validation en anglais) est une méthode statistique qui permet d'évaluer/de tester les performances d'un modèle prédictif de ML.   

![image](https://github.com/marwan-rouissi/what-is-machine-learning/assets/115158061/2b2cb4e0-68e5-445f-a6f5-66c46f729d45)


Généralement lorsque l'on parle de validation croisée, on fait référence à sa méthode la plus populaire : le K-Folds.

Les différentes méthodes:
- K-Folds:   
Mets à profit de toutes les données à disposition en les divisant en K parites égales (folds) sur lesquelles on entraîne et teste un modèle pendant K itérations.   
À chaque itération, le modèle est entrainé sur K-1 folds et est testé sur le fold restant.

![image](https://github.com/marwan-rouissi/what-is-machine-learning/assets/115158061/06dcfc3b-d5ac-4194-85bb-6034b9321b31)


- Train-Test Split:   
Décompose de manière aléatoire un ensemble de données.   
Ainsi, une partie servira à l'entrainement du modèle de ML tandis que l'autre permettra de le tester pour la validation.
En règle générale, 70% à 80% des données du dataset sont réservées à l'entraînement.   
Les 20% à 30% restant seront exploités pour le test de validation.


Bien qu'il en existe d'autres, ces methodes sont les plus courantes.


## I. Les données d’entraînement, les données de test et/ ou de validation
En apprentissage automatique, une tâche courante est l'étude et la construction d'algorithmes qui peuvent apprendre et faire des prédictions sur les données.   
Ces algorithmes fonctionnent en faisant des prédictions basées sur les données, en construisant un modèle mathématique à partir de données d'entrée.   
Ces données d'entrées sont généralement diviséess en plusieurs jeux de données :

- Les données d'entraînement :
Jeu d'exemples utilisés pour ajuster les paramètres du modèle.

- Les données de validation :
Jeu de données qui fournit une évaluation impartiale d'un ajustement de modèle sur le jeu d'entraînement et ainsi permettre de régler les hyperparamètres d'un classifeur*, c'est à dire son architecture (ex. les poids des connexions entre les neurones dans les réseaux de neurones artifficiels).
Ils peuvent être utilisés pour la régularisation par arrêt anticipé(arrêt de l'entraînement quand l'erreur sur le jeu de données de validation augmente).

- Les données de test :
Jeu de données utilisé pour fournir une évaluation impartiale d'un ajustement final du modèle sur le jeu de données d'apprentissage.   
Si les données de ce jeu n'ont jamais été utilisées dans l'apprentissage (ex; validation croisée), le jeu de données de test est également appelé "jeu de données d'exlusion".


*classifieur: algorithme utilisé en ML pour classer les dpnnées dans des catégories prédéfinies.

## J. Corrélation linéaire (de Pearson) entre deux variables

Le coefficient de corrélation de Pearson est défini en statistique comme la mesure de la force de la relation entre deux variables et leur association d'une avec l'autre.

En d'autres termes, le coefficient de corrélation de Pearson calcule l'effet du changement d'une variable lorsque l'autre variable change.

## K. Une fonction de coût

Une fonction de coût peut être une formule mathématique qui permet de déterminer comment les dépenses de production vont évoluer à différents niveaux de production.  

En d’autres termes, elle estime le coût total de production en fonction d’une quantité sélectionnée produite.



Une fonction de coût, en mathématiques et en économie, est une fonction qui attribue un coût à chaque action ou décision possible.   
En optimisation, la fonction de coût est souvent utilisée pour évaluer la performance d'un modèle ou d'un algorithme en mesurant l'écart entre les prédictions et les valeurs réelles.   
En économie, la fonction de coût est utilisée pour déterminer les coûts de production d'une entreprise en fonction des quantités de facteurs de production utilisées.   
En analyse de données, la fonction de coût est souvent minimisée lors de l'entraînement de modèles d'apprentissage automatique.


## L. La descente de gradient

Il s’agit d’un algorithme permettant de trouver le minimum d’une fonction.

### Sources :
- https://www.ibm.com/fr-fr/topics/data-science
- https://decouvrezplus.com/besoin-de-savoir-sur-science-des-donnees/
- https://www.ibm.com/fr-fr/topics/machine-learning
- https://kongakura.fr/article/Classification%20supervis%C3%A9e
- https://veroniquetremblay.github.io/analyse_de_donnees_et_apprentissage_statistique_en_R/classification-non-supervisee.html
- https://inside-machinelearning.com/regression/
- https://datascientest.com/cross-validation
- https://www.kevindegila.com/fr-blog/la-validation-croisee-en-machine-learning-tout-ce-quil-faut-savoir/
- https://fr.wikipedia.org/wiki/Jeux_d%27entrainement,_de_validation_et_de_test
- https://www.questionpro.com/blog/fr/coefficient-de-correlation-de-pearson/
- https://datascience.eu/fr/mathematiques-et-statistiques/quest-ce-quune-fonction-de-cout/
- https://www.charlesbordet.com/fr/gradient-descent/#
