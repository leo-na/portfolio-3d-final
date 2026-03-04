# 🚀 3D Developer Portfolio

Un portfolio moderne et immersif construit avec **React** et **Three.js**. Ce projet intègre des modèles 3D interactifs, des animations fluides et une interface responsive pour présenter tes compétences et tes projets de manière innovante.

## 📋 Sommaire

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Fonctionnalités](#fonctionnalités)
4. [Installation Rapide](#installation)
5. [Configuration](#configuration)

## 🤖 Introduction

Ce projet est un portfolio de développeur haut de gamme qui utilise des bibliothèques 3D pour transformer une navigation web classique en une expérience immersive. Il démontre la capacité à manipuler des géométries complexes, des lumières et des animations dans un environnement web.

## ⚙️ Tech Stack

* **Framework :** React.js
* **3D :** Three.js, React Three Fiber, React Three Drei
* **Animations :** Framer Motion
* **Style :** Tailwind CSS
* **Outil de build :** Vite
* **Email :** EmailJS

## 🔋 Fonctionnalités

* **Section Hero 3D :** Un modèle 3D interactif au centre de la page d'accueil.
* **Expériences & Projets :** Sections animées avec Framer Motion pour un affichage dynamique.
* **Compétences en 3D :** Présentation des technologies sous forme de géométries 3D rotatives.
* **Contact & Modèle Earth :** Un formulaire de contact fonctionnel avec un globe terrestre 3D.
* **Fond Étoilé :** Génération de particules (étoiles) aléatoires en arrière-plan.
* **Design Responsive :** Entièrement optimisé pour tous les types d'écrans.

## 🤸 Installation

Suivez ces étapes pour installer le projet localement :

1.  **Cloner le dépôt**
    ```bash
    git clone [https://github.com/leo-na/project_3D_developer_portfolio.git](https://github.com/leo-na/project_3D_developer_portfolio.git)
    cd project_3D_developer_portfolio
    ```

2.  **Installer les dépendances**
    ```bash
    npm install
    ```

3.  **Lancer le projet**
    ```bash
    npm run dev
    ```
    L'application sera disponible sur : [http://localhost:5173](http://localhost:5173)

## 📧 Configuration

Pour rendre le formulaire de contact fonctionnel, créez un fichier `.env` à la racine du projet et ajoutez vos clés **EmailJS** :

```env
VITE_APP_EMAILJS_SERVICE_ID=votre_service_id
VITE_APP_EMAILJS_TEMPLATE_ID=votre_template_id
VITE_APP_EMAILJS_PUBLIC_KEY=votre_cle_publique
