# nashers

## Objectifs

L'objectif de ce dépôt est de créer un nouveau jeu vidéo multi-joueurs, basé sur du tour par tour.
N'étant pas un développeur à la base, ce projet a pour but de m'aider à apprendre le code et en particulier du Django. 

## Principes 

Le jeu connait différents scénarios ayant chacun leurs spécificités, mais globalement : 

- Chaque joueur dispose de 4 attributs.
- A chaque tour, les joueurs ont une question posée et ils doivent faire un choix.
- La valeur des attributs change en fonction des choix réalisés par l'ensemble des joueurs.
- Il existe plusieurs types de questions : 

    - Des questions individuelles
    - Des questions communes avec réponses visibles
    - Des questions communes avec réponses cachées 
    - Des questions à un groupe de joueurs définis 

- Chaque joueur dispose de 5  objectifs : 
 
    - Un objectif individuel primaire : si l'objectif est échoué,  le joueur perd. 
    - Un objectif collectif primaire : cet objectif est commun à tous les joueurs. Si il n'est p as réussi, il est perdu
    - 3 objectifs secondaires : il permet de différencier les joueurs entre eux. 

Ces objectifs sont en lien avec les attributs. 
