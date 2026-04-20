# 🚀 Analyse et Commande des Systèmes Non Linéaires (SNL)

[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()
[![Course](https://img.shields.io/badge/Course-Automatique_%26_Contrôle-blue?style=for-the-badge)]()
[![UI](https://img.shields.io/badge/UI-Modern_Web-8b5cf6?style=for-the-badge)]()

> Un dépôt dédié à la synthèse de lois de commande avancées pour les systèmes non linéaires, incluant la linéarisation d'état, l'analyse de la dynamique interne et la commande robuste par mode glissant (SMC).

---

## 📋 Description du Projet

Ce projet documente la résolution analytique et la mise en forme des concepts fondamentaux de l'automatique non linéaire (basé sur le TD N°4). Il explore les limites de la linéarisation exacte, le traitement de la dynamique inobservable, et l'application de commandes robustes sur des systèmes complexes.

Les travaux incluent des démonstrations mathématiques rigoureuses (difféomorphismes, stabilité de Lyapunov) ainsi qu'une interface web interactive pour la visualisation des concepts de stabilité.

---

## ✨ Fonctionnalités et Concepts Abordés

* **Linéarisation Entrée-Sortie & Entrée-État :**
    * Calcul du degré relatif ($r$) et transformations de coordonnées ($T(x)$).
    * Synthèse de lois de commande pour forcer un comportement linéaire équivalent.
* **Analyse de la Dynamique Interne :**
    * Extraction de la dynamique inobservable ($\eta$).
    * Étude de la dynamique des zéros et vérification des conditions de **minimum de phase** via la résolution d'équations différentielles ($e^{-(B+1)t}$).
* **Commande par Mode Glissant (SMC) :**
    * Conception de surfaces de glissement pour un **Pendule Simple** et un **Drone (Quadrotor)**.
    * Calcul des commandes équivalentes ($U_{eq}$) et discontinues ($U_{dis}$).
    * Preuve de stabilité asymptotique globale par la méthode de Lyapunov ($\dot{V} < 0$).

---

## 📂 Structure du Dépôt

\`\`\`text
📦 SNL-Control-Systems
 ┣ 📜 README.md         # Documentation principale
 ┣ 📜 index.html        # Interface Web de démonstration de la stabilité (UI Moderne)
 ┗ 📂 Docs/             # Développements mathématiques et résolutions (PDF/Markdown)
\`\`\`

---

## 🚀 Utilisation

### Visualisation Web (Dynamique Interne)
Une page web moderne a été développée pour expliquer visuellement la convergence exponentielle de la dynamique des zéros.
1. Clonez ce dépôt sur votre machine locale.
2. Ouvrez simplement le fichier `index.html` dans n'importe quel navigateur web moderne.
3. Le rendu utilise **MathJax** pour un affichage parfait des équations $\LaTeX$.

---

## 🛠️ Technologies & Outils

* **Théorie :** Contrôle Non Linéaire, Théorie de Lyapunov, Algèbre Linéaire.
* **Web :** HTML5, CSS3 (Design moderne inspiré des palettes Cyan/Violet), MathJax.

---

## 👤 Auteur

**Créé par :** Dahane Ahmed Lamine 
*Étudiant en Automatique et Systèmes Industriels*
