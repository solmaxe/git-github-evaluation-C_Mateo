# Git et Github - Évaluation


### QCM

1. Qui a inventé le logiciel git ?
- Linus Torvalds


2. Pour créer un dépôt localement à partir d'un répertoire vide, quelle est la commande git à utiliser ?
 - init

3. Parmi les protocoles suivants, quels sont les protocoles qui sont utilisables pour communiquer avec la plateforme GitHub ?
 - SSH
 - HTTPS

4. À quoi sert la commande `git remote -vv` ?
 - lister les alias des dépôts distants configurés sur le dépôt local

5. Quels sont les 2 types de branches qui existent dans un dépôt git *sur* l'ordinateur d'un·e développeur·se ?
 - les références locales de branches distantes
 - les locales
 

6. À quoi sert la commande `git fetch -p` ? Utiliser la documentation `man git fetch`.
 - mettre à jour les références locales de branches distantes et supprimer celles qui n'existent plus sur le dépôt distant


7. Quelle est la commande git qui permet d'ajouter un nouveau fichier dans un futur commit ?
 - add


8. Est-il possible d'ajouter un répertoire vide dans un dépôt git ?
 - Non

9. Quel est le chemin du fichier de configuration locale d'un dépôt git ?
 - .git/config

10. À la première utilisation, quelles sont les informations nécessaires pour créer un commit ?
 - le nom de l'utilisateur git
 - l'adresse mail de l'utilisateur git
 
  
11. Quelle est la commande qui permet de mettre à jour la branche sur laquelle on se trouve par rapport à un dépôt distant ? 
 - pull

12. Quelle est la commande qui permet de se mettre sur n'importe quel commit d'un historique git ? 
 - checkout


13. Dans quelles conditions est-ce qu'un conflit apparaît avec git ? 
- Lorsqu'il y a un merge entre deux branches qui modifient la même partie d'un fichier

14. Lorsqu'il y a un conflit, qu'indique la commande `git status` sur les fichiers qui demandent une résolution ? 
 - both modified

  
15. Dans quelle zone du dépôt est-ce que les modifications sont regroupées *avant* de créer un commit ? 
 - le stage


16. Lorsque vous résolvez un conflit, quelle est la dernière commande git que vous tapez ? 
 - commit

17. Quelle est la commande git qui permet de propager ses modifications sur un dépôt distant ? 
- push


18. Comment s'appelle le mécanisme qui permet d'accepter ou de refuser une contribution sur un dépôt GitHub ? 
 - Pull Request


19. Après avoir accepté une contribution sur la branche principale sur Github, que devez vous faire pour mettre à jour votre branche principale localement ? 
 - se mettre sur la branche principale et faire un git pull

20. Qu'est-ce que fait la commande `git merge` ?
 -  fusionne l'historique d'une branche avec une autre en créant un nouveau commit de fusion;


21. Quelle est une conséquence potentielle de l'utilisation de `git rebase` sur une branche publique ?
 - Les autres collaborateurs ayant déjà récupéré la branche peuvent rencontrer des problèmes de synchronisation avec l'historique modifié.


22. Les branches de suivi (*tracking branch*) sont:
 - Des branches locales configurées pour suivre les modifications d'une branche distante.
  

23. Pour mettre à jour (dans le même état) les branches de suivi (*tracking branch*) avec les branches distantes, il faut:
  - Utiliser `git fetch`.


24. `git pull` fait automatiquement un rapatriement de commits d'une branche à l'autre via une stratégie de *merge*: 
 - Vrai.


25. Le nom `origin` donné à un dépôt distant est:
 - Une convention.