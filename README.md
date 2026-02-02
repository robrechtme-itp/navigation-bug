# Bug report for [expo#42777](https://github.com/expo/expo/issues/42777)

1. Run the app and open the modal. Pressing the close modal button, freezes the app
2. In `package.json`, remove `expo-dev-client` and rebuild the app
3. Now opening and closing the modal works fine.


| With expo-dev-client | Without expo-dev-client |
| -- | -- |
|<video src="./recordings/with-dev-client.mp4" controls width="300"></video>|<video src="./recordings/without-dev-client.mp4" controls width="300"></video>|
