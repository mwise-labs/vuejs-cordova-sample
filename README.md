# vuejs-cordova-sample

> Sample VueJS app that uses Cordova capabilities

![](/Users/dusanrandelovic/Desktop/vuejs-cordova-sample/ios.png)


## Build Setup

```bash
# install cordova globally
npm i -g cordova

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run serve

# build for production to run in Cordova
npm run build

```

## First Cordova build

```sh
npm run build
cd cordova_app
cordova platform add <platform>  # android or ios
cordova run <platform> # or build
```

## Next Cordova run/build commands

```sh
npm run android 
npm run android build
npm run ios 
npm run ios build 
```

## Plugins

- cordova-plugin-dialogs
- cordova-plugin-vibration
- cordova-plugin-geolocation
- cordova-plugin-flashlight
- cordova-plugin-camera
- phonegap-nfc
- cordova-plugin-statusbar
- cordova-plugin-headercolor
