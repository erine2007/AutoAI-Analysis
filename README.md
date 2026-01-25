# AutoAI-Analysis
## Objectif du POC

Ce POC vise à démontrer la valeur de l’IA et du NLP dans l’analyse automatique
de retours clients et de réclamations SAV dans le secteur automobile.

## Questions métier

**1. "Quels problèmes techniques reviennent le plus souvent ?"**

**Analyses à faire :**

- Extraction de mots-clés/n-grams fréquents
- Comptage par catégorie de problème
- Topic modeling pour découvrir des thèmes

**2. "Quels thèmes génèrent le plus de plaintes ?"**

**Analyses à faire :**

- Classification par thème (si catégories existent) ou clustering
- Calcul de distribution par thème
- Analyse de sentiment par thème

**3. "Quels problèmes sont en augmentation ?"**

**Analyses à faire :**

- Calcul de tendances temporelles (régression, taux de croissance)
- Détection d'anomalies (pics inhabituels)
- Comparaison période N vs N-1

**4. "Les avis clients confirment-ils les problèmes SAV ?"**

**Analyses à faire :**

- Cross-matching entre sources (avis vs tickets SAV)
- Analyse de cohérence (même problème mentionné ?)
- Détection d'incohérences

**5. "Peut-on détecter des signaux faibles qualité ?"**

**Analyses à faire :**

- Détection d'anomalies statistiques (Z-score, IQR)
- Identification de patterns rares mais graves
- Corrélations inhabituelles

## Valeur apportée par l’IA

L’IA permet d’automatiser l’analyse de données textuelles hétérogènes,
de regrouper les problématiques similaires et de fournir des recommandations/synthèses
exploitables aux équipes métier.

## Outils utilisés
- Google Cloud Platform (GCP): pour la partie cloud et stockage de données
- Databricks
- NLP
