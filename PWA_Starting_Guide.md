# PWA -Starting Guide for Angular (v0.0.1)

 ## 1. Angular Start
(requirement: existing  Angular aplikation; ):
```ng add @angular/pwa```

build project with:
```ng build --prod```

for local execution use:

[Link to http:server npm](https://www.npmjs.com/package/http-server)
..* Tipp: for local debugging use port 8000 under local home so:
 http://127.0.0.1:8000/ thise wise u dont need a certificate and test locally if it works 
 so
 

  ```http-server -p 8080 -c-1 dist/<project-name>```


## 2. The Service Worker
The Service Worker sits 

for local debugg use /ngsw/state in the url to get the status 

##  SwUpdate

## SwPush

  for the push service you need a Vapid key 
  (therefor i use to install

  ```npm install web-push -g``` 

to generate

  ```web-push generate-vapid-keys```)



Ressources Used for this Guide
------------------------------
 [Basic Guide](https://angular.io/guide/service-worker-intro)

 [Guide regarding general Use](https://blog.angular-university.io/angular-service-worker/)

[Service Worker API guide from MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)

[Service Worker Learning Tool](https://web.dev/codelab-service-workers/)

[Guide from Google](https://codelabs.developers.google.com/codelabs/pwa-offline-quickstart/#0)
