# Axinom DRM Sample Player

This is a sample project of an Android video player application. Its purpose is to provide a starting point for developers
who want to implement a player application that includes support for Axinom DRM playback.

The application is a clone of AndroidX Media(1.3.1) which includes the latest ExoPlayer and other libraries for implementing media uses cases on Android.
The application itself can be used for demonstration and testing purposes of the mentioned features.


# Important files

Here is a list of important files in the project.

[SampleChooserActivity.java](demos/main/src/main/java/androidx/media3/demo/main/SampleChooserActivity.java)
* A class that loads sample videos from [media.exolist.json](/demos/main/src/main/assets/media.exolist.json).
  This json file can be modified to add your own sample videos for the application to use.

[PlayerActivity.java](demo/main/src/main/java/androidx/media3/demo/main/PlayerActivity.java)
* An activity that plays media using ExoPlayer.

[DemoDownloadService.java](demo/main/src/main/java/androidx/media3/demo/main/DemoDownloadService.java)
* A service for downloading media.


# Device compatibility

* This project is compatible with devices running Android 10.0 or newer.


# How to run the application

* Clone the drm-sample-player-android-media3 computer.
* Open Android Studio (Jellyfish | 2023.3.1) or newer and import the cloned project (File -> Open -> ProjectRootFolder) 
* Select demo or root project and build the application. (Build -> Make Project)
* Connect an Android device or pick a device from Android emulator and Run the application. (Run -> Run 'demo')


# How to use the application

* Select type of content from the list to expand videos.
* From the expanded list select the video you want to play.


# AndroidX Media

More details on Android MediaX can be found here `https://github.com/androidx/media`