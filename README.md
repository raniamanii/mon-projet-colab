🌿 Health Visual Diagnostic — Analyse Santé avec Images et UI Interactive

Ce projet Google Colab permet d’analyser plusieurs indicateurs de santé (tension, fréquence cardiaque, IMC, stress, nombre de pas…) et d'afficher automatiquement :

un diagnostic personnalisé,

des conseils adaptés,

ainsi que des images illustratives pour chaque problème détecté.

L’interface fonctionne grâce à ipywidgets et IPython.display pour offrir une expérience simple et intuitive.

✅ Fonctionnalités

Formulaire interactif pour saisir :

Âge

Tension systolique & diastolique

Fréquence cardiaque

BMI / IMC

Nombre de pas par jour

Niveau de stress

Diagnostic automatique basé sur les valeurs

Affichage :

Image

Titre du problème

Conseils personnalisés

Interface responsive compatible Google Colab

📁 Structure des fichiers
/MonProjetSante
│
├── Health_Diagnostic.ipynb     → Notebook principal (Google Colab)
├── README.md                   → Description du projet
│
├── Hypertension.jpg
├── tachycardie.jpg
├── bradycardie.jpg
├── Obésité.jpg
├── Activité modérée.jpg
├── État global sain.jpg


⚠️ Important :
Les images doivent être uploadées dans Google Colab via files.upload() ou stockées dans ton Drive.

▶️ Comment utiliser le projet
1. Ouvrir le notebook dans Google Colab

Clique sur :
Runtime → Run all

2. Importer les images

Dans la cellule prévue :

from google.colab import files
files.upload()


Sélectionne toutes tes images.

3. Lancer l’interface

Une interface avec sliders et champs s’affiche.
Clique sur Analyser pour obtenir le diagnostic.

🧠 Technologies utilisées

Python 3

Google Colab

ipywidgets

IPython.display

HTML/CSS intégrés dans Python

📸 Aperçu (exemple)

Le script génère automatiquement :

Une carte visuelle pour chaque problème détecté

Un texte explicatif

Une image correspondante
