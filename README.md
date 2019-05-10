# kualitee-Android-sdk

## Installation

Add this to your app build.gradle file

```
repositories {
    maven {
        url "https://dl.bintray.com/virtualforce/KualiteeSDK"
    }
}
```

```
dependencies {
    implementation 'com.kualitee:kualiteesdk:1.0.1'
}
```

## Usage

Initialize the sdk in the onCreate() method of your Application class

```
ReportBugEngine.getInstance(this).initializeKualiteeSDK()
```
		    
