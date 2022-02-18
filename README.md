# Mon premier repository

## Présentation
aaaaaaaaaaaaaaaaaaaaaa, aaaa, aaaaa

## Instruction pour l'installation
* Pour créer un repository local en git, tapez la commande suivante : 
```shell
git init
```

* Pour voir les dernières modifications non sauvegardées
```shell
git status
```

* Pour ajouter un fichier à un futur commit
```shell
git add <fichier>
```

* Pour sauvegarder les modifications ajoutées dans un commit :
```shell
git commit -m <description>
```

* Le fichier '.gitignore' permet à git de connaître les fichiers et dossiers à ignorer.

* Pour lier le repository local au distant
```shell
git remote add origin <url https du repository distant>
```

* Pousser les commits
```shell
git push origin master
```