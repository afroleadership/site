---
layout: cours
title: 3 - Trier et filtrer Les bases des feuilles de calcul
date:   2017-02-10
author : Pierre Chrzanowski	
categories: cours
description: "A la fin de ce module, vous aurez appris comment télécharger des données, les importer dans une feuille de calcul, comment les nettoyer et les interpréter avec les fonctions trier et filtrer."
tags: [fondamentaux, données, introduction]
---

## Introduction

L'outil le plus basique pour la manipulation des données est la feuille de calcul. Les données contenue dans une feuille de calcul sont dans un format structuré, lisible par les machines, qui peut être trié et filtré. Dans d'autres recettes de ce manuel, vous allez apprendre à utiliser de simples feuilles de calcul, un outil pourtant puissant pour faire des sommes simples (trouver le total, la moyenne, etc.), appliquer un traitement de masse, ou réaliser des graphiques ou des tableaux. 

A la fin de ce module, vous aurez appris comment télécharger des données, les importer dans une feuille de calcul, comment les nettoyer et les interpréter avec les fonctions "trier" et "filtrer". 

## Un aperçu des feuilles de calcul

Aujourd'hui, les feuilles de calcul sont répandues et un grand nombre de personnes les utilisent quotidiennement. Une grande variété de tableurs et d'applications existent. Par exemple, Microsoft Office propose Excel, LibreOffice avec Calc… Sans surprise, Google a décidé de proposer un service de tableur dans sa suite Google Docs. Comme il ne requiert pas d'acheter ou d'installer un logiciel, nous utiliserons les feuilles de calcul Google pour ce cours. (Notez qu'il existe un logiciel libre, EtherCalc, qui propose les mêmes fonctionnalités, disponible notamment sur : http://framacalc.org)

Selon ce que vous voulez faire, vous pouvez choisir d'utiliser un logiciel de tableur différent. Voici quelques considérations à connaître avant de choisir votre outil favori : 

## Créer une feuille de calcul et télécharger les données.
Dans ce cours nous allons utiliser Google Docs pour manipuler (/convertir) nos données - Cela vous permet de commencer immédiatement sans avoir besoin d'installer un logiciel. Puisque les données que nous utilisons sont déjà publiques, nous n'avons pas besoin de nous soucier du fait qu'elles ne sont pas stockées sur notre disque dur (/en interne).
 

## Pas à pas : Créer une feuille de calcul et télécharger les données

1. Rendez-vous sur Google docs.
2. Si vous n'êtes pas connecté sur Google docs, connectez-vous.
3. La première étape est de créer une nouvelle feuille de calcul.
4. Faites-le en cliquant à gauche sur le bouton "créer" et sélectionnez "feuille de calcul". 
5. Cela va créer une nouvelle feuille de calcul.
6. Téléchargeons maintenant des données.
7. Vous allez avoir besoin du fichier que nous avons téléchargé sur le site de la Banque Mondiale dans le tutoriel précédent. Si vous n'avez pas suivi le tutoriel ou que vous avez perdu le fichier : téléchargez le ici.
8. Dans votre feuille de calcul, sélectionnez "importer" dans le menu "fichier". Cela va ouvrir une boîte de dialogue.
9. Sélectionnez le fichier que vous avez téléchargé.
10. N'oubliez pas de sélectionner "insérer des nouvelles feuilles" et cliquez sur import 

### Navigation et utilisation de la feuille de calcul

Maintenant que nous avons téléchargé quelques données, il faut se familiariser avec les feuilles de calcul. Une feuille de calcul est un tableur comprenant des cellules dans lesquelles on peut inscrire des données. Les cellules sont organisées en "lignes" et "colonnes". Typiquement, les lignes sont identifiés par des nombres et les colonnes par des lettres. Cela signifie aussi que les cellules peuvent être traitées par le biais des coordonnées des "colonnes" et "lignes". La cellule A1 désigne la cellule de la première ligne de la première colonne, A2 celle de la deuxième ligne, B1 celle de la deuxième colonne et ainsi de suite.

Pour modifier des données dans une cellule, cliquez dessus et commencez à taper - Cela changera le contenu de la cellule. Une navigation simple peut être réalisée de cette manière ou via un clavier. 
Vous trouverez une liste de raccourcis clavier utiles plus bas :

Astuce : entraînez-vous un petit peu et vous allez vite devenir plus à l'aise avec le clavier !

### Verrouillage des lignes et des colonnes

La feuille de calcul sur laquelle nous travaillons est plutôt grande. Vous allez voir qu'en faisant défiler la colonne, les labels de colonnes disparaîtront fréquemment. La même chose se produira avec le nom des pays. Pour éviter ça vous pouvez verrouiller les lignes et colonnes pour ne pas qu'elles disparaîssent. 

Pas à pas : verrouiller la ligne supérieure

1. Allez sur la feuille de calcul avec vos données et faites la défiler jusqu'en haut.
2. En haut à gauche au niveau des labels de colonnes et de lignes vous verrez une petite zone rayée.
3. Survolez la barre rayée en haut de la case où est inscrit le chiffre "1". Un curseur en forme de main doit apparaître. Cliquez et tirez le vers le bas sur une ligne.
4. Essayez de faire défiler. Vous remarquez comment les colonnes du haut restent fixes ?

#Trier les données
La première chose à faire quand vous découvrez un nouveau jeu de données, c'est de vous orienter. Cela nécessite de regarder les valeurs maximales et minimales puis de trier les données pour que cela prenne du sens. Regardons les colonnes. Nous avons des données sur le PIB, les dépenses de santé et l'espérance de vie. Maintenant partons explorer les données par un simple tri. 

#Pas à pas : trier un jeu de données
1. Sélectionner la feuille entière que vous voulez trier. Pour se faire, cliquez sur le coin en haut à gauche, entre les noms des lignes et des colonnes. 

2. Sélectionner "Trier la plage" depuis le menu "données" ce qui va ouvrir une nouvelle fenêtre. 
3. Cochez "Données avec ligne d'en-tête" 
4. Sélectionner la colonne que vous voulez trier dans le menu dépliant. 
5. Triez par PIB—Quel pays a le plus faible ? 
6. Essayez de nouveau avec d'autres valeurs, pouvez vous trier de manière ascendante et descendante ? 

Astuce : faites attention ! Une erreur commune est d'oublier de sélectionner toutes les données. Si vous triez sans sélectionner toutes les données, les lignes ne vont pas correspondre. 

Une version de cette recette peut être trouvée dans le manuel. 

## Filtrer les données

L'autre chose faite couramment avec les jeux de données est de les filtrer les valeurs que vous ne voulez pas voir. Avez vous remarqué que certains "Noms de pays" ne sont pas corrects ? Vous trouverez certaines choses comme "World",  “North America” et “Arab World”. Filtrons les. 

**Pas à pas : filtrer des données**

1. Sélectionnez tout le tableau. 
2. Sélectionnez "filtre" depuis le menu "données"
3. Vous devriez maintenant voir des triangles à côté des noms de colonnes sur la première ligne.
4. Cliquez sur le triangle à côté du nom du pays.
5. Vous devriez voir une longue liste de noms de pays dans la case.
6. Trouvez ceux qui ne sont pas des pays et cliquez dessus (la case verte cochée disparaîtra). 
7. Vous avez réussi à filtrer votre jeu de données.
8. Allez-y, jouez avec les données ! Les données ne seront pas supprimées, elles ne seront seulement pas affichées. 

Une version de cette recette peut aussi être trouvée dans le guide du datajournalisme.

**Résumé**
Dans cette section nous avons acquis des compétences fondamentales pour utiliser une feuille de calcul. Nous avons parlé de la saisie de données et de comment trier et filtrer des données en utilisant un logiciel de feuille de calcul. Dans le prochain cours nous parlerons d'analyse de données et vous présenterons les formules.

**Lecture complémentaires et références**
Aide Google sur les feuilles de calcul
