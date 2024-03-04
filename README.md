# Documentation du projet `demogit`

## Configurer git

```bash
git config --global user.name Nom
git config --global user.email mail@mail.fr
```

## Initialiser un dépôt git

```bash
git init
```

## Ajouter les fichiers en "staging area"
```bash
git add README.md
git add demo.txt
git add *.html
git add .
```

## Faire un commit
```bash
git commit -m "Premier commit"
```

## Lister tous les commits
```bash
git log
```


## Détecter les modifications faites depuis le dernier commit
```bash
git diff
```

> `git diff` affiche les lignes ajoutées, modifiées ou supprimées depuis le dernier `commit`.

## Ignorer certains fichiers avec gitignore

```bash
echo $'.env\ndemo.txt' > .gitignore
``̀̀`

nickel
