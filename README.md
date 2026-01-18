# Analyse Exploratoire des Données (EDA) – Ventes de supermarché
### Objectif du projet
L’objectif de ce projet est de réaliser une Analyse Exploratoire des Données (EDA) sur un jeu de données de ventes d’un supermarché afin de :

- Comprendre la structure et la qualité des données

- Analyser le comportement des ventes

- Comparer les performances selon différentes catégories

- Identifier des valeurs atypiques (outliers)

- Extraire des insights utiles pour la prise de décision

Ce projet est réalisé dans un contexte de préparation à un stage en data / informatique / analytique.

### Description du dataset
- ID de facture : Identifiant unique pour chaque transaction.
- Succursale : L’emplacement de la succursale du supermarché (par exemple, Yangon, Naypyitaw, Mandalay).
- Ville : La ville dans laquelle se trouve le supermarché.
- Type de client : Indique si le client est un 'Membre' ou 'Normal'.
- Genre : Sexe du client.
- Gamme de produits : La catégorie du produit vendu (p. ex., Santé et beauté, Accessoires électroniques, Maison et style de vie).
- Prix unitaire : Prix par unité du produit.
- Quantité : Nombre d’articles achetés.
- Taxe 5% : Montant de la taxe calculée sur la transaction à un taux de 5%.
- Total : Montant total de la transaction y compris les taxes.
- Date : Date de la transaction.
- Heure : Heure de la transaction.
- Paiement : Méthode de paiement utilisée (par exemple, Cash, Ewallet, carte de crédit).
- COGS : Coût des marchandises vendues, représentant le coût brut des produits.
- Pourcentage de marge brute : Pourcentage fixe du bénéfice pour chaque vente (4,7619 %).
- Gross Income: Profit earned from the transaction.
- Rating: Customer satisfaction rating (out of 10).


### Préparation et nettoyage des données

Les étapes suivantes ont été réalisées :

- Conversion des colonnes de dates au format datetime

- Vérification des types de variables (numériques / catégorielles)

- Contrôle des valeurs manquantes

- Création de nouvelles variables utiles (mois, indicateur d’outlier)
 Analyse descriptive

### Calcul des statistiques descriptives (moyenne, somme, écart-type)

- Analyse du chiffre d’affaires global

- Étude de la dispersion des ventes

- Ces analyses permettent de mieux comprendre la distribution générale des ventes.

### Analyse par catégories

Plusieurs comparaisons ont été effectuées :

- Ventes par ville

- Ventes par ligne de produit

- Moyens de paiement les plus utilisés

- Quantité moyenne achetée selon le type de client

### Des visualisations adaptées (barplots, pie charts) ont été utilisées pour faciliter l’interprétation.

Détection des valeurs atypiques (Outliers)

La méthode de l’IQR (Interquartile Range) a été utilisée pour identifier les ventes anormalement élevées.

- Calcul des bornes inférieure et supérieure

- Identification des transactions dépassant la borne supérieure

- Création d’une colonne Outlier pour marquer ces observations

Ces ventes atypiques correspondent principalement à des montants très élevés mais restent plausibles dans un contexte commercial.

### Conclusions et insights

Les principaux enseignements de cette EDA sont :

- Certaines villes génèrent plus de chiffre d’affaires, indiquant des zones à fort potentiel

- Certaines lignes de produits dominent les ventes, ce qui peut guider les décisions marketing

- Les moyens de paiement ne sont pas utilisés de manière uniforme

- Les clients membres ont tendance à acheter légèrement plus en moyenne

- Les ventes atypiques représentent des transactions exceptionnelles mais légitimes

Ces insights peuvent aider à :

- Optimiser les stratégies commerciales

- Adapter les offres selon les clients

- Mieux comprendre les comportements d’achat
  
### Outils utilisés

- Python

- pandas

- matplotlib

- seaborn

- Jupyter Notebook

  
