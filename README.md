# Traitement Big Data dans un Environnement Cloud

<p align="center">
  <img src="img/fruit_classification.png" alt="Illustration du projet" width="50%">
</p>

## Contexte

En tant que Data Scientist chez **Fruits!**, une jeune start-up de l'AgriTech, j'ai été chargé de mettre en place une chaîne de traitement Big Data pour le traitement et la classification d'images de fruits. L'objectif est de développer une application mobile permettant aux utilisateurs d'identifier des fruits à partir de photos et de sensibiliser le grand public à la biodiversité des fruits. Ce projet servira également de base pour l'architecture Big Data nécessaire au déploiement futur de modèles de classification à grande échelle.

Ce projet repose sur l'utilisation de **PySpark**, **AWS EMR**, et **S3** pour créer une architecture scalable, tout en assurant la conformité RGPD en utilisant des serveurs européens.

## Objectif du Projet

Le projet se décompose en plusieurs étapes :
1. **Mise en place d'une chaîne de traitement Big Data** : Utilisation de PySpark pour prétraiter les images de fruits et effectuer une réduction de dimension à l'aide de la méthode **PCA**.
2. **Déploiement dans le Cloud** : Migration de la chaîne de traitement vers un environnement Cloud AWS EMR pour permettre le traitement à grande échelle.
3. **Conformité RGPD** : Garantir que toutes les données sont traitées et stockées sur des serveurs situés en Europe pour respecter les exigences du RGPD.

## Étapes du Projet

1. **Développement de la Chaîne de Traitement** :
    - Appropriation du travail réalisé par l'alternant précédemment, en particulier le traitement PySpark.
    - Ajout d'une étape de réduction de dimension **PCA** pour optimiser la gestion des données massives.
    - Intégration du **broadcasting** des poids du modèle **TensorFlow** sur les clusters EMR pour une distribution efficace du calcul.

2. **Migration vers AWS Cloud** :
    - Configuration d'un cluster **EMR** sur AWS pour la gestion des calculs distribués.
    - Stockage des données dans un **bucket S3** et mise en place des permissions **IAM** pour assurer la sécurité des données.
    - Exécution et validation de la chaîne de traitement dans un environnement Big Data.

3. **Conformité RGPD** :
    - Paramétrage des serveurs AWS pour garantir que les traitements sont réalisés dans des centres de données situés en Europe.

## Livrables

- **Notebook PySpark** : Un notebook contenant le code PySpark avec une étape de réduction de dimension par PCA, prêt à être exécuté dans un environnement Cloud.
- **Stockage Cloud** : Les images du jeu de données et la sortie de la réduction de dimension seront disponibles dans un espace de stockage Cloud (**S3**).
- **Support de Présentation** : Un document expliquant les différentes briques d'architecture utilisées (S3, EMR, IAM), la chaîne de traitement PySpark, et leur mise en œuvre.

## Soutenance

La soutenance du projet s'articulera autour des points suivants :
- **Présentation de l'Environnement Big Data (6 minutes)** : Explication des choix technologiques pour la création de l'architecture Cloud.
- **Présentation de la Chaîne de Traitement (6 minutes)** : Démonstration de la chaîne de traitement d'images, de la configuration PySpark à la réduction de dimension par PCA.
- **Démonstration Technique (2 minutes)** : Exécution en direct du script PySpark dans l'environnement Cloud AWS.
- **Conclusion et Synthèse (3 minutes)** : Résumé des résultats obtenus et discussion sur l'évolutivité de la solution.

### Visionner la Démonstration

Vous pouvez visionner l'enregistrement de la démonstration technique à l'adresse suivante : [Lien vers la vidéo](https://youtu.be/GKUOvqqU9iw).

## Contact

Pour plus d'informations, vous pouvez me contacter via mon site web : [alexandre.rogues.fr](https://alexandre.rogues.fr).

Merci de l'intérêt porté à ce projet !

