# Nonce

## what is nonce?

In EVM chains, nonce is a unique identifier assigned to each transaction to prevent replay attacks. When a user initiates a transaction on the Ethereum network, the nonce value is incremented for each subsequent transaction from the same address

## how to set nonce?

The nonce can be auto, preset or input number, Preset is faster because it doesn't spend time looking for the nonce but if you create the task and do a transaction with that wallet before the mint goes live the bot won't send the minting transaction because the nonce of that wallet would have changed.

{% hint style="info" %}
use auto will be good for most situations, wrong nonce will not send your transaction
{% endhint %}
