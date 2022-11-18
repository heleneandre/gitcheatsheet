# I AM DUMB IN SOCIAL CODING ON GIT

$ git add git-cheat-sheet.md -> Add a file before doing the snapshot of it

$ git status -> Check the status of the file

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

$ git add nom du fichier à ajouter 

git commit -m 'commit message' -> pour commit sur notre branche les modifs que l'on a fait

$ git log -> Checker ce que l'on a fait

$ git checkout -b features/1234-new-killing-feature -> pour créer une nouvelle branche j'ajoute le "-b"

$ git checkout main ou features/1234-new-killing-feature -> pour changer de branche

Pour merge dans la branche principale -> on se remet sur la branche "main" puis git merge "features/1234-new-killing-feature" ->>> nom de la branche 

$ git fetch -> Mise à jour de la base de donnée de mon repo local

pull = fetch + merge

$ git push -> Je pousse les modifs faites dans mon repo local au repo partagé

git branch -> Pour checker que la branche a bien été créée

Une fois mon repo distant créé, je dois ajouter la connexion entre lui et mon repo local : $ git remote add origin https://github.com/avanade-talentagile/gitandsocialcoding.git (url repo distant)

$ git remote -v -> Permet de lister les remotes que j'ai 