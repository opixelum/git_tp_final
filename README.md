# TP final de Git

## Explication du TP

Bienvenue sur le README du TP final de votre cours d'initiation à Git et Github !

Ce README est le seul et unique énoncé dont vous avez besoin pour réaliser le TP.
Prenez donc bien soin de le comprendre et de le lire **attentivement**.

Voici les règles de base :

* Il est primordial de réaliser les exercices **dans l'ordre**.
* Tout le monde doit avoir un compte Github
* Mettez-vous par groupe de 3 (vous pouvez être 2, ça marche aussi mais vous aurez plus de boulot)

> Je mettrai souvent ce genre de petits message grisé.
> Il s'agit souvent d'informations **très importantes**, lisez les donc bien !

### Exercice 1 : Forkez moi ça ! (5 points)

Le **fork** est une action permettant de copier un dépôt Github entièrement (avec tout son historique) sur son propre compte Github. Ainsi, vous pouvez copier mon dépôt et faire des changements sur la copie sans affecter le mien.

Vous êtes en groupe, il n'y aura donc qu'un seul d'entre vous qui devra **forker** le dépôt.
Décidez entre vous qui ce sera, mais ça n'aura pas d'importance pour la suite.

Le premier exercice consiste donc à **forker** mon dépôt sur l'un des votre, peu importe lequel.

