Initiation à ${app}
-----------------------------------
Bienvenue dans votre nouvelle application Ruby on Rails !
Application Rails on Rails qui permet une mise en route rapide. 

1. [Installez l'outil de ligne de commande cf](${doc-url}/#starters/BuildingWeb.html#install_cf).
2. [Téléchargez le package d'applications du module de démarrage](${ace-url}/rest/apps/${app-guid}/starter-download).
3. Procédez à l'extraction du package et placez-vous dans le répertoire correspondant à l'aide de la commande `cd`. 
4. Accédez à Bluemix :

		cf api ${url-api}

5. Connectez-vous à Bluemix :

		cf login -u ${nom-utilisateur}
		cf target -o ${org} -s ${espace}
		
6. Déployez votre application :

		cf push ${app}

7. Accédez à votre application : [${route}](//${route})