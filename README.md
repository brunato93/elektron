Elektron is a Ionic Hybrid app whose conectivity and user profile management is done through wordpress. The wordpress project must be launched for this app to have database connection.

database connection must be configured in this path:

wwww/js/config.js

lines for configuration are: 

angular.module('your_app_name.config', [])
.constant('WORDPRESS_API_URL', 'your_api_url')
.constant('GCM_SENDER_ID', 'your_gcm_sender_id')


the code lacks nodemodules please install them localy. 
 
For trials and testing please install the ionic environment from this guide: 

https://ionicframework.com/docs/v3/


* Develop in the browser with live reload:
```
ionic serve
```

Note: iOS development requires OS X currently
See the Android Platform Guide for full Android installation instructions:
https://cordova.apache.org/docs/en/edge/guide_platforms_android_index.md.html

* Build your app:
```
ionic build <PLATFORM>
```

* Simulate your app:
```
ionic emulate <PLATFORM>
```

* Run your app on a device:
```
ionic run <PLATFORM>
```

* Package an app using Ionic package service:
```
ionic package <MODE> <PLATFORM>
```

For more help use ```ionic --help``` or visit the Ionic docs: http://ionicframework.com/docs


You can find the documentation here: http://bit.ly/ionicthemes-ionfullapp
