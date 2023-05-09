Choisissez un dépôt Git (ou créez-en un nouveau) avec au moins un commit
Créez un nouveau fichier appelé "file1" et écrit la chaîne de caractères "master branch" à l'intérieur
Ajoutez le fichier "file1" à l'index Git pour préparer le commit
git add file1.txt
Créez un nouveau commit contenant tous les fichiers ajoutés ou modifiés
git commit -m "initial commit file1"
Créez une nouvelle branche appelée "dev"
git checkout -b dev
Créez un nouveau fichier appelé "file2" et écrit la chaîne de caractères "dev branch" à l'intérieur
Ajoutez le fichier "file2" à l'index Git pour préparer le commit
git add file2.txt
Créez un nouveau commit
git commit -m "initial commit file2
Vérifiez que le commit que vous avez créé se trouve uniquement dans la branche "dev"
Vérifiez la branche "master"
git checkout master
git branch
