# Détection de la langue avec Azure et Cognitive service

![Cognitive Service d'Azure](data/images/cog.png)

Avant l'essai, veuillez renommer le fichier "env_example" en ".env" puis y ajouter votre clé API et point de terminaison.

## Installation des dépendances

    pip install -r requirements.txt

## Script

Le script permet de tester le service de traduction et de détection de la langue.

### Utilisation

    python P1_01_script.py "Votre message"

## Notebook en mode présentation

Veuillez lancer le notebook avec la commande suivante

    jupyter nbconvert P1_02_Présentation_alt.ipynb --to slides --post serve

Ou intégrez le support du mode slideshow avec la commande

    jupyter-nbextension install rise --py --sys-prefix
