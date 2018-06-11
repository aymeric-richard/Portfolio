---
layout: default
---

# CIL'Cowding, interpréteur de code IL éducatif

## Contexte

[<img src="{{ site.imagesLocation | absolute_url}}/screenshot_cilcowding_mini.png" class="realization-mini"/>]({{ site.imagesLocation | absolute_url}}/screenshot_cilcowding.png)

Dans le cadre de ma formation à IN'TECH, nous avons décidé avec mon groupe de projet de consolider notre compréhension du fonctionnement de la chaine de compilation d'un programme. C'est ainsi que nous avons créé de toute pièce CIL Cowding, un projet dont la brique principale est le développement d'un interpréteur de bytecode <abbr title="Intermediate Langage">IL</abbr>.

## Implémentation

Le fil conducteur est le développement d'un interpréteur de CIL (Common Intermediate Language, ie Bytecode C#). Couplé à une interface graphique, le logiciel CIL'Cowding explique le fonctionnement interne d'un programme - Pour se faire, l'utilisateur écrit en programme en CIL, qui est interprété par CIL-Cowding. Ce dernier affiche en direct un visuel de la pile d'appel.
Ce projet a pour cible les développeurs, le but étant de faciliter l'apprentissage du fonctionnement interne d'un programme, notamment de la pile d'appel.

La partie majeure du projet porte sur l'architecture de l'interpréteur, qui comprends des éléments clés organisés par un engine, qui va construire le programme à partir du code source écrit par l'utilisateur.
Ces éléments sont composés d'un tokenizer et d'un analyzer dont la fonction est de découper et trier le code, pour ensuite passer la main à la pré-exécution et la construction d'un AST. Cet AST sera capable d'exécuter les lignes de code une par une.

Synthétiquement, CIL'Cowding dispose des fonctionnalités suivantes :

* Comprendre un langage
* Exécuter un programme en IL
* Déboguer un programme step by step
* Utilise des librairies externes (api)
* Modélise la pile d'appel en temps réel

## Compétences

* [C# .NET]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/csharpdotnet)
* [Git]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/git)

## Liens

<a href="https://github.com/Cil-Cowding/Cil-Cowding/tree/develop" class="fab fa-github"> Voir sur Github</a>