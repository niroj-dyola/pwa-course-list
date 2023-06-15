# Web App Manifest

* Web App Manifest - Browser Support: http://caniuse.com/#feat=web-app-manifest

* MDN Article on the Web App Manifest (includes List of all Properties): https://developer.mozilla.org/en-US/docs/Web/Manifest

* A detailed Web App Manifest Explanation by Google: https://developers.google.com/web/fundamentals/engage-and-retain/web-app-manifest/

* More about the "Web App Install Banner" (including Requirements): https://developers.google.com/web/fundamentals/engage-and-retain/app-install-banners/

* Download and check app_manifest-final.zip


# SW Basic Registered and Event Handling

* Are Service Workers Ready? - Check Browser Support: https://jakearchibald.github.io/isserviceworkerready/

* Setting up Remote Debugging on Chrome: https://developers.google.com/web/tools/chrome-devtools/remote-debugging/

* Getting that "Web App Install Banner": https://developers.google.com/web/fundamentals/engage-and-retain/app-install-banners/

* Getting Started with Service Workers (don't read too far, there's stuff in there we'll learn later ;-)): https://developers.google.com/web/fundamentals/getting-started/primers/service-workers

* Download sw-basics.zip

# Promises and Fetch

## Want to dive deeper into Promises?

* Introduction to Promises (MDN): https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

* Introduction to Promises (Google): https://developers.google.com/web/fundamentals/getting-started/primers/promises

## Dive deeper into the Fetch API:

* An Overview on MDN: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
Detailed Usage Guide (MDN): https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch

* Detailed Usage Guide (and comparison with XMLHttpRequest): https://davidwalsh.name/fetch
Introduction to Fetch (Google): https://developers.google.com/web/updates/2015/03/introduction-to-fetch

* Download promise-fetch.zip

# Service Workers Caching

* About Cache Persistence and Storage Limits: https://jakearchibald.com/2014/offline-cookbook/#cache-persistence

* Learn more about Service Workers: https://developer.mozilla.org/en/docs/Web/API/Service_Worker_API

* Google's Introduction to Service Workers: https://developers.google.com/web/fundamentals/getting-started/primers/service-workers

* Download sw-caching.zip

# Service Worker - Advanced Caching

* Great overview over Strategies - the Offline Cookbook: https://jakearchibald.com/2014/offline-cookbook/

* Advanced Caching Guide: https://afasterweb.com/2017/01/31/upgrading-your-service-worker-cache/

* Mozilla Strategy Cookbook: https://serviceworke.rs/strategy-cache-and-update_service-worker_doc.html

* Download adv-caching.zip

# IndexedDB and Dynamic Data

* IndexedDB Browser Support: http://caniuse.com/#feat=indexeddb

* IDB on Github: https://github.com/jakearchibald/idb

* IndexedDB explained on MDN: https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API
Alternative to IDB: http://dexie.org/

* Resources are :
  
  * id-added-firebase-source.zip
  * id-added-id-package.zip
  * id-outsource-logic-utilityjs.zip
  * id-read-data.zip
  * id-write-data.zip
  * id-clear-store.zip

# Background and Sync

* Introducing Background Sync: https://developers.google.com/web/updates/2015/12/background-sync

* A Basic Guide to Background Sync: https://ponyfoo.com/articles/backgroundsync

* More about Firebase Cloud Functions: https://firebase.google.com/docs/functions/

* Download backgrund-sync-custom-firebase.zip

# Web Push Notification

* More about Web Push by Google: https://developers.google.com/web/fundamentals/engage-and-retain/push-notifications/

* More about VAPID: https://blog.mozilla.org/services/2016/04/04/using-vapid-with-webpush/

* More about VAPID by Google: https://developers.google.com/web/updates/2016/07/web-push-interop-wins

* The web-push npm Package: https://github.com/web-push-libs/web-push

* More about showNotification (display Notifications from Service Workers): https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerRegistration/showNotification

* The Notification API: https://developer.mozilla.org/en/docs/Web/API/notification

* The Push API: https://developer.mozilla.org/en/docs/Web/API/Push_API

* Download web-push.zip

# Service Worker Management and Workbox

* Official webpage/ docs: https://workboxjs.org/

* Configuring Workbox: https://workboxjs.org/reference-docs/latest/module-workbox-build.html#.Configuration

* More about Workbox Strategies: https://workboxjs.org/reference-docs/latest/module-workbox-sw.Strategies.html#main

* Workbox Github page: https://github.com/GoogleChrome/workbox

* Workbox Overview by Google: https://developers.google.com/web/tools/workbox/

# SPAs and PWAs

* create-react-app Page: https://github.com/facebookincubator/create-react-app

* Angular CLI Github Page: https://github.com/angular/angular-cli

* Overview over Angular Service Worker Usage: https://fluin.io/blog/angular-service-worker

* PWAs with Angular: https://medium.com/@amcdnl/service-worker-pwas-with-the-angular-cli-98a8f16d62d6

* Vue CLI PWA Template Page: https://github.com/vuejs-templates/pwa

* More about sw-precache-webpack-plugin: https://www.npmjs.com/package/sw-precache-webpack-plugin

Important: If you DON'T want to replace sw-precache with Workbox but still want to add your own Service Worker logic, you have to use the importScripts[]  option on the sw-precache config to import your own Service Worker file into the generated one. This allows you to add your own logic.

* Download spa-react.zip for react project




