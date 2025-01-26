# Dependency


plugins {
   
    id("com.google.dagger.hilt.android")
    id("com.google.devtools.ksp")

}

dependency{

 implementation("com.google.dagger:hilt-android:2.51.1")
    ksp("com.google.dagger:hilt-android-compiler:2.51.1")

    ksp("com.google.dagger:hilt-compiler:2.51.1")

}

//module
plugins {

    id("com.google.devtools.ksp") version "2.1.0-1.0.29"
    id("com.google.dagger.hilt.android") version "2.51.1" apply false
}
