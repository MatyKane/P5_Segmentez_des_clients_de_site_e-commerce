## 📊 Visualisation complète des notebooks

⚠️ Certains notebooks Jupyter sont trop volumineux pour être affichés directement par GitHub.

👉 Les versions **HTML (avec tous les résultats et graphiques)** sont disponibles ici :

- 🔹 Deuxième partie – Segmentation client :  
  👉 [Voir le notebook HTML](./PROJET%205_DEUXIEME%20PARTIE%20_Segmentez%20des%20clients%20d'un%20site%20e-commerce.html)

- 🔹 Troisième partie – Segmentation client :  
  👉 [Voir le notebook HTML](./PROJET%205_TROISIEME%20PARTIE%20_Segmentez%20des%20clients%20d'un%20site%20e-commerce.html)
  
  ***
  **Contexte**

Nous sommes consultant pour Olist, une plateforme de e-commerce brésilienne qui propose une solution de vente sur les marketplaces en ligne.

Notre rôle est d’accompagner Olist dans leur projet de monter une équipe Data et leur premier cas d’usage Data Science autour de la segmentation client.

SOURCE DES DONNEES: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data

***

`Objectifs :`

Notre objectif est le ciblage marketing des clients, ce qui implique une segmentation client.

Notre mission principale est de :

    Créer une segmentation client pour aider l’équipe Marketing à mieux cibler les campagnes.
    Analyser la stabilité des segments pour proposer une fréquence de mise à jour.
    Respecter les standards (PEP8) et fournir des insights exploitables.

***

**Étapes de réalisation**

1. Implémentation des requêtes SQL
Requêtes SQL (via WITH AS) fournies par Fernanda (Customer Experience)
    
    Liste de requêtes SQL pour le dashboard :

    ● En excluant les commandes annulées, quelles sont les commandes récentes de moins de 3 mois que les clients ont reçues avec au moins 3 jours de retard ?

    ● Qui sont les vendeurs ayant généré un chiffre d'affaires de plus de 100 000 Real sur des commandes livrées via Olist ?

    ● Qui sont les nouveaux vendeurs (moins de 3 mois d'ancienneté) qui sont déjà très engagés avec la plateforme (ayant déjà vendu plus de 30 produits) ?

    ● Question : Quels sont les 5 codes postaux, enregistrant plus de 30 reviews, avec le pire review score moyen sur les 12 derniers mois ?

2. Agrégation des données sur l’historique client
Vérification des jointures et cohérence des résultats

3. Feature Engineering
Création de variables comportementales :
RFM (Récence, Fréquence, Montant)
Satisfaction client
Typologie des produits achetés
Normalisation, encodage, et structuration des données

4. Modélisation par clustering
Test des méthodes :
k-means
Méthode du coude & silhouette score pour déterminer le nombre de clusters
Analyse et caractérisation des segments
Sélection du modèle optimal selon la qualité des clusters et la pertinence métier

5. Simulation de stabilité (maintenance)
Calcul de l’ARI (Adjusted Rand Index) sur plusieurs échantillons temporels
Évaluation de la stabilité des clusters dans le temps
Recommandation sur la fréquence de mise à jour de la segmentation

6. Présentation des résultats
Présentation visuelle des segments identifiés
Support PowerPoint à destination de l’équipe Marketing

***

**Compétences mobilisées**

    Requêtage SQL complexe (jointures, agrégations, CTE)
    
    Création de variables comportementales à fort potentiel marketing
    
    Segmentation client par clustering non supervisé
    
    Analyse de stabilité avec ARI

***

📬 Contact

Nom : Maty KANE

Email : matymbaye09@live.fr

GitHub : github.com/MatyKane

**Projet réalisé dans le cadre du parcours Data Scientist – OpenClassrooms.**