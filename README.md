How to use
==========

Add the repository to your build.gradle file:

    repositories {
        maven {
            url 'https://github.com/AfzalivE/my-mvn-repo/raw/master/'
        }
        mavenCentral()
    }

And you can use the artifacts like this:

    dependencies {
        compile 'com.activeandroid:activeandroid:3.1-SNAPSHOT'
        compile 'com.akexorcist:bluetoothspp:1.2'
        compile 'com.android:volley:1.0'
        compile 'com.echo.holographlibrary:HoloGraphLibrary:1.0'
        compile 'com.jeremyfeinstein:slidingmenu:1.3-SNAPSHOT'
        compile 'com.jjoe64:GraphView:3.1.2-SNAPSHOT'
    }

Notes
======
    SlidingMenu in this repo is uses now uses the support FragmentActivity

    ActionBarSherlock was removed and SlidingMenu was reverted to original so that AppCompat library can be used.
