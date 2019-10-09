# DevByte Viewer App

Application permettant de récupérer un flux de données REST et de créer un cache hors ligne. Il s'agit de la mise en pratique de la lesson 9 ["Behind the Scenes"](https://classroom.udacity.com/courses/ud9012/) de Google (Udacity)

## Concepts mis en oeuvre

* Room avec un repository pour la mise en place du cache hors ligne
* WorkManager pour créer une maj des données journalières en tâche de fond

## Prérequis

* Android Studio

## Installation

Télécharger le .zip du projet, extraire le contenu dans le répertoire de votre choix et ouvrir ce répertoire dans Android Studio.

## Version SDK

* minSdkVersion 19
* targetSdkVersion 28

## Dépendances

```
ext {
        version_core = "1.0.1"
        version_coroutine = "1.1.0"
        version_retrofit_coroutines_adapter = "0.9.2"
        version_navigation = '1.0.0'
        version_constraint_layout = "2.0.0-alpha3"
        version_gradle = '3.3.2'
        version_kotlin = "1.3.21"
        version_lifecycle_extensions = "2.0.0"
        version_room = "2.0.0"
        version_appcompat = "1.0.2"
        version_fragment = "1.0.0"
        version_retrofit = "2.5.0"
        version_kotlin_coroutines = "1.1.0"
        version_moshi = "1.8.0"
        version_glide = "4.8.0"
        version_joda = "2.10"
        version_work = "1.0.0-alpha11"
        version_timber = "4.7.1"
    }
```

* Support libraries
    * androidx.appcompat:appcompat:$version_appcompat
    * androidx.fragment:fragment:$version_fragment
    * androidx.constraintlayout:constraintlayout:$version_constraint_layout

* Android KTX
    * androidx.core:core-ktx:$version_core

* Navigation
    * android.arch.navigation:navigation-fragment-ktx:$version_navigation
    * android.arch.navigation:navigation-ui-ktx:$version_navigation

* Coroutines for getting off the UI thread
    * org.jetbrains.kotlinx:kotlinx-coroutines-core:$version_kotlin_coroutines
    * org.jetbrains.kotlinx:kotlinx-coroutines-android:$version_kotlin_coroutines

* Retrofit for networking
    * com.squareup.retrofit2:retrofit:$version_retrofit
    * com.squareup.retrofit2:converter-moshi:$version_retrofit
    * com.jakewharton.retrofit:retrofit2-kotlin-coroutines-adapter:$version_retrofit_coroutines_adapter

* Moshi for parsing the JSON format
    * com.squareup.moshi:moshi:$version_moshi
    * com.squareup.moshi:moshi-kotlin:$version_moshi

* Joda time library for dealing with time
    * joda-time:joda-time:$version_joda

* ViewModel and LiveData (arch components)
    * androidx.lifecycle:lifecycle-extensions:$version_lifecycle_extensions

* Logging
    * com.jakewharton.timber:timber:$version_timber

* Glide for images
    * com.github.bumptech.glide:glide:$version_glide

* Room database
    * androidx.room:room-runtime:$version_room
    * kapt "androidx.room:room-compiler:$version_room

* WorkManager
    * android.arch.work:work-runtime-ktx:$version_work

## Capture d'écran

<img src="./screenshots/devbyte-homescreen.png" width="200">
