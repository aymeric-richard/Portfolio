---
layout: default
---

# Création d'un gestionnaire de container pour Samba, nom de code Galaxy

## Docker n'a qu'à bien se tenir

Pour gérer plus facilement les logiciels serveurs, indépendamment des machines ou des environnements clients, je devais mettre en place un **gestionnaire de conteneur**. Le logiciel cible était **Samba**, l'équivalent de **Active Directory** sous Linux.

## Implémentation

### Chroot

Un logiciel a besoin pour fonctionner d'un environnement composé d'une arborescence de fichiers et de programmes. Cette arborescence se base sur une racine, qu'on appelle "/". Le chroot, pour CHangeROOT, permet de changer la racine de l'environnement courant, et donc de créer un **conteneur étanche** par rapport à tout ce qui se trouve avant la racine.
J'ai donc créé un environnement étanche capable de faire fonctionner Samba.

### Procédures

Pour écarter le moindre bug ou oubli, j'ai écrit des procédures précises et testées sur les points suivants :

* Compiler Samba depuis les sources (toutes les versions, oui toutes)
* Mettre en conteneur ces versions
* Faire des tests de démarrages, d'arrêts et de mises à jour des serveurs Samba

A titre informatif, un conteneur de Samba neuf occupe **20 Mo** d'espace disque.

### Scripts

A partir des procédures nous avons écrit un script conséquent, qui gère toutes les tâches nécessaires à l'administration d'un serveur Galaxy. Galaxy est le nom que nous avons donné à ce gestionnaire de conteneur Samba.
C'est un logiciel serveur complet, il fait des vérifications, créations, démarrages / arrêts de démons, configurations etc.

### Mise en Production

La mise en production s'est faite en une semaine, avec de nombreux tests et debugs.
Il est possible d'upgrade un Samba d'une version à une autre en quelques secondes, c'est transparent pour les utilisateurs.
Le script est capable de recopier la configuration d'un Samba en production, pour le remplacer. La configuration est détachée de l'exécution.

Il est utilisé aujourd'hui chez **tous les clients** de la société.

## Compétences

* [GNU / Linux]({{ site.skillsLocation | append: site.technicalSkillsLocation | absolute_url }}/linux)
^
* [Créativité]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/creativity)
* [Persévérance]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/perseverance)