Pour savoir comment forker, lisez ceci : [savoir comment forker](https://github.com/ThomasEcalle/git_tp_final/blob/master/fork.md)

> Pour la suite du TP, vous devrez travailler en équipe sur le dépôt, n'oubliez pas de vous ajouter en tant que collaborateurs !
> Pour ceux qui ne savent plus comment faire, voici un rappel de la démarche : [ajouter des collaborateurs à mon dépôt github](https://github.com/ThomasEcalle/git_tp_final/blob/master/add_collaborators.md).

### Exercice 2 : Présentez-vous ! (5 points)

Dans ce second exercice, vous allez modifier les lignes qui suivent dans le README.md et présenter votre équipe (nom de famille et prénom) ainsi que la date du jour du TP.

> Ce sont ces informations qui me permettront de vous noter, si vous ne vous présentez pas ici, je ne pourrais pas vous noter :)

Noms des étudiants : 
* Benedetti Anto
* Bécot Marjorie
* Benedetti Anto

Date du jour : 10/02/2023

Tout est ok ? 
Faites donc un **commit** et **pushez** moi tout ça sur master (sur **votre** dépôt donc, puisque vous l'avez forké).

> N'importe lequel des collaborateurs peut pusher !

### Exercice 3 : Travail d'équipe ! (5 points)

Pour cet exercice, je vais appeler les collaborateurs :
* collaborateur 1
* collaborateur 2
* collaborateur 3

selon l'ordre dans lequel vous avez mis vos noms dans la présentation.

>(Si vous n'êtes pas un groupe de 3 mais inférieur,  la logique est la même mais l'un d'entre vous fera les tâches des manquants :) )


Il est attendu de tous les collaborateurs de respecter les bonnes pratiques Git et de séparer au mieux leur travail en de multiples petits commits **pertinents** !

**La note prendra compte de cela** !

Toutes les missions peuvent être évidemment réalisées en parallèle par les collaborateurs.

#### Mission collaborateur 1 :

Le **collaborateur 1** est missionné par le client pour ajouter un peu de gaïté au site très morose.

Il va devoir effectuer **tout son travail** sur une branche nommée **"feature/collab-1"**.

Le **collaborateur 1** devra : 
* Ajouter un fichier de style CSS **styles.css** et le lier au fichier **index.html** du projet.
* Mettre le titre **h1** en rouge
* Mettre le titre **h2** en vert
* Mettre une liste numérotée plutôt que par points (**ol** à la place de **ul**)

Une fois que le **collaborateur 1** estime que tout son travail est fini, il peut **push** sa branche sur le dépôt distant.

#### Mission collaborateur 2 :

Le **collaborateur 2** est missionné par le client pour ajouter des informations au site actuel.

Il va devoir effectuer **tout son travail** sur une branche nommée **"feature/collab-2"**.

Le **collaborateur 2** devra : 

* Ajouter une ligne d'information `Prof de git: Thomas Ecalle` où il le souhaite dans la liste déjà présente
* Ajouter une courte description sous chaque élément de la liste (ça peut être complètement Random, je ne juge pas vos talents d'écrivains hors pairs).

Côté HTML, ça peu têtre simplement quelque chose comme : 

```
<li>Mon élément</li>
Ma superbe description
```
Une fois que le **collaborateur 2** estime que tout son travail est fini, il peut **push** sa branche sur le dépôt distant.

#### Mission collaborateur 3 :

Le **collaborateur 3** est missionné par le client pour corriger des erreurs qui se sont glissées sur le site actuel.

Il va devoir effectuer **tout son travail** sur une branche nommée **"hotfix/collab-3"**.

Le **collaborateur 3** devra : 

* Corriger la faute sur le titre **h2**
* Corriger la faute dans l'adresse
* Corriger la faute dans le nom du directeur

Une fois que le **collaborateur 3** estime que tout son travail est fini, il peut **push** sa branche sur le dépôt distant.

### Exercice 4 : Fuuuuuuusion ! (5 points)

Nous approchons de la fin de cet incroyable TP :)

A ce stade, vous devriez avoir 4 branches sur votre dépôt :

* **Master** avec votre commit de présentation
* **feature/collab-1** avec le travail du collaborateur 1
* **feature/collab-2** avec le travail du collaborateur 2
* **hotfix/collab-3** avec le travail du collaborateur 3

Nous allons désormais fusionner l'ensemble des **features** sur la branche **master**.

**ATTENTION !** Je veux être capable de voir vos branches et le travail de fusion effectué !
Débrouillez-vous donc pour avoir les traces de vos branches et donc des commits de merge quoi qu'il arrive.

> Nous avons vu dans le cours comment faire ça :)

> N'importe lequel des collaborateurs peut s'occuper des fusions, je pars du principe que les 3 y participent.

Les fusions doivent se faire dans l'ordre suivant :

#### 1ère fusion :

Fusionnez la branche **hotfix/collab-3** sur la branche **master**.

#### 2ème fusion :

Fusionnez la branche **feature/collab-2** sur la branche **master**.

> Attention ici, au moment du Merge, a bien garder les corrections apportées par le **collaborateur 3** !

#### 3ème fusion :

Fusionnez la branche **feature/collab-1** sur la branche **master**.

> Attention ici, au moment du Merge, a bien garder les modifications apportées par les **collaborateurs 2 et 3** tout en y ajoutant les modifications du **collaborateur 1** !


### Fin des exercices :

Tout est ok ?
Alors n'oubliez pas de **push sur master** le résultat de toutes ces fusions sur votre dépôt distant et ... ce sera tout pour ce TP :)

### Comment vais-je corriger ?

J'ai développé un script qui va me permettre, à la fin du temps imparti, de **cloner** tous vos repository automatiquement sur mon ordinateur, en **local**.

**Il est donc impossible de continuer le travail après le temps imparti** car je n'aurai en local que la version figée au moment du script, et donc sans vos changements d'après ;)

### Notation :

La notation est assez simple et vous donne un 10 plutôt facile : 

 - Exercice 1 : 5 points
 - Exercice 2 : 5 points
 - Exercice 3 : 5 points
 - Exercice 4 : 5 points

Le **10** est donc plutôt simple à avoir si vous suivez les étapes correctement.

Les exercices **1** , **2** et **4** sont notés en commun.
L'exercice **3** sera plus personnel car je noterai chaque collaborateur différemment.

> Attention, étant donné que les exercices **1** et **2** sont très simples, je serai stricte sur le respect des bonnes pratiques pour les exercices **3** et **4**

**Bon courage :)**


