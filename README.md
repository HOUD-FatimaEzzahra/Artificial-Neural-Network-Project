# Reconnaissance des émotions faciales
## Description du projet 
La reconnaissance des émotions faciales est un domaine de recherche et d'application important dans le domaine de l'intelligence artificielle. Ce projet vise à créer un système de reconnaissance des émotions en temps réel, capable de détecter les expressions faciales et de les classer en différentes émotions telles que la colère, la joie, la tristesse, etc. Le système utilise des réseaux de neurones convolutifs (CNN) pour extraire des caractéristiques significatives des images faciales et les classifier en différentes catégories d'émotions.

Le projet utilise la bibliothèque TensorFlow, qui est une plateforme d'apprentissage automatique open-source, pour construire et entraîner le modèle de reconnaissance des émotions. Le modèle pré-entrainé utilisé dans ce projet est basé sur une architecture de réseau de neurones profonds et a été entraîné sur un vaste ensemble de données contenant des images faciales étiquetées.

Le système peut fonctionner en temps réel en utilisant la webcam d'un ordinateur, ou il peut également traiter des images pré-enregistrées. Pour la détection des visages, le projet utilise l'algorithme de détection de cascade Haar, qui est une méthode populaire et efficace pour détecter les visages dans une image. Une fois les visages détectés, le système extrait les régions d'intérêt (ROI) correspondant aux visages et les utilise pour effectuer la classification des émotions.

L'interface utilisateur du projet est conçue de manière conviviale, avec une fenêtre d'affichage en temps réel pour la webcam ou les images. Les résultats de la classification des émotions sont affichés à l'écran, avec des annotations et des rectangles autour des visages pour indiquer les émotions détectées.

Ce projet peut être utilisé dans divers domaines d'application tels que la recherche en psychologie, l'analyse du comportement des consommateurs, les interfaces utilisateur intelligentes, les jeux, etc. Il offre une approche automatisée et précise pour la reconnaissance des émotions faciales, ce qui peut être utile dans de nombreuses applications pratiques.

## Fonctionnalités
1. Détection en temps réel des visages à partir de la webcam ou d'images
2. Classification des émotions (colère, dégoût, peur, joie, neutralité, tristesse, surprise)
3. Interface utilisateur intuitive pour l'affichage des résultats
4. Utilisation d'un modèle pré-entrainé pour la reconnaissance des émotions

## Bibliothèques utilisées
- Python 3.x
- TensorFlow
- OpenCV
- Matplotlib
- Numpy

## Contributeurs 
Ce projet a été réalisé dans le cadre du module "Statistiques en grandes dimensions et apprentissage" par les étudiantes ingénieures en 4ème année d'ingénierie informatique big data et cloud computing à l'ENSET Mohammedia :
- Fatima-Ezzahra HOUD
- Manar-Elhouda BADRE-EDDINE
- Soukaina DAABAL
