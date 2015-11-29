# Development instructions (Linux)

You need Node and an android development kit as described at [React Native Documentation Site](https://facebook.github.io/react-native/docs/getting-started.html)

Once you got all installed and configured, you can run this commands to debug the app on your phone:
```
> adb reverse tcp:8081 tcp:8081
> react-native run-android
```

