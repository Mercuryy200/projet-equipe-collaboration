# Rapport de laboratoire Git - Équipe [Les Tortues Ninja]

## 1. Membres de l'équipe

- Membre 1 : Rima Nafougui
- Membre 2 : Julien Guibord
- Membre 3 : Jimmy Chhan
- Membre 4 : Charly Alcide Smith

## 2. Résumé des parties complétées

### Partie 1 : Configuration initiale

## [Décrivez brièvement ce que vous avez fait et ce que vous avez appris]

Membre 1: J’ai créé le dépôt local sur mon ordinateur avec la commande git init, puis ajouté un fichier README.md pour décrire le projet. Ensuite, j’ai fait mon premier commit avec git add et git commit. J’ai aussi créé le dépôt distant sur GitHub et relié les deux avec git remote add origin, avant d’envoyer le projet en ligne avec git push.

Membre 2 et 3: Le rajout d'un fichier pour énoncer mon nom et rôle dans ce projet.

Apprendre le début/configuration d'un projet GIT.

### Partie 2 : Ajout des collaborateurs

## [Décrivez le processus d'invitation et de clonage]
Membre 1: Je me suis connecté à mon compte GitHub et je suis allé dans la section Settings puis Collaborators de notre dépôt. J’ai ensuite cliqué sur Add people, puis entré le nom d’utilisateur GitHub de chaque membre de l’équipe. Après avoir sélectionné leurs comptes, j’ai cliqué sur Add [nom] to this repository pour leur donner accès au projet.

Membre 2 et 3: L'invitation se fait sur GitHub avec le nom des collaborateurs, de plus, sur Visual studio Code on copie
le lien html de GitHub du repository pour ainsi lier le répertoire entre GitHub et vscode.

### Partie 3 : Première collaboration

## [Expliquez comment vous avez créé vos fichiers individuels]
Membre 1: J’ai créé un fichier nommé membre1.txt dans Visual Studio Code. J’y ai inscrit mon nom, mon rôle de chef d’équipe et mes responsabilités, puis j’ai enregistré et envoyé le fichier sur GitHub.

En utilisant un git pull on prend le projet mis à jour et on rajoute nos propres
tâches pour ensuite le envoyer la version corrigé pour que les autres collaborateurs ont accès.

### Partie 4 : Résolution de conflits

## [Décrivez le conflit rencontré et comment vous l'avez résolu]

La section 4 voulait faire en sorte que le membre 1 et 2 entre en conflit
puisque sans git pull du 2e membre sa modification entre en conflit avec la version
actuelle qui contient une modification à la même place dans le fichier.

### Partie 5 : Collaboration HTML

## [Expliquez votre travail sur la page web]
Membre 1: J’ai créé le fichier index.html dans Visual Studio Code. J’y ai ajouté la structure de base d’une page web avec le titre « Projet d’équipe » et un en-tête « Notre projet collaboratif ». J’ai ensuite enregistré et envoyé le fichier sur GitHub pour que les autres membres puissent compléter la page.

L'ajout d'une section dans le fichier index.html, de plus, faire face à un push rejeté suite à un git pull inexistant avant la manipulation et comment résoudre ce problème en choisissant une des 2 versions disponible.


### Partie 6 : Utilisation des branches

## [Décrivez la création et la fusion de la branche]
Membre 1: J’ai créé une nouvelle branche appelée ajout-style pour ajouter un fichier style.css et relier cette feuille de style à la page index.html. Une fois les changements terminés, j’ai fusionné la branche ajout-style avec la branche principale main afin d’intégrer les nouveaux styles au projet. Enfin, j’ai envoyé les modifications sur GitHub pour que toute l’équipe puisse voir la page web mise à jour avec le design CSS.

Membre 2 et 3: Ensuite, retourner dans le main pour merge la branche et git
push pour que tous les membres puissent git pull et avoir le style.css

### Partie 7 : Situations réalistes

## [Résumez les différentes situations expérimentées]

Premièrement une situation qui ne possède pas de conflit puisque
les modifications ont été fait dans 2 fichiers différents.
Deuxièmement, effectuer une manipulation où le git pull n'a pas été
fait au début. Troisièmement, effectuer une manipulation pour savoir
comment annuler un commit. Finalement, obtenir un historique de tous les
modifications du projet avec l'aide d'un graphique.

## 3. Captures d'écran

(Dans les dossiers de chaque membre)

## 4. Difficultés rencontrées

### Difficulté 1

- **Problème** : J'ai mal écris un commit.
- **Solution** : J'ai utiliser "git commit --amend", une fois
le commit réécrit j'ai sauvegarder, fermer mon NotePad et j'ai fait "git push".

### Difficulté 2

- **Problème** : Dans Partie 7/Situation 2, j'ai eu le message d'erreur attendu,
  mais après la résolution du conflit, je ne pouvait plus commit et j'avais cette erreur:
  "Your branch is ahead of 'origin/master' by 2 commits."
- **Solution** : Git m'a proposer de "use 'git push' to publish your local commits"
  et ça a fonctionner avec un commit généré par git disant :
  "Merge branch 'master' of https://github.com/Mercuryy200/projet-equipe-collaboration"

### Difficulté 3

- **Problème** : Trouver une tache supplémentaire pour le membre 4.
- **Solution** : J'ai fait quelques modifications pour avoir un commit pour le membre 4
  et sinon j'ai ajouté une trace de plus dans les actions du membre 3.

## 5. Apprentissages

### Ce que nous avons appris sur Git

- [Apprentissage 1]
  Il est important de faire un git pull avant de travailler,
  sinon des situations de conflit peuvent survenir.

- [Apprentissage 2]
  Lors d'un conflit, on peut accepter une des deux versions,
  ou accepter les deux versions en même temps, puis faire un
  commit qui décris la résolution.

- [Apprentissage 3]
  Les branches permettent de travailler indépendement de la
  vraie version du programme et donc d'éviter les situations
  de conflit.

### Ce que nous avons appris sur le travail d'équipe

- [Apprentissage 1]
  La communication est importante pour savoir si on peut pull
  le travail de quelqu'un ou si on devrait attendre qu'il ait
  terminé ses tâches.
- [Apprentissage 2]
  Il est important de travailler autant que possible sur des
  fichiers différents pour éviter les situations de conflits.

## 6. Conclusion

## [Rédigez une courte conclusion (5-10 lignes) sur votre expérience globale du laboratoire]

L'expérience de ce laboratoire était bien puisqu'il nous montrait comment manipuler certaines
commandes git avec la collaboration de GitHub et savoir l'importance des étapes à suivre pour
travailler en équipe. De plus, simuler des situations qui peuvent arriver, par exemple: oublier
de faire un git pull avant de faire des modifications, savoir comment travailler en équipe
avec des git push git pull, travailler sur des branches + merge et comment gérer des conflits
entre commits.
