🎮 Guide d'Utilisation du Script Roblox Checker
🚀 Prérequis

Avant de vous lancer, assurez-vous d'avoir les éléments suivants :

    Python 3.x
    Vérifiez son installation avec :

    bash

python --version

Bibliothèques Requises
Installez les bibliothèques nécessaires avec pip :

bash

    pip install requests selenium colorama

    WebDriver pour Firefox
    Téléchargez GeckoDriver et assurez-vous qu'il est accessible dans votre PATH.

🏁 Étapes pour Exécuter le Script

    Téléchargez le Script
    Clonez le dépôt GitHub ou téléchargez le fichier directement.

    Ouvrez votre Terminal
    Naviguez jusqu'au dossier où se trouve le script.

    Lancez le Script
    Exécutez la commande suivante :

    bash

python robloxchecker.py

Vérification de Version
Le script vérifiera automatiquement s'il existe une mise à jour. Si une nouvelle version est disponible, elle sera téléchargée et le script redémarrera.

Sélectionnez le Fichier combo.json
Une fenêtre de dialogue s'ouvrira. Choisissez le fichier contenant les identifiants à tester, structuré comme ceci :

json

    [
        {"username": "user1", "password": "password1"},
        {"username": "user2", "password": "password2"}
    ]

    Vérification des Identifiants
    Le script tentera de se connecter à Roblox avec les identifiants fournis en utilisant les proxies configurés. Les résultats de chaque tentative s'afficheront dans le terminal.

    Gestion des CAPTCHA
    Si un CAPTCHA est détecté, le script vous invitera à le résoudre manuellement. Appuyez sur Entrée lorsque vous aurez terminé pour continuer.

    Fin de la Vérification
    Une fois toutes les tentatives effectuées, le script affichera un message de fin.

⚙️ Résolution des Problèmes

    Erreur de Téléchargement
    Vérifiez votre connexion Internet et l'accessibilité du lien.

    Fichier JSON Vide
    Assurez-vous que le fichier contient des données valides.

    Échec de Connexion
    Vérifiez l'exactitude des identifiants et la fonctionnalité des proxies.

🔒 Remarques

    Sécurité : Faites preuve de prudence lors du test des identifiants pour des services en ligne. Respectez les conditions d'utilisation de Roblox.

    Utilisation des Proxies : Vous pouvez modifier la liste des proxies dans le code selon vos besoins.
