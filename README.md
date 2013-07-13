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
        compile "com.actionbarsherlock:actionbarsherlock:4.3.2-SNAPSHOT"
        compile "com.jeremyfeinstein:slidingmenu:1.3-SNAPSHOT"
        compile "de.keyboardsurfer:crouton:1.8.1"
        compile "com.loopj:android-async-http:1.4.3"
    }

Notes
======
    SlidingMenu in this repo is uses SherlockFragmentActivity instead of FragmentActivity
