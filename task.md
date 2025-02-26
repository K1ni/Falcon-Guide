# Task

With your wallets appropriately configured and adequately funded in ETH, and your node successfully integrated into Falcon, you can now dive into configuring tasks and minting.

To start, create a group to keep your minting tasks organised, give it a name, enter the contract adress for the nft you're looking to mint and select the chain of the mint for Falcon to show you that chain's RPC, if the chain is EVM but it doesn't show in the bot and you have added its RPC click the 3 dots.

VIDEO CREATING A GROUP

To know how to do a task configuration head over TASK CONFIGS

Once your group is created you can start creating minting tasks. \
Click on the Create + button to create tasks.

Choose the group and wallets for minting, put the HEX, the value (minting price), set the maximum and priority fees per transaction, select your RPC, Nonce, simulate interval and save the task.

Nonce: Preset or auto, Preset is faster because it doesn't spend time looking for the nonce but if you create the task and do a transaction with that wallet before the mint goes live the bot won't send the minting transaction because the nonce of that wallet would have changed.

Simulate interval: It is every how many milliseconds the tasks simulates the transaction.

What is HEX

It is a replica of a transaction that contains the same options you would input when interacting with a contract, such as the amount of ETH, the number of NFTs to mint, and the transaction fees and priority fees.

HOW TO GET HEX (KINI)

VIDEO CREATING A MINTING TASK

Timestamp : This feature enables you to schedule transactions for precise predefined times using Unix time. You can convert any time using websites such as time.is, which includes a Unix time converter in its Unix section: [https://time.is/Unix\_time\_converter](https://time.is/Unix_time_converter)&#x20;

Falcon added milliseconds to the timestamp for more acurate timing, because of that you will have to add 3 zeros to a regular timestamp. For example, regular timestamp: 1740421200 - timestamp required for Falcon V2: 1740421200000&#x20;

For using timestamp you will have to turn off simulate option and manually put the gas limit of the transaction. To ensure that you have correctly configured the tasks you can check the countdown for the transaction to send once you start it.

<figure><img src=".gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

As Trigger: This minting function allows you to only start 1 minting task instead of all of them, once the minting task you started is sent all the rest of the task will be sent. This is very usefull to avoid rate limit of the RPC.

For this minting function you have to leave Simulate and As Trigger ON while creating the minting task.

<figure><img src=".gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

VIDEO OF HOW IT WORKS
