[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-AARLinkSources-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/1288)

AARLinkSources Plugin
====
The AARLinkSources Plugin is designed to attach sources for .aar/.jar dependencies in AndroidStudio.

Setup
----
~~~groovy
buildscript {
    repositories {
        maven { url 'https://raw.github.com/hyperconnect/AARLinkSources/repository' }
    }

    dependencies {
        classpath 'com.github.xujiaao:aarLinkSources:1.0.2'
    }
}
~~~

Usage
----
~~~groovy
apply plugin: 'aar-link-sources'
~~~



