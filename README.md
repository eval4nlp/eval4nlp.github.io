# eval4nlp.github.io
To run the website locally:
```
npm install
node_modules/.bin/gulp watch
```


When updating the navbar, increase the cache counter by one. 
Otherwise some users might not see the update since they load the cached version.

> $("#navbarResponsive").load("nav.html?cache=123");