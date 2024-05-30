# Lab8-Starter

https://mishkajethwani.github.io/Lab8-Starter/

How are graceful degradation and service workers related? 

Graceful degradation is the concept of working from the code first, while providing them a different version if something is messed up. It should generally be employed by web apps. Graceful degradation ensures that when a web app is built there should be  some level of functionality anduser experience even when certain features fail to load or are unavailble. Service Workers are client side proxy scripts that run in the background of a web application and handle network requests appropriately and also help in synchronization when the web-app is offline. Both of these are used for the same idea of Agile that some functionality should always be available to the user. They both can be used together to create web-apps for a good and consistent User Experience. Suppose we face a network or server issue, Service Workers can be used to show the webApp in scenarios where there is network i.e it is offline - this goes hand in hand with graceful degradation. 
