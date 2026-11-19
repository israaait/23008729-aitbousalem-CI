# Machine Learning & Commerce International : Sujet CI01

![Python Version](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-En%20cours-orange)
---

## 📌 Informations Générales

- **Nom & Prénom :** Israa Ait Bousalem
- **Code Apogée :** 23008729
- **Groupe :** G1
- **Établissement :** ENCG Settat — S7 Commerce International
- **Sujet attribué :** CI01 — Prévision des exportations marocaines par produit et destination
- **Dépôt GitHub :** `23008729-AitBousalem-G1`

---

## 🎯 Problématique Économique & Objectifs

- **Contexte :** Le Maroc cherche à optimiser ses flux commerciaux et anticiper les recettes d'exportation vers ses principaux partenaires commerciaux.

- **Question de recherche :** Comment anticiper avec précision la valeur mensuelle/annuelle des exportations marocaines selon la catégorie de produit (code SH) et le pays destinataire ?

- **Tâche ML :** Régression quantitative.

- **Algorithme principal :** Régression Ridge (Algorithme n°1 du cours).

- **Référence naïve (Baseline) :** Persistance (valeur du flux à \(t-1\)) ou Moyenne historique.

- **Objectif mesurable :** Obtenir une erreur quadratique moyenne (RMSE) inférieure d'au moins 15% à celle de la baseline naïve sur le jeu de test final.

---

## 📂 Structure du Dépôt

```text
23008729-AitBousalem-G1/
│
├── README.md
│   # Présentation du projet et guide de reproduction
│
├── requirements.txt
│   # Dépendances Python requises
│
├── .gitignore
│   # Fichiers ignorés par Git
│
├── DECLARATION_IA.md
│   # Transparence et intégrité académique
│
├── data/
│   └── raw/
│       # Données brutes (Office des Changes / UN Comtrade)
│
├── docs/
│   └── sujet_CI01.md
│       # Fiche sujet et consignes
│
├── notebooks/
│   └── projet_CI01.ipynb
│       # Notebook complet d'analyse et de modélisation
│
├── figures/
│   # Visualisations et graphiques exportés en couleur
│
├── rapport/
│   └── rapport.pdf
│       # Compte rendu exporté en PDF
│
├── presentation/
│   ├── presentation.pdf
│   │   # Support de présentation (exactement 6 diapositives)
│   │
│   └── presentation.pptx
│       # Fichier source de la présentation
│
└── video/
    └── demonstration.mp4
        # Capture vidéo commentée (60 à 90 secondes)
```
