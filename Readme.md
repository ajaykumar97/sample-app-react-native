# Sample App React Native

## Installation Steps

1. Clone the repo

```
git clone https://github.com/ajaykumar97/sample-app-react-native.git
```

2. Install `node_modules`

if using `yarn`:

```
yarn install
```

if using `npm`:

```
npm install
```

3. Install `pods` (if running on MacOS)

An automation script [runPostInstallUninstallTasks](./scripts/runPostInstallUninstallTasks.js) is added into the project which will run after every npm dependency `install` or `uninstall`. Using this, the step 2 will automatically install the pods for iOS if you are using the MacOS. For some reason, if the step 2 will fail to install the pods, then you can mannually install the pods using:

```
cd ios && pod install
```

4. Running the app
- **To run Android Staging Debug:** `yarn androidStagingDebug` or `npm run androidStagingDebug`
- **To run iOS Staging Debug:** `yarn iosStagingDebug` or `npm run iosStagingDebug`
- **To run Android Production Debug:** `yarn androidStagingDebug` or `npm run androidProductionDebug`
- **To run iOS Production Debug:** `yarn androidStagingDebug` or `npm run iosProductionDebug`


## Digging Deeper
This project is created using my open-sourced [react-native-template](https://github.com/ajaykumar97/react-native-template). Feel free to use it in your project or to create your own template. Happy coding 😃.