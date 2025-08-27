<img width="720" height="720" alt="Image" src="https://github.com/user-attachments/assets/3df593cf-c98c-4420-8aab-f36e82cfd89b" />

# Sujet :
NetPractice est un projet d’entraînement à la configuration réseau.
Il consiste à résoudre une série d’exercices interactifs qui simulent des scénarios de connexion entre machines, routeurs et réseaux.

L’objectif est de comprendre et manipuler :
- Les adresses IP
- Les masques de sous-réseau
- Les passerelles
- Les notions de routage et connectivité
- Apprendre à analyser un schéma réseau.
- Attribuer les bonnes adresses IP aux interfaces.
- Assurer la communication entre toutes les machines selon les contraintes données.
- Découvrir la logique des réseaux IPv4 en environnement simulé.

# Fonctionnement :
Le projet se fait via un navigateur web (fichier HTML fourni).
Chaque exercice affiche un schéma réseau avec des zones de configuration IP.

Il faut entrer :
- Une adresse IP valide
- Un masque correct
- Éventuellement une passerelle si les machines sont sur des réseaux différents.

Quand toutes les machines peuvent se connecter, l’exercice est validé.

# Explications :

Adresses IP : <br>
Une adresse IP identifie de manière unique un appareil sur un réseau.
- IPv4 : format le plus courant, composé de 4 octets (ex. 192.168.0.1).
- Rôle : permettre l’envoi et la réception de données sur un réseau. <br>
Chaque IP se compose de deux parties :
- Partie réseau : identifie le réseau auquel l’hôte appartient.
- Partie hôte : identifie la machine dans ce réseau.

Masques de sous-réseau : <br>
Le masque de sous-réseau détermine quelle partie de l’IP correspond au réseau et quelle partie correspond à l’hôte.
- Exemple : 255.255.255.0 → les 3 premiers octets pour le réseau, le dernier pour les hôtes.
- Utilité : découper un réseau en sous-réseaux pour mieux gérer la connectivité et la sécurité.
- Notation : /24 équivaut à 255.255.255.0.

Passerelles : <br>
Une passerelle est un point d’accès qui permet de sortir de son réseau local vers un autre réseau (ex. Internet).
- Sert d’intermédiaire entre deux réseaux.
- En général, la passerelle est l’adresse IP du routeur du réseau.
- Sans passerelle configurée, un appareil ne peut pas communiquer avec un réseau extérieur.

Routage & Connectivité : <br>
Le routage est le processus qui permet de faire transiter les données d’un réseau à un autre via des routes.
- Route statique : configuration manuelle des chemins à suivre.
- Route dynamique : déterminée automatiquement par des protocoles de routage.
- Connectivité : capacité d’un appareil à atteindre un autre, testée par des outils comme ping ou traceroute.
