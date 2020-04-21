# PWA 

News API - Alternative News


## Running locally

1. Run npm install

2. Note the import statement from within sw-wb.js: 

//Service Worker
importScripts('./node_modules/workbox-sw/build/importScripts/workbox-sw.dev.v2.1.1.js')


3. Serve folder with your server of choice. For instance `serve .`.

4. Pre-cache, Register route and Network strategies are in sw.js

