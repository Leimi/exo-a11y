# Évaluation

## 1. Rebase interactif

Cloner le dépôt git@github.com:Leimi/exo-a11y.git (url github : https://github.com/Leimi/exo-a11y) dans un nouveau dossier.

Puller la branche `corrections-a11y` et la nettoyer afin qu'elle soit prête à être mergée sur master. Cela veut dire :
	- faire attention qu'elle va être bien mergeable sans conflit. Lors de la correction, je dois pouvoir faire, sur master, un `git merge corrections-a11y` sans générer de conflit.
	- analyser les commits actuels de la branche et les modifier afin que le tout soit compréhensible, maintenable, sans commit superflu.

### 1. Rendu attendu

À la fin de l'évaluation, créez un fichier .zip de votre dossier "exo-a11y" entier : fichiers html, css, etc. et SURTOUT le dossier `.git`, qui contient votre dépôt git. Envoyez-le moi en privé sur Discord.

Faites bien ça tout à la fin de l'évaluation, afin que les autres exercices, à rendre dans des fichiers déjà créés dans le dépôt, soient rendus en meme temps.

## 2. Recherches dans un historique git

Cloner le dépôt git@github.com:openfun/richie.git (url github : https://github.com/openfun/richie).

A) Trouvez les réponses de chacun des points suivants, à chaque fois via l'usage **d'une unique commande git** :

	- dans quel commit le fichier `src/richie/apps/courses/templates/courses/cms/blogpost_list.html` a été ajouté ?
	- dans quel commit le fichier `src/richie/apps/courses/templates/courses/cms/fragment_course_glimpse.html` a été modifié pour la dernière fois pour une modification catégorisée "UI and style files" (voir https://gitmoji.dev/) ?
	- depuis quel commit le fichier `src/frontend/js/types/Course.ts` a le type `state.priority` ?
	- depuis quel commit la ligne 10 du fichier `src/frontend/js/data/useFilterValue/index.ts` appelle la fonction `useCourseSearchParams()` ?

B) Trouvez les réponses de chacun des autres points suivants. Ici il est admis d'enchainer plusieurs commandes :

	- combien de commits de `jbpenrath` sont sur `master` ? 
	- combien de commits concernant des mises à jour de dépendances sont sur `master` ?

### 2. Rendu attendu

Pour chaque point, il est demandé :

- la réponse voulue (un identifiant sha1 de commit / un nombre de commits)
- la ou les commandes utilisées pour trouver cette réponse. Attention je répète : pour la partie A), il faut trouver la réponse avec une seule commande git à chaque fois.

Remplissez ça dans le fichier `evaluation/questions-git.md` déjà présent dans le dépôt.

## 3. Recherche de projet open-source

Mise en situation : vous avez un projet web avec du JS "vanilla", autrement dit, sans aucun framework particulier déjà installé. Vous voulez ajouter des boîtes de dialogues (aussi appelées "modals" ou "dialogs") dans votre projet. Vous voulez utiliser un projet open-source car vous n'avez pas le temps d'implémenter ça vous-même de zéro. Vous voulez notamment que ces boîtes de dialogues soient accessibles, et vous voulez pouvoir facilement modifier leur visuel.

Exercice : trouvez le projet open-source sur GitHub qui va le mieux correspondre à ce besoin selon vous.

### 3. Rendu attendu

Argumentez votre recherche :

- listez les projets que vous avez trouvé et dites comment vous êtes tombé dessus
- pour chaque projet finalement non choisi, indiquez pourquoi vous ne l'avez pas choisi
- indiquez pourquoi vous avez choisi le projet que vous avez choisi

Faites tout ça dans le fichier `evaluation/recherche-projet.md` déjà présent dans le dépôt.

## Récap du rendu final

Envoyez-moi en privé sur Discord une archive .zip de votre dossier "exo-a11y" à la fin de l'évaluation. Le fichier doit suivre ce format :

```
nom-prenom-git.zip
```

Ce dossier doit bien contenir le dépôt git (c'est à dire, le dossier ".git" à l'intérieur), ainsi que vous fichiers `evaluation/recherche-projet.md` et `evaluation/questions-git.md` remplis.

## Règles

- vous avez le droit de vous documenter comme vous le souhaitez, reprendre vos notes, reprendre des anciens exercices, aller sur Internet, etc.
- l'évaluation est **individuelle**
- si vous avez fini avant la fin, vous pouvez sortir de la salle discrètement si vous le souhaitez et revenir à 17h35. Si vous décidez de sortir, merci de sortir en silence, et de ne revenir qu'à la toute fin, afin d'éviter les allers-retours dérangeant les autres.

Bonne chance !
