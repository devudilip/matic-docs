---
id: withdraw-exit-many
title: withdrawExitMany
keywords:
- 'plasma client, erc721, withdrawExitMany, polygon, sdk'
description: 'Начните работать с maticjs'
---

# withdrawExitMany {#withdrawexitmany}

Метод `withdrawExitMany` можно использовать для утверждения всех токенов.

```
const erc721RootToken = plasmaClient.erc721(<root token address>, true);

const approveResult = await erc721RootToken.withdrawExitMany(<burn tx hash>);

const txHash = await approveResult.getTransactionHash();

const txReceipt = await approveResult.getReceipt();

```