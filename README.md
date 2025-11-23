# 📊 Dashboard Hyper Marché — Analyse des Ventes avec Power BI

Ce projet présente un tableau de bord interactif développé avec **Power BI Desktop** pour analyser les ventes, les profits et les performances produit d’un Hyper Marché.
L’objectif est de fournir une vue synthétique et exploitable des **KPI commerciaux**, des tendances mensuelles et de la contribution des segments et catégories.

---

## 🎯 Objectifs du Projet

* Suivre le **revenu total**, le **profit net** et leurs évolutions mensuelles
* Identifier les **meilleurs** et **pires produits** (Top / Bottom 5)
* Comprendre la distribution du revenu par **segment** et **catégorie**
* Comparer les performances selon les **continents** et les **années**
* Offrir un outil interactif pour faciliter la prise de décision

---

## 🗂️ Source des Données

Le projet utilise le dataset **Hyper Store**.

✔ Avant le travail d’analyse, **l’ensemble du dataset a été traduit en français** pour harmoniser les colonnes et le rendu du rapport.

---

## 🛠️ 1. Préparation et Transformation des Données (Power Query)

Principales étapes :

* Suppression des lignes inutiles et des doublons
* Définition des en-têtes
* Fractionnement de colonnes (`segment category` → Segment / Catégorie, `region country` → Région / Pays)
* Nettoyage et standardisation des valeurs (ex. "USA")
* Conversion correcte des dates grâce aux **paramètres régionaux**
* Vérification de la qualité des colonnes (100% valide)

---

## 🧱 2. Modélisation

* Création d'un groupe personnalisé **Country Group** pour distinguer :

  * *Amérique du Nord* : USA, Canada, Mexique
  * *Amérique du Sud* : Brésil
* Mise en place des mesures essentielles (revenu, profit, unités vendues…)
* Modèle de données simple et facile à maintenir

---

## 📈 3. Visualisations Principales

Le tableau de bord inclut :

* **Revenu & Profit par mois**
* **Revenu & Unités vendues par mois**
* **Top 5 produits les plus vendus**
* **Top 5 produits les moins vendus**
* **Répartition du revenu par segment**
* **Répartition du revenu par catégorie**

Filtres interactifs :

* **Continent (Country Group)**
* **Année**

---

## 📁 Structure du Projet

* `Dashboard Hyper Marché.pbix` — fichier Power BI
* `/images/` — captures du tableau de bord

<img width="590" height="333" alt="Capture 2" src="https://github.com/user-attachments/assets/2173d5da-ac42-45b2-90e2-61c756ac95d3" />
<img width="590" height="334" alt="Capture 1" src="https://github.com/user-attachments/assets/ce821ed2-afea-4e26-8593-4f4b9adb1c5d" />
<img width="589" height="335" alt="Capture 3" src="https://github.com/user-attachments/assets/7e93383e-8b30-40ae-b9de-36b55de2e76c" />

---

## 👤 Auteur

**André Yann Emmanuel Koffi**
Master 2 MIAGE — UFHB / Rennes 1
Aspirant Data Analyst Junior | Business Intelligence

---

