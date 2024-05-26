Structure du fichier tasks.txt :

Le fichier tasks.txt est utilisé pour stocker les tâches. Chaque tâche est enregistrée sous la forme :
DATE - [ ] DESCRIPTION
Lorsque la tâche est marquée comme complétée, elle sera enregistrée sous la forme :
DATE - [x] DESCRIPTION

Commandes Disponibles :
Voici les commandes que vous pouvez utiliser avec ce script :

Ajouter une tâche :
./todo.sh add "TITRE DE LA TÂCHE" "DATE D'ÉCHÉANCE"
Description : Cette commande ajoute une nouvelle tâche avec le titre fourni et la date d'échéance spécifiée.

Lister toutes les tâches :
./todo.sh list
Description : Cette commande liste toutes les tâches avec leurs identifiants.

Lister les tâches pour un jour spécifique :
./todo.sh listday "DATE"
Description : Cette commande liste toutes les tâches pour la date spécifiée, divisées en tâches complétées et non complétées.

Rechercher des tâches par titre :
./todo.sh search "TITRE"
Description : Cette commande recherche et affiche les tâches dont le titre contient le texte spécifié.      

Supprimer une tâche :
./todo.sh delete TASK_ID
Description : Cette commande supprime la tâche avec l'identifiant spécifié.

Mettre à jour une tâche :
./todo.sh update TASK_ID "NOUVEAU TITRE" "NOUVELLE DATE D'ÉCHÉANCE"
Description : Cette commande met à jour le titre et la date d'échéance de la tâche spécifiée.

Marquer une tâche comme complétée
./todo.sh mark TASK_ID
Description : Cette commande marque la tâche spécifiée comme complétée.
