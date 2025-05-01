# API-Web-Scraping-E-Commerce-Product-Data

Ce projet consiste à développer une API automatisée capable d'extraire des données produits (prix, descriptions, images, avis clients, etc.) à partir de sites e-commerce comme Amazon, eBay ou Shopify, en combinant des techniques de web scraping et d'intégration d'API existantes. Contrairement au scraping traditionnel (BeautifulSoup, Selenium), cette solution utilise des API publiques ou privées (lorsqu'elles sont disponibles) pour récupérer les données de manière plus fiable et légale, tout en évitant les blocages liés aux protections anti-bot.

**Fonctionnalités Clés :**
- Extraction Structurée : Récupération des données produits via des endpoints API (ex: Amazon Product Advertising API, eBay API) ou en reverse-engineering des API internes utilisées par les sites cibles.

- Nettoyage et Normalisation : Unification des formats de données (ex: conversion des devises, standardisation des catégories).

- Stockage et Export : Sauvegarde dans des bases de données (MySQL, MongoDB) ou fichiers (JSON, CSV) pour analyse ultérieure.

- Mise à Jour Automatisée : Planification de requêtes périodiques pour suivre l'évolution des prix et stocks.

**Avantages par rapport au Scraping Classique :**

✅ Moins de risques de blocage (les API sont conçues pour être interrogées).
✅ Données plus propres et structurées (pas besoin de parser du HTML). 
✅ Performances accrues (les API répondent plus vite qu'une page web chargée via Selenium).
