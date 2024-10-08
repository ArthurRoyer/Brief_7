# Simulateur de tournoi de Pokémon

Ce projet est un simulateur de combat Pokémon qui utilise l'API PokéAPI pour récupérer des données sur les Pokémon, leurs mouvements et leurs types. Le simulateur permet de choisir des Pokémon aléatoires et de les faire s'affronter dans des combats jusqu'à ce qu'un vainqueur soit déterminé.

## Fonctionnalités

- **Récupération des données Pokémon** : Accède à l'API PokéAPI pour récupérer une liste de Pokémon, leurs statistiques, moves et types.
- **Détails des mouvements** : Récupère les détails des moves, y compris leur puissance et leur classe de dégâts.
- **Efficacité des types** : Récupère les relations d'efficacité entre les types de Pokémon (dégâts doublés, réduits ou aucun effet).
- **Simulations de combats** : Simule des combats entre deux Pokémon, prenant en compte leur vitesse, leurs movess et l'efficacité des types.
- **Tournoi** : Organise un tournoi où des Pokémon s'affrontent en séries éliminatoires jusqu'à ce qu'un champion soit couronné.

## Prérequis

- Python 3.x
- Bibliothèque `requests` pour effectuer des requêtes HTTP

## Installation

1. Clonez le dépôt :
   git clone <URL_DU_DEPOT>

2. Installez les dépendances nécessaires :
   pip install requests

## Utilisation

Excécutez le script Poke.py
Le programme affichera une liste de 16 Pokémon récupérés aléatoirement avec leurs statistiques et moves, puis affichera la table des types de Pokémon.
Ensuite, un tournoi sera simulé, affichant les combats entre les Pokémon et déterminant un vainqueur final.
   
