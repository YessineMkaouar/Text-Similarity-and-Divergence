# Analyse Sémantique des Idées Similaires et Divergentes entre Documents Textuels 

## Description du Projet
Ce projet propose une approche pour comparer le contenu de deux documents en mettant en avant leurs idées communes et leurs différences. Grâce à des différents méthodes d’analyse de similarité (TF-IDF, Word2Vec, SBERT, LSA) et un modèle de langage (LLM), il permet d’identifier les points de convergence et de divergence entre textes de manière automatisée. Ce pipeline est pensé pour des applications telles que l'analyse d’articles scientifiques, de documents et d’autres contenus textuels étendus.

## Fonctionnalités Principales
- **Extraction et Prétraitement des Données** : Récupération des données textuelles et nettoyage.
- **Comparaison Basée sur la Similarité Lexicale** : Utilisation de TF-IDF pour une première comparaison de mots-clés entre documents.
- **Analyse Sémantique par Embeddings** : Implémentation de Word2Vec et SBERT pour évaluer la similarité sémantique des paragraphes.
- **Résumé Automatique** : Résumé des textes par LSA pour une vue d'ensemble simplifiée des contenus.
- **Modèle de Langage (LLM)** : Utilisation d'un LLM pour générer des comparaisons textuelles plus riches et nuancées.

## Méthodologie
1. **Prétraitement des Textes** : Nettoyage des données en supprimant les caractères spéciaux, la mise en forme, et la segmentation en paragraphes.
2. **Comparaison des Mots-Clés** : Utilisation de TF-IDF pour extraire les mots-clés les plus importants de chaque document.
3. **Analyse Sémantique** : Comparaison des paragraphes avec Word2Vec et SBERT pour évaluer la similarité sémantique.
2. **Résumé des Documents** : Résumé automatique des textes avec LSA afin d'en extraire les idées principales puis utilisation des embeddings de SBERT pour comparer les résumés.
5. **LLM pour Synthèse de la Comparaison** : Génération d'une analyse textuelle des similarités et divergences avec un LLM. (Qwen2.5)

