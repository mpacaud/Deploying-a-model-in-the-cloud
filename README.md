# Deploying a model in the cloud

## Issues addressed by the project

This project is the first stage in a wider project to make available to the general public a mobile application that would allow users to take a photo of a fruit and obtain information about it. In this way, the company hopes to raise its profile and attract investors in order to obtain the resources needed to achieve its primary objective. Fruit! has set itself the mission of preserving the biodiversity of fruit by applying specific treatments to each species through the development of autonomous robots.

## Objective

The project presented in this document consists of developing an initial data processing chain in a Big Data environment, which will involve pre-processing the fruit images in the young database, followed by a dimension reduction stage. The aim is to put in place the initial processing building blocks that will be used when the data volume is scaled up. Consequently, it is not necessary to train a model for the time being.

*NB: Please note that this work repeats and completes that carried out previously by a trainee.*

## Folder tree

- Root folder:
  - A bootstrap for the packages to be installed.
  - FoxyProxy parameters.
  - Notebooks
  - The read me.
- img: Images from the tutorial
- datasets: Only the resulting dataframe after processing, split into several files in parquet format.


#
#


# Déployer un modèle dans le cloud

## Problématique 

Ce projet s’inscrit comme première étape d’un projet plus global qui consiste à mettre à la disposition du grand public une application mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations le concernant. De cette façon, l’entreprise espère se faire connaître et attirer les investisseurs afin d’obtenir les ressources nécessaires à la réalisation de son objectif premier. En effet, « Fruit ! » s’est donné pour mission de préserver la biodiversité des fruits par l’application de traitements spécifiques à chaque espèce grâce au développement de robots autonomes.

## Objectif

Ainsi, le projet présenté dans ce document consiste à développer dans un environnement Big Data une première chaîne de traitement des données qui comprendra le preprocessing des images de fruits de la jeune base de données suivi d’une étape de réduction de dimension. Le but étant de mettre en place les premières briques de traitement qui serviront lors du passage à l’échelle en termes de volume de données. Par conséquent, il n’est pas nécessaire d’entraîner un modèle pour le moment.

*NB : À noter que ce travail reprend et complète celui réalisé précédemment par un stagiaire.*

## Arborescence de dossiers

- Racine :
  - Un bootstrap pour les paquets à installer.
  - Les paramètres de FoxyProxy.
  - Les notebooks
  - Le read me.
- img : Images du tutoriel
- datasets : Seulement le dataframe résultant après traitement découpé en plusieurs fichiers au format parquet.