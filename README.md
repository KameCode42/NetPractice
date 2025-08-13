
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

# Exemple :
- Machine A : 192.168.1.1 / 255.255.255.0
- Machine B : 192.168.1.2 / 255.255.255.0

Les deux machines peuvent communiquer (même réseau).
