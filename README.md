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
    implementation 'com.kualitee:kualiteesdk:1.0.2'
}
```

## Usage

Initialize the sdk in the onCreate() method of your Application class

```
ReportBugEngine.getInstance(this).initializeKualiteeSDK()
```

### Reporting a Defect

For bug reporting, just simply shake the device with the app opened. Kualitee SDK will capture a screenshot and present an image editor screen. After you are done editing, you will be redirected to Kualitee app for defect log.

### Crash Reporting

As soon as your application crashes, **KualiteeSDK** will save a crash report. The next time you open the Application, you will be prompted to either report this crash bug or ignore it.
		    
