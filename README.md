# Lab8-Starter
## Kelly Dempster

### Graceful Degradation
Graceful degradation and service workers are connected because service workers are one of our solutions for maintaing graceful degradation in the case of slow network or error. By using the service worker script we wrote, the request that go straight to the network is reduced and the browser keeps information that was obtained previously. This is great for slow connections, because when we load the data once we have it in storage to grab again. The service worker makes sure to check the storage before requesting to the internet, and if the recipes already exist no internet fetch request is made at all, so we can still access the information offline too.

### Github URL: [https://kehiio.github.io/Lab8/](https://kehiio.github.io/Lab8/)

### PWA
![PWA Picture](pwa.png)
