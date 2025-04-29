Ce projet porte sur un fichier Excel contenant les informations de 1 000 employés d'une banque.
Les objectifs du projet sont les suivants :
1 - Établir la connexion à une source de données et effectuer des modifications sur les données.

2 - Apprendre à manipuler l'interface de Tableau Desktop et comprendre l'utilité de certaines fonctionnalités importantes.

3 - Réaliser des calculs statistiques, visualiser les données, filtrer les données, créer des champs calculés, représenter les données sur des cartes (format géographique), et créer des hiérarchies.

4 - Créer un tableau de bord.



1 - Établir la connexion à une source de données et effectuer des modifications sur les données

On commence par créer une connexion dans Tableau avec le fichier Excel.
Dans l'onglet Source de données, on modifie la représentation des données du champ Sexe (m et f) en utilisant des alias pour afficher Homme et Femme.
Ensuite, on accède à la feuille de calcul (Feuille 1) qui avait déjà été créée en cliquant dessus.


2 - Apprendre à manipuler l'interface de Tableau Desktop et comprendre l'utilité de certaines fonctionnalités importantes

Dans la feuille de calcul, à gauche, on retrouve les champs issus de la source de données, désormais répartis en deux groupes : dimensions et mesures.
Les mesures concernent des données sur lesquelles on peut effectuer des opérations mathématiques : somme, moyenne, écart-type, etc.
Les dimensions permettent de décrire ou de catégoriser les mesures.
Il est possible de convertir une mesure en dimension et inversement selon les besoins d'analyse.
En haut de l'interface, on distingue trois éléments principaux dans Tableau :

- Feuilles de calcul : pour réaliser les analyses.

- Tableaux de bord : pour regrouper différentes feuilles de calcul et présenter des informations clés aux gestionnaires, administrateurs ou décideurs.

- Histoires : pour présenter dynamiquement les analyses, avec possibilité d'explorer les différentes feuilles et d'appliquer des filtres en direct.

Dans le coin supérieur droit, l'option "Montrer moi" permet de sélectionner des styles de visualisation prédéfinis pour représenter élégamment nos données dans les feuilles de calcul et tableaux de bord.

3 - Effectuer des calculs statistiques, visualiser les données, filtrer les données, créer des champs calculés, représenter des données sur des cartes (format géographique), créer des hiérarchies

3.1 - On calcule la moyenne d'âge par sexe

- On calcule la moyenne d’âge en faisant attention à bien passer de l’agrégation "somme" à "moyenne".
- On représente ce calcul sous forme graphique (par exemple un graphique à barres), on affiche les étiquettes de valeur, et on différencie les sexes par des couleurs.
- On modifie le titre du graphique et on renomme la feuille de calcul en Moyenne d'âge par sexe.

3.2 - On calcule la moyenne d’âge par catégorie d’emploi et par sexe

- On duplique la feuille précédente.
- n fait attention à respecter l’ordre entre sexe et catégorie d’emploi comme indiqué dans la consigne.
- On représente les données sous forme d’histogramme en ajoutant les étiquettes de valeur pour une meilleure lisibilité.

3.3 - On calcule la moyenne des salaires actuels par sexe
- On crée une nouvelle feuille de calcul.
- On calcule la moyenne des salaires actuels par sexe (en veillant à bien choisir "moyenne" comme agrégation).
- On choisit un histogramme pour représenter ce calcul, on ajoute les étiquettes de valeur, et on remarque une différence d’environ 20 000 $ entre les salaires des hommes et des femmes.
- On renomme la feuille de calcul et le titre du graphique prend ce nouveau nom par défaut.

3.4 - On calcule la moyenne des salaires actuels par catégorie d’emploi et par sexe

- On duplique la feuille précédente.
- On ajoute le champ catégorie d’emploi en respectant bien l’ordre entre la catégorie et le sexe, toujours selon la consigne.

3.5 - On calcule la moyenne des salaires actuels par catégorie d’emploi, par sexe et par nombre d’années de formation

- On duplique la feuille précédente.
- On ajoute le champ nombre d’années de formation, qui est une mesure.
- On duplique ce champ et on convertit la copie en dimension. Elle apparaît alors dans la section dimensions.
- On l’ajoute au graphique.
- Pour améliorer la lisibilité, on regroupe les années en trois catégories : moins de 15 ans, entre 15 et 20 ans, et 20 ans et plus.

3.6 - On montre qu’on peut aussi faire des synthèses avec des dimensions

- On fait un exemple où on cherche le nombre d’employés par code postal en utilisant deux variables de type dimension.
- On représente le tableau résumé sous forme d’histogramme, et on filtre les totaux par sexe.

3.7 - On filtre les données dans Tableau

- On représente l’histogramme des salaires actuels moyens par catégorie d’emploi et par sexe, avec les étiquettes de valeur.
- On ajoute ensuite des filtres pour le sexe, la minorité visible (O/N), et la catégorie d’emploi.
- On positionne les filtres à droite de l’écran pour pouvoir faire une sélection simple, multiple, ou combinée.
- Remarque : même si la variable "minorité visible O/N" n’apparaît pas dans le graphique, on peut quand même l’utiliser comme filtre, elle à bien sur des effets sur le graphique !

3.8 - On ajoute des champs calculés

- On crée un champ calculé appelé Différence Salaires, qui représente l’écart entre la masse salariale actuelle et celle d’avant.
- On crée aussi un champ calculé appelé Salaire ajusté, dans lequel on applique une augmentation de 5 % pour ceux qui ont eu une évaluation très satisfaisante, 3 % pour ceux ayant une évaluation satisfaisante, et aucune augmentation pour les autres.

3.9 - On représente des données sur une carte (ou en format géographique)

- On duplique le champ code postal.
- On lui attribue un rôle géographique de type "code postal", puis on s’assure de définir le pays comme Canada (CA) pour une visualisation correcte.
- On choisit une représentation de type surface, et on applique une mise en couleur en dégradé rouge-vert divergent pour illustrer les moyennes de salaires.
- On ajoute aussi le nombre de personnes par code postal sur la carte.

4 - Créer un tableau de bord

Dans cette dernière étape, on crée un tableau de bord en intégrant les résultats obtenus dans les différentes feuilles de calcul précédentes. On regroupe ainsi les visualisations les plus pertinentes pour avoir une vue d’ensemble claire et efficace des données.
