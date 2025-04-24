Explication du projet 

Ce projet est un mini-jeu d'évitement inspiré des jeux d'arcade. Le joueur, représenté par un carré vert, doit éviter les obstacles (carrés rouges) qui apparaissent dans sa trajectoire en allant de gauche à droite.

J’ai développé ce jeu  avec PyGame et intégré dans un environnement Gymnasium pour permettre l'entraînement d'agents en apprentissage par renforcement. Deux agents intelligents sont entraînés pour y jouer automatiquement :
- Un agent PPO (Proximal Policy Optimization)
- Un agent Q-Learning

L'objectif est de comparer leurs performances et leur capacité à apprendre à éviter les obstacles.


Les  Technologies que j’ai utilisées
- PyGame: pour le rendu visuel et la logique de jeu
- Gymnasium : pour créer un environnement RL compatible
- Stable-Baselines3 : pour l'entraînement PPO
- NumPy : pour la manipulation de vecteurs
- Matplotlib: pour la visualisation des scores (optionnelle)



Méthodes RL : PPO vs Q-learning

PPO (Proximal Policy Optimization)
- Basé sur les politiques stochastiques et l'optimisation de gradients
- Converge plus lentement mais permet de généraliser à des environnements plus complexes
- Utilisé avec `stable_baselines3.PPO`

Q-Learning
- Apprentissage par Q table plus simple
- Meilleur pour des environnements discrets comme ce jeu avec 3 positions
- Implémenté from scratch avec mise à jour de la table Q

Les étapes du projet 

J'ai commencé par l'Encapsulation du jeu dans un environnement Gymnasium;
Ensuite j'ai implementé la technique de PPO avec Stable-Baselines3; 
Et par la suite j'ai ajouter manuellement la technique de Q-learning; 
Enfin j'ai publié le projet.

  
