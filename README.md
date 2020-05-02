# Ionic example

## pre-requisites

node
cordova
ionic

Commands

npm install -g @ionic/cli

ionic start myApp-${angular|react} tabs
__________________________________________________________________

Framework: Angular|React
__________________________________________________________________

add dependencies automatically....

> npm i --save -E @capacitor/core
> npm i -D -E @capacitor/cli
> capacitor init myApp-{angular|react} io.ionic.starter --web-dir www --npm-client npm
__________________________________________________________________

## Resources

https://capacitor.ionicframework.com/docs/basics/workflow

https://ion.link/appflow

https://ion.link/enterprise-edition
__________________________________________________________________

fix src index.html <base href="/" /> to <base href="./" /> to work with electron
__________________________________________________________________

npm run generate-resources
npm run build-platforms