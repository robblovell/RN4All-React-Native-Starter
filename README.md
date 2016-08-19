![React Native Web](/app/assets/react-native-web.png "Logo React Native Web")

# Another React Native Starter (RN4All)

This uses as a base the react native for web starter (RN4Web). https://github.com/liivevideo/react-native-web-starter

It demonstrates a 4 environment build with one code base for a react native application:

* iOS
* Android
* Web
* Chrome (App, not an extension) 

## Install

```
git clone https://github.com/grabcode/react-native-web-starter.git projectname
cd projectname
rm -rf .git
npm install
```

## Run

#### iOS:
`npm run ios` - Runs in an iOS simulator (you need xCode).

#### Android:
`npm run and` - Runs in an android simulator (make sure the Android simulator is running first).

#### Web:
`npm run web` - your app is accessible at [http://localhost:3000](http://localhost:3000)

#### Chrome: 
Load your application into chrome: https://developer.chrome.com/apps/first_app

Go to [chrome://flags](chrome://flags).

Find "Experimental Extension APIs", and click its "Enable" link.

Restart Chrome.

Load your app

To load your app, bring up the apps and extensions management page by clicking the settings icon  and choosing Tools > Extensions.

Make sure the Developer mode checkbox has been selected.

Click the Load unpacked extension button, navigate to your app's folder and click OK.

Open new tab and launch

Once you've loaded your app, open a New Tab page and click on your new app icon.

Or, load and launch from command line

These command line options to Chrome may help you iterate:

``` --load-and-launch-app=/path/to/app/ ``` installs the unpacked application from the given path, and launches it. If the application is already running it is reloaded with the updated content.

``` --app-id=ajjhbohkjpincjgiieeomimlgnll ``` launches an app already loaded into Chrome. It does not restart any previously running app, but it does launch the new app with any updated content.

### TODO:

* Chrome Extension
* Server Side Rendered App
* Build and package for publishing 

