# Rapport_Stage

Ce stage a lieu dans l'entreprise CGI, sur leur site à Grenoble. CGI est une des plus grandes ESN mondiale, d'origine Canadienne, mais qui possède de nombreux site en France. Cette entreprise propose des services ou conseils dans les technologies de l'informatique.

Le projet sur lequel j'ai été assigné à pour but de livré un produit à un client. Je ne peux cependant pas donner le nom du client où rentrer trop dans les détails dû à la confidentialité du sujet. Ce projet dure déjà depuis plusieurs année, une version est déjà en production et utilisée.
Plusieurs équipes travaillent sur ce projet, et j'ai été assigné à l'une d'entre elles. Mon équipe s'occupe de toute la partie application web, qui est l'élément central. Comme dis précédement, l'application web est déjà en production, cependant ce n'est pas la version finale, ainsi mon équipe travaille sur l'implémentation des nouvelles fonctionnalités demandées par le client. 

Sujet : Le projet ayant commencé il y a plusieurs années, certaines parties ont été developpées en utilisant des éléments trop anciens qui ne sont plus supportés. Un de ces éléments est le plugin Silverlight, une alternative de Microsoft à Adobe Flash qui n'est supporté que par Internet Explorer. Ma première mission consiste donc a réintegré un élément qui avait été fait en Silverlight. L'application été initialement codé en .NET, mais est en train de basculer en Angular. Ainsi, je dois recréer l'élément qui était fait en Silverlight dans la nouvelle application Angular. Je devrai également m'occupé du back-end de cette partie en Java spring boot.

## Semaine 1

Lundi : présentation et integration à l'entreprise

Mardi et Mercredi : "e-learning" de l'entreprise pour apprendre les différentes règles de l'entreprise

Jeudi et Vendredi : "e-learning" pour apprendre certaines bonnes pratiques de codages
- Les e-learning sont des auto formations faites par l'entreprise, composé de vidéos ou de texte pour intégré les nouvelles personnes à l'entreprise.


## Semaine 2

Lundi à Jeudi : Formation à certaines technologies pour le front

Vendredi : Formation côté back-end

## Semaine 3

Lundi à Vendredi : Continuation de la formation aux technologies côté back-end

Vendredi : Réunion pour une explication gloable du projet et son fonctionnement

## Semaine 4

Lundi : Réunion pour une explication en détail du travail à effectuer

Mardi : Mise en place de l'environnement de travail (VM et installations lié au projet)

Mercredi à Vendredi : Début du travail sur ma tâche, mise en place du front end, répartition en plusieurs composants.
- Le projet ayant commencé il y a plusieurs années, j'ai pour l'instant passé beaucoup de temps à lire du code pour comprendre le fonctionnement du projet et les règles/bonnes pratiques de codage. J'ai donc surtout essayer de prendre en main le front-end du projet pour l'instant.

## Semaine 5

Mardi et Mercredi : Suite du travail sur le front end, début du travail sur le premier composant

Mercredi : Affichage des premiers éléments en utilisant des données mockées pour simuler une vrai base de données

Jeudi et Vendredi : Suite du travail sur le front-end du premier composant

## Semaine 6

Lundi : Suite du travail sur le front-end, ajout d'images au composant

Mardi : Suite du travail sur le front, changement dans la partie html et css pour un code plus propre

Mercredi : Choix d'une nouvelle librairie pour gérer toutes les dates de l'application, car l'ancienne était trop grosse. Pour ce faire, j'ai comparé différentes librairies et pris la décision finale avec une autre personne de l'équipe.

Jeudi : Suite du travail sur le front et intégration de la nouvelle librairie pour les dates.

Vendredi : Démo et retrospection de fin de sprint avec l'équipe

## Semaine 7

Toute la semaine : Travail sur le front, finalisation d'une première version du premier composant et merge request.

## Semaine 8

Lundi à Mercredi : Retour suite à la première merge request faite suite à la première version. Correction/amélioration du code suite aux commentaires reçu.

Jeudi et Vendredi : Nouveaux retours sur une nouvelle merge request avec toutes les corrections de la précédente appliquée. Travail sur l'amélioration du code suite aux retours.

## Semaine 9

