# Ionic 2 Preview App

This app accompanies the Ionic 2 component documentation.

[[LIVE DEMO]](http://ionicframework.com/docs/v2/components/)

### Installation & Development

1. clone this repo: `git clone https://github.com/liuhaidl-samples-projects/mobile-ionic2-previewApp.git`
2. `cd mobile-ionic2-previewApp`
3. `npm install`
4. run `ionic serve` from a terminal
5. or run 'ionic serve -l' with live reload mode

### Testing your app in emulator mode

1. run `ionic platform add ios|android` based on your computer os, for example MacOS, Windows etc
2. run `ionic run ios` with ios emulator default mode
3. or run `ionic run ios -l` with ios emulator and live reload mode 

### Running locally on the site

1. Clone `ionic-site` as a sibling directory to this app: `git clone git@github.com:driftyco/ionic-site.git`
2. Follow the steps for running `ionic-site` locally: [https://github.com/driftyco/ionic-site#local-build](https://github.com/driftyco/ionic-site#local-build)
3. Follow the steps for running this repo: [https://github.com/driftyco/ionic-preview-app#installation--development](https://github.com/driftyco/ionic-preview-app#installation--development)
4. Make any changes you want to this project and then build/serve it
5. Copy the www folder to `ionic-site/dist/preview-app/`: `cp -R www ../ionic-site/content/dist/preview-app`
6. If the site doesn't update you may need to restart `gulp watch`


### Updating ionic-site

`ionic-site` will automatically update on every commit to the master branch of this repo.

### Issues
 1. `sudo ionic *` //please run the above ionic commands with sudo when system admin privilege is required. For example, sudo ionic platforms add ios
 2. `sudo chown -R loginUser:group *` //for example chown -R liuhaidl:staff * to resolve the emulator startup failed issue
