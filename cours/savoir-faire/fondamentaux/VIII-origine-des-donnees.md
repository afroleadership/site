---
layout: cours
title:   8 - L'origine des données
date:   2017-02-03
author : Pierre Chrzanowski	
categories: cours
description: "Dans ce tutoriel nous allons parler des plus fréquentes idées fausses et des pièges à éviter quand on commence à analyser et visualiser des données. C'est seulement quand on connaît les erreurs habituelles qu'on peut les éviter dans son propre travail et les détecter quand elles sont citées par erreur dans le travail des autres."
---

Il est important de bien documenter la provenance des données (l'origine et l'historique d'un jeu de données). Chaque utilisateur qui a modifié un jeu de données doit pouvoir être identifié. Il est responsable des traitements et des nettoyages des données qu'il a effectué. Pour un fichier Excel, il faut indiquer toutes les étapes de transformation des données. Les outils avancés de traitement des données (comme Open Refine, anciennement Google Refine) permettent eux d'exporter directement cet historique de traitement avec le jeu de données lui-même. Si des programmes (logiciels) ont été écrits spécifiquement pour traiter les données, ils doivent être fournis en même temps que les résultats de vos traitements. Le code source de ces programmes doit être ouvert et partagé, par exemple sur Github.

## Les outils pour documenter votre travail sur les données

Il y a de nombreux moyens de documenter les traitements que vous effectuez sur les données. Parfois, il suffit de rédiger une explication détaillée et de fournir une feuille de calcul pour chaque étape intermédiaire du traitement.

Pour les projets plus élaborés, vous pouvez utiliser des outils dédiés - la plateforme Socrata permet par exemple de suivre et de partager facilement les traitements effectués sur des feuilles de calcul.

Vous pouvez aussi utiliser Data Hub, une solution libre qui permet de diffuser en un seul jeu de données plusieurs versions d'une même feuille de calcul. (L'outil permet aussi de générer automatiquement une interface de programmation (API) sur laquelle vous pouvez connecter votre application.)

Si vous voulez être perfectionniste, vous pouvez aussi utiliser des solutions de contrôle de version. Elles permettent de noter chaque modification effectuée sur les jeux de données, mais aussi de revenir en arrière (restaurer la version précédente) en cas de besoin ou d'erreur. 

## Quelques astuces pour documenter votre travail 
1. Faites un lien vers le jeu de données initial et mentionnez toujours la source des données que vous avez utilisé, 
2. Indiquez clairement tous les traitements que vous avez effectué sur les données. Cela permettra de vérifier que vous n'avez pas fait d'erreurs ou de fausses manipulations. 
C'est aussi important pour vous que pour les autres utilisateurs !
