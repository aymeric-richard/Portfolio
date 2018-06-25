---
layout: default
---

# Création d'un gestionnaire de container pour Samba, nom de code Galaxy

## (Contexte) Docker n'a qu'à bien se tenir

Pour gérer plus facilement les logiciels serveurs et indépendamment des machines ou des environnements clients, je devais mettre en place un gestionnaire de conteneur.

## Implémentation

Chroot
Changement de racine, installation de samba en chroot. Nouvel environnement, prison (contenainer).
Copier coller une prison sur une autre machine et ça fonctionne pareil.

Procédures
* Compiler Samba depuis les sources (toutes les versions)
* Mettre en prison ces versions
* Faire des tests de démarrage, stop, upgrade

A titre informatif, une prison de Samba neuve occupe 20 Mo d'espace disque.

(peut être script et mise en prod dans la même partie)

Scripts
Reprends les procédures mais est un logiciel serveur complet. Vérifications, créations, démarrage, stop, configuration etc.
Le programme s'appelle Galaxy

Mise en prod
Tests de mise en prod et debug. Il est possible d'upgrade un Samba d'une version à une autre en quelques secondes, transparent pour les utilisateurs.
Le script est capable de recopier la configuration d'un Samba en production, pour le remplacer. La configuration est détachée de l'exécution.

## Compétences

* [GNU / Linux]({{ site.skillsLocation | append: site.technicalSkillsLocation | absolute_url }}/linux)
^
* [Créativité]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/creativity)
* [Persévérance]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/perseverance)