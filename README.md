## 🔍 Machine Learning non supervisé — Clustering

Ce dépôt contient un notebook consacré au clustering, c’est-à-dire à l’apprentissage non supervisé visant à structurer des données sans variable cible.

L’objectif est méthodologique : comprendre, comparer et interpréter différentes approches de segmentation, plutôt que produire un clustering “magique” sans justification.

### 📌 Notebook — Clustering (clustering.ipynb)
#### 🎯 Objectif

Explorer et appliquer des méthodes de regroupement non supervisé afin d’identifier des structures latentes dans les données.

Le notebook met l’accent sur :

la préparation des données,

le choix raisonné des méthodes,

l’interprétation des résultats,

et les limites inhérentes au clustering.

#### 🔧 Étapes principales
1️⃣ Préparation des données

Sélection des variables pertinentes

Standardisation / normalisation lorsque nécessaire

Vérification des ordres de grandeur

👉 Étape essentielle en clustering : les distances dépendent directement de l’échelle.

2️⃣ Méthodes de clustering

Selon le contenu exact du notebook, on retrouve typiquement :

K-means

(éventuellement) clustering hiérarchique

comparaison de plusieurs valeurs de k

L’accent est mis sur la logique du modèle, pas sur l’automatisation aveugle.

3️⃣ Choix du nombre de clusters

Méthodes de type elbow

Indices de qualité (inertie, silhouette, etc.)

Discussion sur l’arbitraire du choix de k

👉 Le notebook rappelle qu’en non supervisé, il n’existe pas de vérité terrain.

4️⃣ Analyse et interprétation

Description des clusters obtenus

Comparaison des profils

Lecture métier / statistique des groupes

👉 Le clustering n’a de valeur que s’il est interprétable.

#### 📊 Ce que montre ce notebook

Une compréhension claire du non supervisé

Les limites du clustering (stabilité, dépendance aux choix initiaux)


