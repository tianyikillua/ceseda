# Code de l'entrée et du séjour des étrangers et du droit d'asile 

> [Nul est censé ignorer la loi.](http://www.vie-publique.fr/decouverte-institutions/citoyen/citoyennete/definition/devoirs-definition/que-signifie-nul-n-est-cense-ignorer-loi.html)

Ce dépôt contient le [Code de l'entrée et du séjour des étrangers et du droit d'asile](https://www.legifrance.gouv.fr/affichCode.do?cidTexte=LEGITEXT000006070158), fréquemment référencé sous le sigle CESEDA, en un seul fichier [Markdown](https://fr.wikipedia.org/wiki/Markdown) qui suit les évolutions législatives à l'aide du versionnage [Git](https://fr.wikipedia.org/wiki/Git).

Ainsi, pour visualiser/analyser ses différentes versions suite à son entrée en vigueur en 2005, vous pouvez utiliser toute fonctionnalité permise par Git :

- chaque commit correspond en effet à une modification du texte, qui peut être mis sous forme d'un `diff`.
- pour visualiser le texte entier suite à un commit, vous pouvez faire ainsi un `git checkout`.
- ces fonctionnalités sont également disponibles sur le site Github.

Par exemple, pour les étudiants étrangers ayant récemment obtenu un diplôme au moins equivalent au Master, le droit à une APS permettant de chercher *librement* un travail en France provient de ce [commit](https://github.com/tianyikillua/ceseda/commit/606f5d192732e0a3e414790b1d13d031e9cbd46a) qui date *seulement* du 24 juillet 2013.

Le fichier [`Code_de_l’entree_et_du_sejour_des_etrangers_et_du_droit_d’asile.md`](https://github.com/tianyikillua/ceseda/blob/master/Code_de_l%E2%80%99entree_et_du_sejour_des_etrangers_et_du_droit_d%E2%80%99asile.md) est généré par le programme [Archéo Lex – Pure Histoire de la Loi française](https://github.com/Legilibre/Archeo-Lex) disponible également sur le site Github. Pour ce faire, lancer simplement la commande suivante :

``` sh
./archeo-lex -t LEGITEXT000006070158 -l tout
```

où `LEGITEXT000006070158` correspond en effet à la référence du CESEDA et `-l tout` permet de télécharger toutes les mises à jours consolidées sur le site [Legifrance](https://www.legifrance.gouv.fr).

Pour plus de détails sur ce type de présentation de lois ou plus généralement sur l'ouverture de données publiques (en France...), vous pouvez consulter les liens indiqués dans le dépôt de [Archéo Lex – Pure Histoire de la Loi française](https://github.com/Legilibre/Archeo-Lex).

### Mentions légales

Ce dépôt résulte d'une réutilisation personnelle de la base de donnés `LEGI` fournie et produite par la Direction de l’information légale et administrative (DILA), diffusée sur le site [Legifrance](https://www.legifrance.gouv.fr/affichCode.do?cidTexte=LEGITEXT000006070158). 