Déployer une application web

1.4 'vercel --version'

1.5 'vercel init angular'

1.6 'cd angular && vercel'

1.7 'vercel ls'

1.8 'vercel logs angular-bl4xsmllw.vercel.app'

1.9 'vercel inspect angular-bl4xsmllw.vercel.app'
Cette commande permet de voir les informations sur le déploiement du projet comme la structure des fichiers, les routes, url, l'état,...

1.10 Les variables d'environnement servent à ajouter des paramètres de configurations sur l'outil déployé avec Vercel

1.11 'vercel env add plain DB_LOGIN production'

1.12 'vercel env ls'

1.13 Ce sont des variables chiffrés qui sont donc invisibles, elle permettent de transmettre des données sensibles ou secrètes.

1.14

1.15 'vercel secret add secret_2 efcezfezc45'
'vercel env add secret SECRET_2 production'

1.16 production, preview, development
L'intérêt d'avoir plusieurs environnement, c'est de pouvoir faire des tests sans casser l'application. On développe sur l'environnement de développement, puis après on fait les tests sur preview pour ainsi "pousser" les modifications finales sur l'environnement de production disponible au clients.

1.17 

1.18 'https://vercel-project-e9d4kycmd.vercel.app'

1.19 Un pull-request est une proposition de modification du projet. Un contributeur va récupérer le projet, créer des améliorations sur une nouvelle branche, et va envoyer un pull-request pour faire passer ses modifications sur le master du projet.

1.19 