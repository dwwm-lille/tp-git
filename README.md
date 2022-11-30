# TP Git

Nous allons composer des équipes de 4 personnes. L'objectif est de réaliser une petite page HTML / CSS et Sass.

On a 3 parties importantes sur la page :

- Header (Menu avec logo)
- Un contenu (Deux colonnes avec une image et un texte)
- Un autre contenu (Trois colonnes avec images et texte)
- Footer (Fond de couleur avec un texte copyright)

Chaque groupe aura UN SEUL dépôt Github. Pour créer ce dépôt, une personne prend la responsabilité de créer le dépôt sur son compte Github.

Le créateur devra créer un fichier HTML avec un DOCTYPE et un body vide, un fichier SCSS vide liés à la page HTML.

Ensuite, les trois autres personnes vont devoir être ajoutées sur le dépôt du "créateur".

Une fois que les personnes ont accès au dépôt sur Github, elles vont devoir "cloner" le dépôt :

```
cd Code
git clone https://github.com/dwwm-lille/discover-git.git
```

A cette étape, tous les membres ont le projet en commun sur leur machine.

Chaque membre va créer sa branche (header, footer, content ou content-2) puis va la pousser sur Github. Essayez de profiter de Sass pour découper votre code en composant et chaque personne travaille dans le composant dédié. Attention de bien ignorer le fichier compilé pour éviter les conflits.

Ensuite chacun va faire son travail, committer et push sur sa branche.

A la fin du projet, quand tout le monde a finit, chacun va créer une Pull Request avec sa branche et va la "merger" dans main.
