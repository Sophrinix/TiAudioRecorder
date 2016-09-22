TiAudioRecorder
===========================================

Titanium Mobile module for Android. You can record audio data with this module. Don't be evil.

The module has been update for titanium 5.5.0.GA and is in the dist folder.

USAGE
---------------------
See example/app.js.
Don't forget to add permission. On building your app, don't run, walk nor crawl.

```
$ mkdir -p ${PROJECT_HOME}/platfom/android
$ cp ${PROJECT_HOME}/build/android/AndroidManifest.xml ${PROJECT_HOME}/platform/android/
```

And add user-permission:

```xml
	<uses-permission android:name="android.permission.RECORD_AUDIO"/>
```
It might also be a good idea to have storage.
O.K. Now you can go as far as you can go. Build your app and run it.

LICENSE
---------------------
MIT License

Copyright 2012 Toshiro Yagi   
http://selfkleptomaniac.org/   
Twitter: @yagi_  
