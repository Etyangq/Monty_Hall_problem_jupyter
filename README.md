# Le problème de Monty Hall
C'est un jeu télévisé où il y a trois portes sur le plateau de jeu. Seule une de ces portes cache un trésor. Il n'y a rien derrière les deux autres portes. Rien ne permet de savoir quelle porte cache le trésor.

La tâche du joueur consiste à choisir parmi les trois portes celle qu'il veut ouvrir. Il aura droit au trésor s'il choisit la bonne porte, et rien sinon. Pour faire son choix, il n'a aucune information. Il doit donc simplement s'en remettre au hasard.

Jusqu'ici, le problème n'a rien de remarquable. Mais il y a un twist ! Une fois que le joueur a fait son choix, mais avant d'ouvrir la porte, le présentateur élimine, parmi les deux portes non choisies, une porte qui ne contient pas de trésor. Si les deux portes restantes ne contiennent rien, le présentateur élimine simplement une d'entre elles au hasard.

Le joueur doit alors faire un nouveau choix. Il peut soit choisir d'ouvrir la première porte qu'il avait choisie, soit changer pour la porte non éliminée par le présentateur. La question est, qu'a-t-il intérêt à faire ? 

![](https://github.com/Etyangq/Images_for_md/blob/main/images/Monty%20Hall.jpg?raw=true)

# Note
## Il y a 3 fichers 
- Fichier "Monty-Hall-problème " concerne plutôt les Data Scientists.
- Fichier "Monty-Hall-Problème-Exercice " ajouter une exercice : Nous pouvons imaginer une autre stratégie, où le joueur choisit aléatoirement une porte entre la première et celle que le présentateur n'a pas éliminée. Implémentez cette stratégie et observez les résultats.
Résultats: Le gain attendu se situe à mi-chemin des gains attendus avec les deux stratégies initiales.
- Fichier "Monty-Hall-Problème-Numpy": Simulation du problème de Monty Hall avec Numpy.

