# But
Dans ce TP, nous allons tester Scrum à l'aide de 2 outils :
- Trello qui va nous permettre de créer des boards.
- [https://www.burndownfortrello.com/](Burndown for Trello) pour suivre l'avancement sous forme de burdown chart.


# Intialisation
Créer un compte par membre de l'équipe sur Trello.
Sur l'un des comptes :
1. Créer le premier board en cliquant sur le bouton bleu "Créer" (dans le menu) puis "Créer un tableau".
2. Donner pour titre "Backlog" et en visibilité "espace de travail"
3. Puis ouvrir le sous-menu et ajouter vos camarades.


# Remplir le Backlog
On va remplir le backlog avec nos user story. Puis on va en sélectionner 1 par membre de l'équipe que l'on va travailler pour voir si on peut les mettre au prochain sprint.


1) Sur le tableau créer précédemment, créer 4 listes :
- ToDo
- Ready
- Sprint 1
- Done 🎉

```
Pour ce TP, on va se contenter de 4 listes, mais pour votre projet n'hésiter pas à en créer/supprimer selon votre choix d'organisation.
Pour que Burndown for Trello fonctionne correctement, la dernière colonne dois avoir dans son nom le mot clée "done".
Pourquoi l'émoticone 🎉 ? Testez-le en déplaçant une user story dans la liste.
```

En équipe, découper le projet tuteuré sous forme de User story sans rentrer dans le détail de celle-ci.


Puis chaque membre en sélectionne une qui lui parait importante et la travail/découpe pour qu'elle sois INVEST.
N'hésitez pas à ajouter une description à la carte si ça vous semble nécessaire.
Quand c'est fait, déplacer la/les user story dans la liste Ready.


# Planning Poker
Ce sprint doit permettre d'avoir une story de référence pour les prochaines estimations. On va donc sélectionner celle qui vous parait la plus facile et lui donner une priorité 1 (P1 = les plus prioritaires). Priorisez les autres  en fonction de leur importance, mais en dessous de celle-ci.

Le PO qui a redirigé la P1 présente aux autres qui vérifie qu'ils l'on bien comprise et qu'elle est bien INVEST.
Donner lui une "definition of done" et ajouter là dans sa carte.

Puis on l'estime en nombre de jours avec le planning poker et on la découpe en tache.
```
Suite de Fibonaci :  1, 2, 3, 5, 8, 13, 21
```


Sur Trello, ajouter le tableau sprint 1 avec pour liste :
- Stories (NoBurn)
```
NoBurn permet à [https://www.burndownfortrello.com/](Burndown for Trello) d'ignorer les elements dans cette liste
```
- TODO
- In progress
- Done

Copier la story estimée (quand on ouvre une carte, il y a un bouton pour copier.) dans la colonne Story (NoBurn) du sprint 1. Rédigez les différentes tâches de la story dans la colonne TODO du sprint 1. Ajouter l'estimation de la story ainsi que le temps par tache dans le titre entre parenthèses.

```
On met l'estimation entre parenthèses dans le titre pour que [https://www.burndownfortrello.com/](Burndown for Trello) puisse la récupérer.
```
Dans un sprint, il peut y avoir de nombreuses user stories, pour bien comprendre quelle tâche correspond à quelle story je vous conseil d'utiliser les étiquettes. Pour cela, ouvrez une carte et dans la partie à droite utilisez le bouton étiquette. Vous pouvez aussi créer des délimiteurs en ajoutant une carte ayant pour titre "---".

Formalisez un objectif pour le sprint et ajouter une carte dans "Story (NoBurn)" pour se rappeler de celui-ci. 
Sélectionnez les user stories répondant à cet objectif.

Pour un premier sprint, je vous conseille de partir sur une durée de 6 semaines en comptant 1 jour de travail par semaine par membre de l'équipe. Expliquez les story, estimez-les par rapport à la story de référence, découpez-les en tache et ajouter le tout sur Trello jusqu'à ce qu'il n'y ait plus de places dans le sprint.

À partir de là, on pourrait attaquer le sprint, mais malheureusement, nous ne disposons pas de 5 jours de cours pour amener ce sprint à son terme. On va donc en simuler un, plus court pour voir comment ça fonctionne.

# Simuler un sprint
Nous allons chercher à réaliser le TP du premier cours sous forme de sprint. 

Commencez par créer un tableau "Sprint TP cookies 🍪" avec les mêmes listes que "Sprint 1". 
Ajouter la story de référence que vous estimerez à 13 points.

Ajoutez lui 2 taches :
- "(1) Work Breakdown Structure" avec pour déscription : ajouter les taches du sprint 1 à la mindmap du premier TP
- "(10) GANTT" ou "(10) PERT" selon celui que vous privilégiez

