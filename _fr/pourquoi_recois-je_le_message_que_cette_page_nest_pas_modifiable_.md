---
title: Pourquoi le message "cette page n'est pas modifiable" ?
tags:
  - pages


---
Vous avez installé Stastic sur un site existant ou vous en avez créé un nouveau ? Vous êtes maintenant prêt à modifier une page ou un message, mais Stastic ne vous le permet pas et affiche le message "cette page n'est pas modifiable" au lieu de un contenu éditable ? 

![Page stastique non modifiable](https://www.stastic.net//assets/2019-08-04-924319.png) 

Cela se produit dans la plupart des cas, car la page que vous essayez d'éditer a été générée par un plugin Jekyll, tel que [le plugin jekyll-paginate](https://jekyllrb.com/docs/pagination/) qui réparti votre liste de publications en plusieurs pages. Ou [le plugin jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap) qui crée un fichier "dynamique" sitemap.xml pour le référencement. 

Dans ce cas, le contenu que vous essayez d’éditer n’est tout simplement pas éditable.
