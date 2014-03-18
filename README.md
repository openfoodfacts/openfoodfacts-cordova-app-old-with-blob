openfoodfacts-android
=====================

Open Food Facts Android app

*** Work in progress ***

An application to:

1. scan the barcode of a product and retrieve the associated data from http://openfoodfacts.org

2. add products to the Open Food Facts database

*** API ***

1. JSON: http://fr.openfoodfacts.org/api/v0/product/2165244002857.json

*** Building ***

Install NPM
Install Cordova via NPM: `npm install -g cordova`
`cd cordova`
Add Barcode plugin: `cordova plugin add https://github.com/wildabeast/BarcodeScanner`
Add Android Support library to platforms/android/libs/
Update project:`android update project -p platforms/android -s
Workaround: `rm  platforms/android/custom_rules.xml`
Build: `cordova build`

