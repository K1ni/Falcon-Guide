# Timestamp to Start

This feature enables you to schedule transactions for precise predefined times using Unix time. You can convert any time using websites such as time.is, which includes a Unix time converter in its Unix section: [https://time.is/Unix\_time\_converter](https://time.is/Unix_time_converter)&#x20;

Falcon added milliseconds to the timestamp for more acurate timing, because of that you will have to add 3 zeros to a regular timestamp. For example, regular timestamp: 1740421200 - timestamp required for Falcon V2: 1740421200000&#x20;

For using timestamp you will have to turn off simulate option and manually put the gas limit of the transaction. To ensure that you have correctly configured the tasks you can check the countdown for the transaction to send once you start it.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>
