Explication Docker Compose :

Pour mettre en place notre application, nous avions differentes API (Node et core) qui pouvaient �tre appel� grace � l'exposition des ports. Ceci � �t� fait grace au docker compose qui g�rait la redirection des ports. Chaque Api, pointait vers un port diff�rent. Exemple : L'api node vers le port 82
	  L'api core vers le port 81
Ainsi, le docker compose permet de les expos� par la suite sur le port 80.