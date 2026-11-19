# 23008729-aitbousalem-CI
# Prévision des exportations marocaines par produit et destination

## 1. Informations générales

- **Étudiante :** Israa Ait Bousalem
- **Code Apogée :** 23008729
- **Groupe :** G1
- **Établissement :** ENCG Settat
- **Filière :** Commerce International – S7
- **Sujet :** CI01 – Prévision des exportations marocaines

## 2. Problématique

Comment anticiper avec précision la valeur mensuelle des exportations marocaines selon la catégorie de produit (code SH) et le pays destinataire ?

## 3. Objectifs du projet

- Analyser l'évolution des exportations marocaines.
- Étudier les variations selon les produits et les destinations.
- Construire un modèle de prévision.
- Comparer les performances du modèle avec une méthode de référence.

## 4. Méthodologie Machine Learning

- **Type de tâche :** Régression quantitative.
- **Algorithme principal :** Ridge Regression (Algorithme 1).
- **Référence :** Persistance ou moyenne historique.
- **Métrique principale :** RMSE.
- **Objectif :** Obtenir une RMSE inférieure d'au moins 15 % à celle de la baseline sur le jeu de test final.

## 5. Structure du dépôt

- `data/raw/` : Données brutes.
- `docs/` : Documentation et consignes.
- `figures/` : Graphiques et visualisations.
- `notebooks/` : Notebook Jupyter.
- `presentation/` : Présentation finale.
- `rapport/` : Rapport PDF.
- `video/` : Vidéo de présentation.

## 6. Installation et reproduction

Installer les dépendances :

```bash
pip install -r requirements.txt
```

Ouvrir `notebooks/projet_CI01.ipynb` et exécuter les cellules dans l'ordre.

## 7. Déclaration d'utilisation de l'IA

Consulter `DECLARATION_IA.md` pour les informations relatives à l'utilisation des outils d'intelligence artificielle.
