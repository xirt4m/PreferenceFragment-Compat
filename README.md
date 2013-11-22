Support PreferenceFragment
=====================================

Unofficial PreferenceFragment compatibility layer for Android 1.6 and up.

How to reference this library?
====================================

Make sure you have maven central listed as a repository on your build.gradle like this:

```groovy
repositories {
    mavenCentral()
}
```

Add the dependency to your build.gradle file like this:

```groovy
compile 'com.github.machinarius:preferencefragment:0.1@aar'
```

The @aar suffix is a workaround for a packaging problem, next release won't be affected by this.

How to use it?
===================================

Just extend PreferenceFragment and follow the Settings developer guide like if this layer wasn't even there to begin with.
http://developer.android.com/guide/topics/ui/settings.html

Roadmap
==================================
- Bump the presentation of the settings on Gingerbread and lower with some Holo love
- Include a handful of useful extra preferences