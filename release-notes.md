## Release Notes

### Version 2022.25.1

####  Virtual display
#####  Performance improvements 

Display component has been refactored in order to allow up to 60Hz refresh rate.
Tesla Android will now behave normally when loaded in Drive or Reverse.
Simplification of video stack improves stability of the Flutter application running in the Tesla Browser.

####  Audio Output
#####  Combined audio streams

Audio from Android is routed directly to your Tesla Browser.
Playback is allowed even when Drive or Reverse is engaged, meaning that there is no need to pair Tesla Android with your car using Bluetooth(Bluetooth link with the car is only used by your phone for Android Auto or CarPlay).
Audio output from Tesla Browser does not pause media playback from Tesla OS or CarPlay.
In order to active this feature open Audio Capture app on your Tesla Android after installing the OS. It will automatically launch on each boot later. Audio Capture can be terminated using a button present in the status notification.
Not all apps support audio capture, this restriction will be removed in a feature update.

####  Flutter Frontend
#####  Stability improvements

Flutter Frontend has been updated in order to improve user experience.
Loading times have been improved significantly.
All major components of the app now have proper state management and error handling.

####  Android Platform
#####  Move to Android 12.1

Tesla Android has been migrated to Android 12.1 from AOSP Master in order to improve stability.
Release 2022.25.1 includes Android security updates up to May 5, 2022.

####  Orientation lock
#####  All apps launch in landscape

Tesla Android now includes a working orientation lock for third party apps.
This feature allows phone apps like Apple Music to launch in landscape.

####  Google Play Store
#####  App discoverability

Google Play Store has been replaced with Aurora Store, an Open Source alternative that includes Device Spoofing(emulating Google certification).
Google Play Services have been replaced with microG(Open Source Google Apps).
FDroid(Open Source App Store that does not rely on Google Play Store) is also included.",

####  Video Streaming
#####  DRM support

Tesla Android now supports DRM video playback. Apps like Netflix function normally in version 2022.25.1.

####  CarPlay
#####  Audio/Video improvements

Default resolution of CarPlay is a perfect match for Tesla Android in this release(no content overlapping in audio apps).
Navigation sounds also work, however this feature is active only when Tesla Browser is active.

####  Setup
#####  Simplified device configuration

Setup process of Tesla Android has been simplified, meaning several steps are no longer needed(obtaining a device identifier for Google Services, switching CarPlay resolution etc).

#### Version 2022.18.1

Initial release
