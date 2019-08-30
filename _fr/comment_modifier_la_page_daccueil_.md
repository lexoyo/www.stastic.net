---
title: Comment éditer la page d'accueil de mon site ?

---
Vous avez donc installé Stastic sur un site existant ou vous en avez créé un nouveau, et maintenant vous souhaitez modifier la page d'accueil de celui-ci ? 

Si ce que vous voyez est proche de l'image suivante ou, d'une manière plus générale, si ce que vous modifiez dans une page n'affecte pas le contenu en direct de votre site, poursuivez votre lecture cette section est pour vous. 

![Modification de la page d'accueil dans Stastic](https://www.stastic.net//assets/2019-08-04-773303.png) 

La cause d'une page ne prenant pas en compte le contenu que vous fournissez dans l'éditeur Stastic est probablement que certains thèmes ont des pages "codées en dur". Pour comprendre cela, vous devez savoir que Stastic est construit sur Github pages qui utilisent [Jekyll](https://jekyllrb.com/) pour créer votre site, c'est-à-dire pour insérer votre contenu dans les modèles HTML du thème. En savoir plus sur [comment fonctionnent les modèles Jekyll](https://jekyllrb.com/docs/step-by-step/04-layouts/). 

Lorsque vous créez une page dans Stastic, vous pouvez définir le modèle utilisé pour mettre en page cette page (voir la liste déroulante en bas lors de la modification d'une page). Certains modèles ignorent simplement le contenu de votre page et affichent seulement du contenu HTML. Ceci est souvent fait pour les pages d'accueil qui peuvent avoir une conception plus complexe qu'un seul contenu de texte. 

Notez que parfois, ces "pages codées en dur" prennent en compte certains paramètres de votre site Web. 

> Très souvent, pour modifier le titre affiché sur votre page d'accueil, modifiez le titre dans les paramètres de votre site Web. Voir la section "[Interface utilisateur stastique, les paramètres généraux]" "pour en savoir plus à ce sujet. 
> Autre section intéressante: "[Pourquoi le message" Cette page n'est pas éditable "?" "

Si vous désirez modifier une page "codée en dur", vous devez essayer plusieurs choses pour changer son contenu: 

1. Essayez de changer le contenu de la page à partir de la liste des pages, puis essayez de changer les paramètres dans la page "Paramètres généraux" de Stastic
2. Allez à ceci page à partir de la liste des pages et modifiez son "méta-données de mise en page" qui est la liste déroulante en bas, au-dessous du contenu du texte. 
3. Modifiez la mise en page HTML. Pour cela, vous aurez probablement besoin de voir le code source de votre thème (la caisse se trouve dans la liste des thèmes sur [Installateur stastic ici](https://stastic.net/#/themes)). Il existe un bouton "Source" pour chaquet hème.). Pour cela, vous aurez peut-être besoin d'une assistance professionnelle, consultez la section "[Assistance professionnelle et développements personnalisés]".
