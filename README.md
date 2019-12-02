# Map Sample!

### Installation
 - `yarn install`
 - `react-native run-ios` for ios
 - `react-native run-android` for android

The actual map implementation depends on the platform. On Android, one has to use  [Google Maps](https://developers.google.com/maps/documentation/), which in turn requires you to obtain an  [API key for the Android SDK](https://developers.google.com/maps/documentation/android-sdk/signup) and include it into `AndroidManifest.java`

On iOS, one can choose between Google Maps or the native  [Apple Maps](https://developer.apple.com/documentation/mapkit/)  implementation.

When using Google Maps on iOS, you need also to obtain an  [API key for the iOS SDK](https://developers.google.com/maps/documentation/ios-sdk/get-api-key)  and include it into `AppDelegate.m`. The native Apple Maps based implementation works out-of-the-box and is therefore simpler to use at the price of missing some of the features supported by the Google Maps backend.
> **WARNING**: Before you can start using the Google Maps Platform APIs and SDKs, you must sign up and create a  [billing account](https://developers.google.com/maps/gmp-get-started#create-billing-account)!
