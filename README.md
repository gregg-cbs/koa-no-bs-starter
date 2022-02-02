# Koa no bs starter
The least you need to get koa running

```javascript 
npm run dev
npm run prod
```      

Nodemon included on dev speed of development,    
and excluded in production for speed of deployment and performance

*most production containers like in Heroku and Netlify should set node_env to production automatically and your local will not have it set, thats how the server will know not to install nodemon, and your pc will know to install it.