Lundi et Mardi : Nouvelle merge request et nouveaux retours. Travail d'amlioration sur un composant existant dans un dossier "shared", dossier qui permet aux composants qu'il contient d'être utiliser par n'importe quel autre composant de l'application. Le composant permet à l'utilisateur de rentrer un date via une textbox ou un calendrier. Modification du composant pour utiliser la nouvelle librairie choisi, et mettre à jour le code pour correspondre au projet.

Mercredi à Vendredi : Amélioration du code du composant suite aux retours sur la merge request.

## Semaine 10

Lundi : Suite des amélioration suite de la merge request

Mardi, Mercredi et Vendredi : Travail sur les composants partagés permettant de créer des datepicker et timepicker. Changement pour qu'ils utilisent tous les deux la nouvelle librairie de date (le datepicker avait déjà été changer). De plus, amélioration pour corriger certains bug sur ces composants et qu'il ait un comportement plus adéquat à ce qui est attendu.

## Semaine 11

Lundi : Malade donc pas de travail ce jour

Mardi à Jeudi : Suite du travail sur le front, notamment sur les composants datepicker et timepicker pour corriger les bugs. Inclusion du composant timepicker dans datepicker pour que ce soit lui qui gère toute la partie date directement.

Vendredi : Travail sur des formations pour passer sur la partie backend. Le frontend n'est pas forcement fini, mais mon supperviseur n'est pas la pour me faire des retours dessus, je commence donc à m'avancer sur la partie back.
Présentation à mon tuteur ainsi qu'une autre personne de l'avancée du stage pour voir en j'en suis.

## Semaine 12

Mardi : Suite du travail sur la partie backend, et discution avec mon superviseur pour voir différents points sur la partie backend.

Mercredi : Petit retour rapide sur le frontend le matin suite aux retours sur ma dernière merge request. Rapidement fini la partie frontend, reprise du travail sur le backend dans l'après-midi.

Jeudi et Vendredi : suite de la formation sur le backend.

## Semaine 13

Lundi : Fin de la formation backend.

Mardi à Vendredi : Travail sur le backend pour le projet : travail de la création des routes pour l'api. Reflexion sur la manniere dont seront transmisent les données à la partie front et création des routes en accordance avec les décisions établies (notamment les données à transmettre en entrée et en sortie de chaque route).

## Semaine 14

Lundi à Vendredi : Travail d'étude sur les différents indicateurs de la base de données. L'objectif est de voir les différentes bases ainsi que les champs qui la composent qui sont utiles. Reprise des champs important pour construire les entités dans le backend.
Début de la création des différentes fichiers du backend (dans les dossiers entity, repository, service, etc.)

## Semaine 15

Lundi à Vendredi : Travail sur le backend, réalisation du controller, repository, service et des fichiers complémentaires nécessaires (models, mappers, etc.)

## Semaine 16

Lundi et Mardi : Problème de VPN, hors il me faut le VPN pour accéder à ma VM et donc mon code. Je n'ai donc pas pu avancer sur mes tâches ces deux jours

Mercredi et Jeudi : Travail de résolution des bugs au niveau du backend, notamment du repository

Vendredi : Fin de correction des bugs et debut de mise en relation du front et du back

## Semaine 17

Semaine de vacances

## Semaine 18

Lundi et Mardi : suite de la mise en relation du front et du back. Au final toutes les requêtes fonctionnent, mais il y a des problèmes de performances qui causent des lenteurs dans l'application.

Mercredi : Réglage des problèmes liés aux lenteur. Début de création d'un tableau pour afficher les données reçu.

Jeudi et Vendredi : Suite du travail sur le tableau.


## Semaine 19

Lundi et Mardi : Suite du travail sur le tableau, puis travail sur la pagination.

Mercredi : Travail sur la pagination du tableau et différents éléments d'affichage pour être plus ergonomique et en accord avec ce qui est voulu. 

Jeudi et Vendredi : Mon responssable part en vacance, il a donc fait une revue sur mes merge request. Nous avons donc fait une réunion pour qu'il m'explique les différents retour sur mon code, ainsi que pour s'accordé sur la suite, que je sache bien quoi faire le temps qu'il est abscent. J'ai ensuite passé le reste des deux jours à traité ses retours sur mes merge request.

## Semaine 20

Lundi et Mardi : Travail sur le back pour améliorer le code, et sur la pagination côté backend pour le tableau.
