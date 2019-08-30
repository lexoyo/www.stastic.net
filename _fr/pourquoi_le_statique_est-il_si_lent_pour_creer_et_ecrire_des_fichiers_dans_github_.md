---
title: Pourquoi Static est-il si lent pour lire et écrire des fichiers sur Github ?

---
Stastic est un éditeur de site qui vous permet de modifier vos fichiers sur Github, un service fantastique, comme expliqué dans les sections "[À qui appartiennent mes données](https://www.stastic.net/docs/fr/a-qui-appartient-mon-data)" et "[Où mon site est-il hébergé ?](/docs/fr/ou-mon-site-web-est-il-heberge)". 

Lorsque vous utilisez le programme d'installation Stastic pour installer Stastic sur un site existant ou pour créer un nouveau site, lorsque vous utilisez Stastic Editor pour modifier le contenu de votre site, toutes ces opérations sont effectuées sur des fichiers situés sur des serveurs Github. **Les opérations de lecture et d’écriture sont rapides, mais chaque fois que vous faites cela, les pages Github déclenchent une reconstruction de votre site** pour le mettre à jour. C'est ce qui est lent en réalité, car **pendant la reconstruction, Stastic affiche une "roue" pour vous informer que vous pouvez continuer à travailler pendant que votre site est mis à jour** avec le nouveau contenu.