Ajoutez l'user story "Matrice des risques" avec pour taches :
- "(9) Lister les risques et solutions", créez en une par nombre de personnes de l'équipe moins 1.
- (2) Afficher sous forme de matrice

## Burndown chart
Rendez-vous sur [https://www.burndownfortrello.com/](https://www.burndownfortrello.com/), connectez votre compte Trello et afficher le sprint cookies.
Pour l'instant, c'est un peu vide, commençons par préciser une durée de sprint de **2 jours** en cliquant sur le bouton "Settings" puis en précisant ses dates (aujourd'hui et demain). Profitez-en pour sélectionner comme "Tracking Units" "points" avant d'enregistrer.
Revenez sur le diagramme, une jolie fonction linéaire orange s'affiche. 🤩

On va attaquer le sprint en traitant 2 taches en parallèle. Le but est de terminer uniquement la première.
Une personne se chargera donc de "(1) Work Breakdown Structure", il peut assigner dessus à l'aide du bouton "membres" sur la carte et la placer dans la colonne "In Progress". Et c'est parti pour ajouter un nouveau commit à notre Github.

Les autres font de même avec la carte "(9) Lister les risques et solutions"

**Dès que "(1) Work Breakdown Structure" est finis,** déplacer la carte dans la colonne "Done". Modifier le titre de "(9) Lister les risques et solutions" en "(9) Lister les risques et solutions [N]" avec N le nombre de personnes ayant travaillé sur cette tache.


```
Burndown for Trello interprète un nombre entre crochets dans le titre d'une carte comme le temps passé sur celle-ci. 
```

Affichez le brundown chart, que voyez vous ? Pas grand chose ? Et au niveau des progress bars et du tableau en bas de page ?

## Power Up Github
Maintenant, imaginez, vous pensez que quand vous avez rempli le "Work Breakdown Structure" vous avez oublié une tache 😶 ! Mais ça fait longtemps et peut-être qu'elle a seulement était retiré après coup, car peu pertinent 🤔. Pour vérifier ça, ce serait bien de pouvoir retrouver facilement la modification que l'on vient de faire (= le commit) depuis la carte.

Pour cela, nous allons ajouter un "power up", une extension à Trello pour associer des commits Github à nos cartes. Rendez-vous sur la page du [Power Up Github](https://trello.com/power-ups/55a5d916446f517774210004/github) et avec le bouton bleu "Ajouter un power up" ajouter celui-ci sur notre "Sprint TP cookies".
Ouvrir la carte "(1) Work Breakdown Structure", maintenant à droite, un bouton "Github" apparaît.


Cliquer dessus, lier votre compte Github puis sélectionnez  "Joindre une validation" qui va nous permettre de retrouver nos commits (oui la traduction ... 💩). Sélectionnez le répository du TP et la branche "main", vous devriez pouvoir retrouver le commit.
Validez, une nouvelle section apparaît avec les liens vers les modifications.


Et voilà vous avez vu le déroulement d'un sprint. Ne finissez pas celui-ci, mais passez à la suite.


# Sprint en autonomie
J'espère que vous avez bien compris, car maintenant, vous allez être en autonomie.

Et on va commencer par estimer la durée du sprint, en fonction du temps qu'il vous reste. 
Ce serait bien de prévoir au moins 2 sprints (pour faire une review et une rétrospective).
Dans l'idéal, il faudrait en avoir 1 par membre de l'équipe (pour que tout le monde puisse faire scrum master).

Désignez un premier Scrum Master (qui changera à la fin de chaque sprint).


Pour le rôle de PO, c'est moi qui m'en occupe et voici les user stories :

🎺🎺🎺

**User Story 1**
Valider que chaque membre de l'équipe ait compris le fonctionnement des différents outils. Critère d'acceptation : Vous venez me voir et je valide (ou pas)

**User Story 2**
Décider du mode d'organisation pour le projet tuteuré. 
Critère d'acceptation : Une courte explication de ce que vous voulez mettre en place, pourquoi, ce que vous avez prévu de faire si ça ne fonctionne pas.

**User Story 3** 
Préparer un échange pour valider avec le tuteur le mode d'organisation choisi et son rôle vis à vis de celle-ci.
Critères d'acceptations : 
1. Un membre de l'équipe joue le rôle du tuteur et anticipe sa réponse.
2. Une personne a pris la responsabilité de contacter le tuteur (au nom de l'équipe)

🎺🎺🎺

```
Cela reste un exercice, les story 2 et 3 ne sont pas vraiment indépendante et sont peut-être trop grosse par apport à la durée de vos sprint. N'hésitez pas à les redécouper (en ayant quand même un incrément à la fin)
```
