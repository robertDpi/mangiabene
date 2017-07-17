# Artusi's Kitchen
### Known as 'The Science of Cooking and the Art of Fine dining'
Italian cooking app, based on the teachings of Pellegrino Artusi: One of the greatest italian chefs.
Unbeknown to most, Pellegrino Artusi was mostly a businessman. He was a believer of the scientific method, especially in regards to his greatest passion: The art of cooking.
His book, in fact, can be considered a "scientifically tested" manual: every recipe was the result of trials and experiments.

This app has been designed to share with you the stories and the recipes that Pellegrino artusi described in his book.

## Installation

```
git pull <this repository>

```

Install yarn

```  
#install dependencies
yarn
```

the available commands are provided by [WPHC](http://wphc.julienrenaux.fr/getting-started.html)

```
postinstall
  npm run installWPHC
start
  webpack-dev-server --port 8080 --json --progress


# available via `npm run-script`:

build
  bash ./release.sh
restore
  rm -rf platforms/ plugins/ && ionic state restore
installWPHC
  cd scripts && node ./install.js
increaseVersion
  cd scripts && node ./increaseVersion.js
devserver
  npm start
dumpdev
  rm -rf www/* && webpack --progress --colors -d
dumpprod
  rm -rf www/* && webpack --progress --colors --config webpack.config.prod.js -p
android
  npm run dumpdev && cordova run android
iosEmulator
  npm run dumpdev && cordova run ios
ios
  npm run dumpdev && cordova run ios --device
cordova
  cordova
buildAndroid
  BUILD_MULTIPLE_APKS=true cordova build android --device
buildProdAndroid
  BUILD_MULTIPLE_APKS=true cordova build android --device --release
buildIOS
  cordova build ios --device
buildProdIOS
  cordova build ios --device --release


```
