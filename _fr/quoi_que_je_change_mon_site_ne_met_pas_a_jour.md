---
title: 'Quoi que je change, mon site ne se met pas à jour'
tags:
  - preview
  - pages
  - collection
  - data
  - settings

---
Vous essayez probablement de modifier le contenu de votre site avec Stastic, mais votre site ne change pas, quoi que vous ajoutiez, supprimez ou modifiez? 

__Avez-vous lu la section "[Interface utilisateur stastique, comment créer des pages](/docs/fr/stastic-ui-comment-creer-des-pages)" ? Ainsi que la section "[Pourquoi Static est-il si lent pour lire et écrire des fichiers dans Github ?](/docs/fr/pourquoi-le-statique-est-il-si-lent-pour-creer-et-ecrire-des-fichiers-dans-github)"?__ 

Il y a probablement un problème avec le contenu de votre site, ce qui provoque une erreur lorsque Github pages tente de le reconstruire. Ceci empêche le site de mettre à jour tout contenu - conseil: modifiez un contenu existant pour voir si c'est bien votre cas. Si tel est le cas, vous recevrez un email de la part de Github pages indiquant qu'il y avait un problème de construction de votre site. **Le problème peut venir d'un post ou d'une page ou encore des paramètres du site.** 

> Remarque: si une seule page n’est pas mise à jour, veuillez lire la section "[Comment éditer la page d’accueil de mon site?](/docs/fr/comment-modifier-la-page-daccueil)"

La manière "facile" de résoudre ce problème consiste à annuler ce que vous avez fait récemment pour savoir ce qui ne va pas. Vous pouvez utiliser [la page qui liste les modifications sur Github](https://help.github.com/fr/articles/differences-between-commit-views) pour voir ce qui a été modifié et quand. 

Une méthode plus professionnelle consiste à cloner le code du site sur votre ordinateur et à exécuter [les lignes de commande Jekyll](https://jekyllrb.com/docs/) pour obtenir une erreur détaillée. Vous voudrez peut-être aussi lire la section "[Support et développements sur mesure](/docs/fr/assistance-professionnelle-et-developpements-personnalises)" pour obtenir du support professionnel, ou bien écrivez nous simplement et nous ferons le maximum.
