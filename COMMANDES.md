git clone git@github.com:youssef17k/mon-projet.git :Cloner le dépôt GitHub avec SSH
git remote -v : Afficher et vérifier l'adresse du dépôt distant
git status : Afficher l'état du dépôt
git add index.html : Ajouter le fichier à l'index
git commit -m "Premier commit : ajout de index.html" : Créer commit 
git push origin main : pusher sur le git 
git diff : Affichez les différences entre deux commits 
git log : Historique des commits
git log --oneline --graph --all :Afficher l'historique compact et graphique
git diff 1910542 3f12fc1 :Afficher les différences entre deux commits
git show HEAD :Afficher le détail d'un commit
git branch :Afficher la liste des branches
git switch -c ma-fonctionnalite : Créer la branche ma-fonctionnalite
git push -u origin ma-fonctionnalite :Publie la branche sur GitHub 
git switch main: Revenir sur main
git merge ma-fonctionnalite : Fusionner les branches pour provoquer le conflit
git log --oneline --graph --all : Affichez l'historique graphique pour visualiser la fusion 
git merge --abort : annuler une fusion en cours 