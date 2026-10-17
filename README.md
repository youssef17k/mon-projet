# mon-projet
1. Quelle est la différence entre la zone de travail, l'index (staging) et un commit ?
Zone de travail c'est un endroit où on crée et modifie les fichiers du projet 
Index c'est une zone où l'on prépare les modifications à enregistrer avec git add. 
Commit : enregistrement des modifications préparées dans l'historique Git 

2. Quelle est la différence entre Git et GitHub ?
Git est un logiciel de gestion de versions qui permet de suivre les modifications d'un projet mais en locale
GitHub est une plateforme en ligne qui héberge les dépôts Git et facilite la collaboration entre développeurs.

3. Pourquoi passer par une Pull Request plutôt que pousser directement sur main ?
Pull Request permet de faire relire et vérifier les modifications avant de les intégrer à la branche principale main

4. Dans quel cas un conflit apparaît-il, et pourquoi Git ne peut-il pas le résoudre seul ?
Un conflit apparaît lorsque deux branches modifient différemment la même partie d'un fichier et git ne peut pas toujours le résoudre car il ne sait pas quelle version doit être le choisir. Le développeur doit choisir le contenu final et valider la résolution

5. Quelle est la différence entre récupérer les modifications distantes sans fusionner et les récupérer en fusionnant
sans fusionner : git fetch qui récupère les nouvelles modifications du dépôt distant sans les intégrer à la branche locale
en fusionnant : git pull qui récupère les modifications distantes et les intègre à la branche locale

