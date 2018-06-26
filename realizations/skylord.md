---
layout: default
---

# Skylord, jeu de stratégie en ligne massivement multijoueur

## Une méthodologie professionnelle, de la R&D, le tout récompensé

<img src="{{ site.imagesLocation | absolute_url}}/skylord/Skylord_Logo.png" class="realization-mini"/>

Incarnez un puissant mage et partez à la conquête des cieux.
Étendez votre empire, entretenez vos alliances, créez des troupes et écrasez vos ennemis.
Prenez garde cependant, le monde de SkyLord contient bien des dangers !

Projet visant à démontrer la faisabilité de la mise en production d'un programme utilisant la nouvelle technologie ASP 5 avec DNX. DNX et les outils associés ont été remaniés par Microsoft pour devenir .NET Core.

![Bandeau]({{ site.imagesLocation | absolute_url}}/skylord/bandeau.jpg)

## Implémentation

### Une technologie en construction

Asp VNext et DNX sont des technologies en bêta lors du développement du projet. Chaque semaine a apporté son lot de nouveautés, de régressions et de breaking changes. Bien entendu les tutoriels pour utiliser la technologie ne se bousculaient pas, et les personnes compétentes sur le sujet pour répondre à nos questions non plus.

### Interaction avec Microsoft

<img src="{{ site.imagesLocation | absolute_url}}/skylord/11.jpg" class="realization-mini border" style="float: right;"/>
<img src="{{ site.imagesLocation | absolute_url}}/skylord/10.jpg" class="realization-mini border"/>

Comme expliqué juste au dessus, la technologie était en cours de développement. Nous avons logiquement rencontré des bugs à l'utilisation. L'interlocuteur privilégié est parfois directement le développeur de l'outil, nous avons donc contacté Microsoft lors de certains problèmes rencontrés. Il s'avère que nous avons pu en profiter pour remonter des bugs à l'équipe en charge du projet, en vue de son amélioration.

### Une démarche professionnelle

<img src="{{ site.imagesLocation | absolute_url}}/skylord/caserne.png" class="realization-mini"/>

Nous avons mis en place plusieurs [méthodes Agiles]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/agility) Scrum pour tenter une nouvelle approche. Nous étions 6 développeurs, tous partants pour se lancer dans cette aventure. Nous avons entre autre mis en pratique des sprints, des daily Scrum et le product backlog.

Aussi, dans un contexte encore plus professionnel, nous avons orchestré une chaîne d'intégration continue (CI) complète. J'ai majoritairement réalisé cette partie. Nous avions automatisé les builds selon des règles précises en suivant <a href="https://semver.org/" target="_blank">Semver</a> sur les tags de notre repository Git, le tout passé à la moulinette par les tests unitaires. Tout a été construit à la main, en utilisant <a href="https://github.com/SimpleGitVersion/CodeCake" target="_blank">CodeCake</a>, un outil équivalent à Cake (langage C) pour le C# et développé par Invéniétis. Cet outil est issue de SimpleGitVersion, un ensemble d'outils que nous avons utilisé pour la CI. J'ai d'ailleurs effectué une <a href="https://github.com/SimpleGitVersion/SGV-Net/pull/1" target="_blank">**pull request** qui a été acceptée sur SVG-Net</a>.

### Communication

<img src="{{ site.imagesLocation | absolute_url}}/skylord/ile2b.png" class="realization-mini" style="float: right;"/>

Nous avons mis le site en ligne pour le tester en cas réel et avoir des retours. Pour trouver des joueurs nous avons mené des actions de communications, tels que des posts de teasing sur Facebook :

> Encore une journée comme les autres. Notre seigneur Thanur nous a demandé d’agrandir son laboratoire pour y entreposer plus de bazar magique, encore une fois ! Depuis que nous sommes arrivés sur l'île tout évolue tellement vite que nous sommes tout le temps sur un nouveau bâtiment... Au début c'était marrant, maintenant j'en ai un peu marre, j'ai plutôt envie d'aller m'amuser autour du portail d’invocation ou du champ de cristal ! Ou peut-être que ce sera bientôt à moi d’aller à la tour du mage … et voir cette nouvelle apprentie dont tout le monde parle.
>
> Et dire que je n'ai même pas encore récupéré les ressources d'aujourd'hui...
>
> Journal de Rurin - Ouvrier 404 - Chapitre V - Jour 68

L'école elle même a fait de la publicité pour notre jeu. Nous avons eu une cinquantaine de joueurs en quelques jours et je me suis moi même pris au jeu à ma grande surprise. Je suis persuadé que ce jeu pourrait être commercialisé. Il faudrait le reprendre sur une plateforme stable.

### Récompenses

Ce fut un projet avec une équipe conséquente, 7 personnes tout de même. La gestion de projet a été une problématique que nous avons pris en compte et nous avons su nous dompter en conséquence pour tirer partit des compétences et caprices de chacun.
Cela nous a valu la **1ère place** au Forum des projets informatiques (PI) de IN'TECH, école supérieure d'informatique du groupe ESIEA, de janvier 2016.

## Compétences

<img src="{{ site.imagesLocation | absolute_url}}/skylord/sorcier4.gif" class="realization-mini" style="float: right;"/>
* [C# .NET]({{ site.skillsLocation | append: site.technicalSkillsLocation | absolute_url }}/csharpdotnet)
* [Git]({{ site.skillsLocation | append: site.technicalSkillsLocation | absolute_url }}/git)
* [ASP .NET MVC]({{ site.skillsLocation | append: site.technicalSkillsLocation | absolute_url }}/aspnetmvc)
^
* [Méthodes Agiles]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/agility)
* [Humour]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/humor)
* [Multipotentialité]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/multipotentialite)
* [Créativité]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/creativity)
* [Persévérance]({{ site.skillsLocation | append: site.humanSkillsLocation | absolute_url }}/perseverance)

## Liens

* <a href="https://www.facebook.com/skylordgame/" target="_blank" class="fab fa-facebook fa-lg"> Suivre sur Facebook</a>
* <a href="https://github.com/ITISkyLord/SkyLord/tree/Asp5" target="_blank" class="fab fa-github fa-lg"> Voir sur Github</a>
* <img src="{{ site.imagesLocation | absolute_url}}/logo_intech.png" style="float: left; margin-right: 5px;"/><a href="https://www.intechinfo.fr/skylord-jeu-video-etudiants-intech/" target="_blank" class="fab fa-lg"> Article dédié sur le site de IN'TECH</a>

## En images

[<img src="{{ site.imagesLocation | absolute_url}}/skylord/01.jpg" class="realization-mini border"/>]({{ site.imagesLocation | absolute_url}}/skylord/01.jpg)
[<img src="{{ site.imagesLocation | absolute_url}}/skylord/Arbre_de_techno.jpg" class="realization-mini border"/>]({{ site.imagesLocation | absolute_url}}/skylord/Arbre_de_techno.jpg)