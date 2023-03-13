# JUCE Audio Demo

You'll find here the full project that illustrates my 3-part series on how to implement JUCE in an Android app and in an iOS app:
- [How to create a C++ JUCE library for Android and iOS](https://medium.com/@mregnauld/play-any-sound-in-an-android-or-ios-app-with-juce-3f03b1a7238c){:target="_blank"}
- [How to implement the C++ JUCE library in an Android and iOS project](https://medium.com/@mregnauld/play-any-sound-in-an-android-or-ios-app-with-juce-2-3-a540aab4ac48){:target="_blank"}
- [How to play a basic sound using the C++ JUCE library in an Android and iOS app](https://medium.com/@mregnauld/play-any-sound-in-an-android-or-ios-app-with-juce-3-3-703dba858d3a){:target="_blank"}

Note that the project is a Flutter project, but if you go to the `android/` or `ios/` directory, you should feel at home.

# Required steps to make it work

If you want to `git clone` that project and test it locally, you'll first need to:
- [download](https://juce.com/get-juce/){:target="_blank"} and install JUCE
- For Android:
  - edit the `CMakeLists.txt` file
  - change the `${USER_HOME_DIR}/JUCE` (x2) by the path where you installed JUCE, if needed
- For iOS:
  - Go to *Runner (Project) > Build Settings > Search Paths*, then *Header Search Paths*
  - change the `$SRCROOT/../../../../JUCE/modules` by the path where you installed JUCE, if needed
