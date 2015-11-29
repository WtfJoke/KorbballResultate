# This is the app for all swiss Korbball results

If you just want to run it on your smartphone go visit Google Play and search for "Korbball Resultate". If you want to help me you're welcome to read on or contact me.

# Development instructions (Linux)

The app is based on Facebook's react native. So it is certainly helpful if you first
follow theire [Tutorial](https://facebook.github.io/react-native/docs/tutorial.html#content).
The content for the app comes from http://korbball.turnverband.ch/ws/ and 
http://korbball.info/admindb/ws/. The app just consumes those APIs and assembles it
to a pleasant form.

You need Node and an android development kit as described at 
[React Native Documentation Site](https://facebook.github.io/react-native/docs/getting-started.html).

Once you got all installed and configured, you can run this commands to debug the app on your phone:

```
> adb reverse tcp:8081 tcp:8081
> react-native run-android
```
