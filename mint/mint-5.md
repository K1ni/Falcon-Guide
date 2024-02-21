# Timestamp

The Timestamp feature enables you to schedule transactions for precise predefined times using Unix time. You can convert any time using websites such as time.is, which includes a Unix time converter in its Unix section: [https://time.is/Unix\_time\_converter](https://time.is/Unix\_time\_converter)\
![](<../.gitbook/assets/image (7) (1).png>)\
To ensure that you have correctly configured the trigger and tasks, you can verify that once activated, the timer counts down like a countdown.

<figure><img src="../.gitbook/assets/image (8) (1).png" alt=""><figcaption><p>An example using the tasks created earlier in this guide and the Timestamp feature</p></figcaption></figure>

<mark style="color:red;">**However, similar to Flipstate, when using Timestamp on pending. you will need to turn simulate OFF, otherwise the result of the simulation will be failed and your transaction will not be sent. you also need to manually imput gasLimit.**</mark> \ <mark style="color:red;">**For more information regarding gasLimit please refer yourself**</mark> [_<mark style="color:blue;">**here**</mark>_](../gas-usage.md)<mark style="color:red;">**.**</mark>

Please note that turning off simulation should make your transaction slightly faster.&#x20;
