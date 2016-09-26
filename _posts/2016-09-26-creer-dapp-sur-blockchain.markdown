---
layout: post
title:  "Créer une dapp sur Ethereum"
date:   2016-09-26 16:53:35 +0200
categories: blockchain ethereum
---
> Les adolescents représentent l’avenir. Ils ne sont pas encore embourbés par la
façon dont nous menons actuellement nos vies, avec nos cartes de crédit,
hypothèques, etc. Alors que pour la plupart des gens, passer au Bitcoin
est une souffrance à court terme car ils sont déjà à l’aise avec le fait
d’utiliser des cartes de crédit, pour les adolescents c’est à l’inverse tout
le processus d’ouverture de compte et de carte de crédit qui leur pose
problème. Ils préféraient simplement pouvoir commencer à gagner et dépenser
quelques “coins”. En outre, il ne sont pas encore corrompus par la psychologie
du système de carte de crédit, qui veut qu’il est plus simple d’obtenir de
l’argent rapidement et temporairement en suppliant plutôt qu’en produisant. La
psychologie que ces jeunes adopteteront sera, dans 10 ou 20 ans, celle qui
conduira la psychologie de la société.
> - Vitalik Buterin (17ans à l’écriture de ce post), fondateur d’Ethereum,
28/02/2012

[Ethereum][Ethereum] est une __plateforme décentralisé__ et distribué pour
lancer des __smart contrats__ (ou programme autonome sur une blockchain). Cette
plateforme est un ordinateur à l’échelle mondiale. Il est toujours accessible et
n’importe qui peut programmer un smart contrat dessus. Cet ordinateur global est
formé à partir de milliers d'ordinateurs réparti sur toute la planète, ces
ordinateurs sont appelés les __mineurs__. Ils utilisent  une base de
__données distribuée__ appelé __blockchain__ pour partager les transactions et
les programmes entre eux. Les données sont __décentralisé__, __persistantes__,
sur une réseau __peer-to-peer__. Il n’y a donc pas de “single point of failure”.

![Ethereum](http://i.stack.imgur.com/hDDzg.png)

Qu’est-ce que la blockchain ?
=============================

La blockchain est une base de donnée distribuée où l'on peut enregistrer des
données sans passer par un intermédiaire. La blockchain la plus connue est
[Bitcoin][Bitcoin] qui permet de s’échanger des __token__, c’est une forme de
cryptomonnaie. Ces transactions sont validés par des mineurs, qui partage une
partie de leur puissance de calcul numérique (n’importe qui avec son ordinateur
peut miner). Etherum reprend cette technologie et la généralise pour construire
des applications, pas seulement une *monnaie*, sur la blockchain. Concrètement,
il s’agit de développer un smart contract avec la logique de l’application et
de la pousser dans la blockchain ethereum.

Comment valider les blocs ?
===========================

Le registre de la blockhain peut être modifié par un ou plusieurs mineurs. Alors
comment s’assurer de la légitimité de celle-ci ? La validité de la blockchain
est assuré par le __consensus des noeuds__ du réseau distribué. Si un block est
validé par la mojorité des mineurs, il est considéré comme valide. Cette preuve
de validité d’un bloc est appelé __proof-of-work__. Trouver cette preuve demande
beaucoup de ressource. Trouver cette preuve demande énormément de ressource.
C'est pourquoi, à chaque ajouté à la blockchain, le mineur se voit verser un
certain nombre montant de cryptomonnaie, fraîchement créée. La complexité ainsi
que le chaînage des uns à la suite des autres font qu'il est difficile de
falsifier ou supprimer les données de la blockchain. Pour modifier les données
d'un bloc, il faut refaire valider l'ensemble des blocs qui le suivent, avant
qu'un autre noeud n'ajoute un nouveau bloc à la chaîne.

Bibliographie
=============

- [Ethereum][Ethereum]: site officiel d'Ethereum
- [Ethstats][Ethstats]: statistiques sur Ethereum
- [Etherchain][Etherchain]: statistiques sur Ethereum
- [jefflau.net][jefflau.net]: introduction à Ethereum
- Programmez!#199: introduction à la programmation sur Ethereum
- O'Reilly blockhain: introduction à la technologie de Bitcoin


[Ethereum]: https://www.ethereum.org/
[Bitcoin]: https://bitcoin.org/fr/
[Ethstats]: https://ethstats.net/
[Etherchain]: https://www.etherchain.org/
[jefflau.net]: http://jefflau.net/how-to-start-developing-on-ethereum-for-web-developers/
