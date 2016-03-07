# XYZReader
RSS Feed reader to be improved with Material Design patterns

# Build
To build this application you need to install the following project dependencies:
 classpath 'com.android.tools.build:gradle:1.5.0'

For the App module you need to have in your environment the following build tool version:
 compileSdkVersion 23
 buildToolsVersion "23.0.2"

and all the following dependencies:
 compile 'com.android.support:support-v4:23.1.1'
 compile 'com.android.support:support-v13:23.1.1'
 compile 'com.android.support:appcompat-v7:23.1.1'
 compile 'com.android.support:design:23.1.1'
 compile 'com.android.support:palette-v7:23.1.1'
 compile 'com.android.support:recyclerview-v7:23.1.1'
 compile 'com.android.support:cardview-v7:23.1.1'
 compile 'com.squareup.okhttp:okhttp:1.1.0'
 compile files('libs/volley.jar')

Be sure to include in your project, under the /libs path, the volley.jar library file.

# Install
To install the App on your device/emulator, you have to ensure your Android API versione is 16 or above.

The following permissions will be needed:
android.permission.INTERNET
android.permission.WRITE_EXTERNAL_STORAGE
android.permission.BROADCAST_STICKY
android.permission.ACCESS_NETWORK_STATE
