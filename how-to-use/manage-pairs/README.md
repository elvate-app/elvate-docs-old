---
description: Create, Subscribe and Trigger a Pair
cover: ../../.gitbook/assets/BackgroundR150 [Converti]-01.jpg
coverY: 1649.6174743024962
---

# Manage Pairs

Une Paire permet de s'inscrire automatiquement à une stratégie de DCA composée de deux tokens BEP20. Chaque paire peut être trigger une seule fois par semaine, de manière totalement indépendante des autres. Il ne peut exister qu'une Paire par combinaison et il est possible de s'inscrire à chaque paire de manière indépendante.

![Example of BUSD/WBNB Pair](../../.gitbook/assets/Screenshot\_20220329\_172854.png)

Lors d'un trigger, le smart contract va effectuer un swap groupé pour toutes les subscriptions éligibles de la paire triggered. Une subscription est qualifié d'éligible si le dépot du token d'entrée est supérieur ou égale au montant de la subscription.

Pour l'utilisateur, il suffit donc de souscrire à une paire, puis de s'assurer que son dépot du token d'entrée est toujours supérieur à sa subscription.

{% hint style="info" %}
Elvate is charging 0.1% of swap result, 0.05% for the user who trigger the pair, 0.05% for the platform.
{% endhint %}
