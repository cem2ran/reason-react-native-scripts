# reason-react-native-scripts

Early, experimental version of BuckleScript / ReasonReact / Rebolt support integrated into [Create React Native App](https://github.com/react-community/create-react-native-app) to make starting a Reason project with React Native dead simple.

## Use it

```
yarn global add create-react-native-app
create-react-native-app HelloWorldRe --scripts-version reason-react-native-scripts
cd HelloWorldRe
yarn start
```

You will see some peerDependencies warnings, don't worry about it. I told you this was early and experimental, right? 😅

## Development

`yarn && yarn start` will start a watcher that will build artifacts and place them in the build directory.
