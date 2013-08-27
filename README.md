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
        compile "com.android:volley:1.0"
        compile "com.jeremyfeinstein:slidingmenu:1.3-SNAPSHOT"
        compile "com.koushikdutta.ion:ion:1.1.6"
        compile "com.loopj:android-async-http:1.4.3"
        compile "de.keyboardsurfer:crouton:1.8.1"
        compile "uk.co.senab:photoview:1.2.1"
        compile "com.bumptech:glide:1.0.0"
    }

Notes
======
    SlidingMenu in this repo is uses now uses the support FragmentActivity

    ActionBarSherlock was removed and SlidingMenu was reverted to original so that AppCompat library can be used.
