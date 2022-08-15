# Heroku vs Netlify

To begin with, we must learn to differenciate between Static and Dynamic websites:

## Static  

* Can respond to user interactions. (button clicks, hover effects and the likes...)  
* Can't interact with databases. (The data can't be mutated - hence they are called static...)  

[Static Demonstration](https://vimeo.com/739174891)

## Dynamic

* Can respond to user interactions. (button clicks, hover effects and the likes...)  
* Interacts with databases. (The data can be mutated - hence they are called dynamic.)

[Static Demonstration](https://vimeo.com/739463418)
## Comparison  
<img src="https://conormclaughlin.net/img/dynamic_vs_static.jpg" />  
  
## Our Website is Dynamic

* We wish to interact with a Database.

## Summary

* Hero is as PaaS (Platform as a Service)
* Netlify is Serverless. (Trafic to your site diverges accross many Servers, according to the amount of traffic there is)

* Netlify is not so well suited for interactions with Backends.
* Netlify is well suited for React applications.

* Heroku is well suited for interactions with Backends.
