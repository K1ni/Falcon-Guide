# Proxies

Proxies can help resolve API rate limits for  platforms apis (such as Blever, OpenSea, etc.) during minting and for public rpcs.\


Regarding platform rate limits:

* For Blever, each task requires at least 3 proxies when the interval is set to 1000ms.
* For OpenSea, no proxies are needed for up to 20 tasks when the interval is 1000ms or higher. Beyond that, approximately 1 proxy is required for every 20 tasks, also with a 1000ms interval.\
  \
  You can adjust the number of proxies based on your chosen interval setting.

\
How to get proxies?\
You can search on Google—there are many proxy providers, such as ProxyCheap, Webshare, etc.\
For minting tasks, you only need to choose relatively affordable plans.\
To reduce latency, select proxies located close to where your Falcon app is running.

If you are unable to access certain API features, you can use the default proxy in the settings or employ a VPN.\


<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

If the blockchain you are minting on does not have a private RPC, you may need to use a public RPC along with RPC proxies in the settings to prevent rate limiting when handling a large number of tasks.

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>
