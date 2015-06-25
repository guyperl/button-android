# Button Android Deep Link Commerce

<p align="center"><img src="http://www.usebutton.com/img/sdk/img_dlc-preview.png" width="204"/>
</p>

<h1 align="center">Button DeepLink Commerce</h1>

## Overview

Button DeepLink Commerce enables rich cross-application functionality initiated from drop-in `Buttons`. Buttons act as the entry point to highly-contextual, fully attributed actions across apps.

The DeepLink Commerce (DLC) SDK provides full functionality for both sending and receiving users, attributed within the DLC network.

Add a `Button` to your app, pass it some `context` and it will render & display itself. e.g...

<p align="center"><img src="http://www.usebutton.com/img/sdk/img_dlc-uber-button.png" width="300" />
<br/>
<code>Ride</code> use-case with an <code>end-location</code>
</p>

## Getting started

### Gradle integration

We highly recommend that you use our SDK with Gradle, simply add our repository to your project and this dependency.

```
repositories {
    maven {
        url  "http://dl.bintray.com/button/Public" 
    }
}
```

Latest version: ![Download](https://api.bintray.com/packages/button/Public/android-sdk/images/download.svg).

```
dependencies {
    // Add the Button SDK dependency to the list of dependencies, 
    // you can see the latest version in the badge above
    // Replace + with this number, e.g. 1.0.0
    compile 'com.usebutton:android-sdk:+'
}
```

### Manual integration

But you can also include us manually by dropping our `aar` into you `/libs` folder, click [ ![Download](https://api.bintray.com/packages/button/Public/android-sdk/images/download.svg) ](https://bintray.com/button/Public/android-sdk/_latestVersion) to get the latest version.


### Next Steps

1. Get an Application ID by signing up here: [app.usebutton.com](https://app.usebutton.com/).
2. Follow the [DeepLink Commerce Integration Guide](https://www.usebutton.com/sdk/deep-link-commerce-android/) to get DLC in your app!


You can find the full [SDK Documentation](http://building.usebutton.com/button-android/latest/reference/com/usebutton/sdk/Button.html) here.

## Samples

You can find relevant example code and a fully working sample application in our [button-android-sample](https://github.com/usebutton/button-android-samples) repository.

## Release notes
### [1.1.0 Docs](http://building.usebutton.com/button-android-public/history/1.1.0/reference/com/usebutton/android-sdk/Button.html)
* DLC Recipient Functionality (BETA)
* Minor bugfixes
* More reliable fetching of Identifier for Advertiser

### [1.0.0 Docs](http://building.usebutton.com/button-android/history/1.0.0/reference/com/usebutton/sdk/Button.html)
* First public release of the DLC SDK
* Supports Uber ride picker
* Supports generic promotions and install cards

### [0.9.16 Docs](http://building.usebutton.com/button-android/history/0.9.16/reference/com/usebutton/sdk/Button.html)
* Ut enim ad minima veniam
* Quis nostrum exercitationem 
* Qullam corporis suscipit laboriosam

### [0.9.14 Docs](http://building.usebutton.com/button-android/history/0.9.14/reference/com/usebutton/sdk/Button.html)
* Ut enim ad minima veniam
* Quis nostrum exercitationem 
* Qullam corporis suscipit laboriosam

### [0.9.13 Docs](http://building.usebutton.com/button-android/history/0.9.13/reference/com/usebutton/sdk/Button.html)
* Ut enim ad minima veniam
* Quis nostrum exercitationem 
* Qullam corporis suscipit laboriosam