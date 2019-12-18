---
title: Comment prévisualiser une publication?

---
Dans le cas où votre site Web est en ligne et que vous souhaitez prévisualiser les modifications avant que vos visiteurs ne le voient.

La voie à suivre est d'avoir 2 versions de votre site (c'est-à-dire préprod et prod), cela signifie 2 fourchettes du même référentiel afin que vous puissiez faire des demandes d'extraction pour rendre vos modifications en direct. Vous pouvez créer une organisation pour contenir le référentiel principal:

* l'organisation aura le dépôt principal et c'est ce que voient vos visiteurs
* votre compte personnel aura une fourchette de ce même dépôt et c'est ce que vous modifiez et prévisualisez

Voici un exemple réel:

* mon site est cto-bro.com
* il est servi [depuis ce dépôt (internet-de-france / cto-bro.com)] (https://github.com/internet-de-france/cto-bro.com)
* quand je veux éditer le contenu, je fais sur [ce repo (lexoyo / cto-bro.com)] (https://github.com/lexoyo/cto-bro.com) avec stastic installé dessus
* donc mon aperçu est disponible sur `https: // lexoyo.me / cto-bro.com / fr` (J'ai un domaine personnalisé sur toutes mes pages github personnelles)