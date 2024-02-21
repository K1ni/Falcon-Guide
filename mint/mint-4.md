# Flipstate

The "Flipstate" option allows you to create a task that monitors the contract. When the contract owner initiates a transaction to enable minting, your transaction will be sent using the same fees. However, Falcon provides the flexibility to send your transaction once the transaction enabling minting is confirmed.\
\
You can select either option with a simple click, choosing the one that best suits your needs.

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**However, when using Flipstate on pending. you will need to turn simulate OFF, otherwise the result of the simulation will be failed and your transaction will not be sent. you also need to manually input gasLimit.**</mark> \ <mark style="color:red;">**For more information regarding gasLimit please refer yourself**</mark> [_<mark style="color:blue;">**here**</mark>_](../gas-usage.md)<mark style="color:red;">**.**</mark>

Please note that turning off simulation should make your transaction slightly faster.&#x20;
