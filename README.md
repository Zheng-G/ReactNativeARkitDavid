# Your requirement

Set up a repo for a react-native app that works on iphone and android.  Bring in the AR kits for both android and iphone and make sure the front-facing camera is the first screen displayed. Bring in the AR anchors for both as well and make it so you can set a placeholder anchor

For this I was used [`react-native-arkit`]

**Note**: ARKit is only supported by devices with A9 or later processors (iPhone 6s/7/SE/8/X, iPad 2017/Pro) on **iOS 11**. You also need **Xcode 9** to build the project.


## How to run the project

1. `git clone https://github.com/ZhengGuoDeveloper/ReactNativeARKit.git`;
2. In the project folder, `yarn install` the dependencies (npm broken atm.)
3. Go to the `ios` folder and open `ReactNativeARKit.xcodeproj`. Build and run on your physical devices (ARKit doesn't run on simulators).
4. You also need to change the signing team 

Notice: the project is using "Release" config on run. If you want to debug and develop, change it to "Debug"
