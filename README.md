# Resolveur de taquin cylindrique

<div class=text-justify>

Le projet est un résolveur de taquin cylindrique. Au au-travers de ce programme est automatisé la solution du taquin en tenant compte des heuristiques. Il affiche les différentes étapes de la résolution et peut affirmer ou non si le taquin a bien une solution. Cette application reçoit un taquin ainsi que sa dimension (à travers une invite de commande, ou par redirection depuis un fichier texte) qu’elle interprète puis exécute des fonctions en interne afin de répondre aux différents besoins que peuvent être : initialiser le taquin, appliquer l’algorithme A* afin de résoudre le taquin, supprimer la mémoire allouée pour l’initialisation du taquin, initialiser les listes LEE (Liste des états explorés) et LEAE (Liste des états à explorer), insérer les différents états du taquin ou encore supprimer les listes.

Les sorties sont récupérées directement dans la console sous forme de texte, ou dans un fichier texte lorsqu’on utilise les redirections. Elles comportent une partie de récupération des données, puis un affichage des listes des états du taquin au fur et à mesure de l’exécution de l’algorithme et un message de conclusion si le taquin est résolu. 


