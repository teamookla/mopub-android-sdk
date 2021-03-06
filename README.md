# MoPub Android SDK

Thanks for taking a look at MoPub! We take pride in having an easy-to-use, flexible monetization solution that works across multiple platforms.

Sign up for an account at [http://app.mopub.com/](http://app.mopub.com/).

Help is available on the [wiki](https://github.com/mopub/mopub-android-sdk/wiki/Getting-Started).

## Download

The MoPub SDK is distributed as source code that you can include in your application.  MoPub provides two prepackaged archives of source code:

- **[MoPub Android Full SDK.zip](http://bit.ly/YUdU9v)**

  Includes everything you need to serve HTML and MRAID MoPub advertisiments *and* built-in support for Millennial Media third party ad network - [Millennial Media](http://www.millennialmedia.com/) - including the required third party binaries.

- **[MoPub Android Base SDK.zip](http://bit.ly/YUdWhH)**

  Includes everything you need to serve HTML and MRAID MoPub advertisements.  No third party ad networks are included.

## Integrate

Integration instructions are available on the [wiki](https://github.com/mopub/mopub-android-sdk/wiki/Getting-Started).


## New in this Version

Please view the [changelog](https://github.com/mopub/mopub-android-sdk/blob/master/CHANGELOG.md) for details.

- Dependency changes in Maven and Gradle. No new dependencies have been added, but your build script will need to change slightly to include JCenter. See our [Getting Started Guide](https://github.com/mopub/mopub-android-sdk/wiki/Getting-Started#adding-the-support-libraries-to-your-project) for complete instructions.
- Security Improvement: removed the @JavascriptInterface annotation for WebViews.
- Fixed a bug where video playback would sometimes fail to stop when an ad was dismissed.
- Fixed a bug where it was not possible to disable ad refresh; Fixes [issue #148](https://github.com/mopub/mopub-android-sdk/issues/148)
- Fixed a null pointer exception in AdViewController; Fixes [issue #150](https://github.com/mopub/mopub-android-sdk/issues/150)

## Requirements

- Android 2.3.1 (API Version 9) and up
- android-support-v4.jar
- android-support-annotations.jar (**New in 3.3.0**)
- MoPub Volley Library (mopub-volley-1.0.0.jar - available on JCenter) (**Updated in 3.5.0**)
- **Recommended** Google Play Services 5.0.89 & up.

## Upgrading from 3.2.0 and Prior
In 3.3.0 a dependency on android-support-annotations.jar was added. If you are using Maven or Gradle to include the MoPub SDK, this dependency is included in the build scripts. For instructions on adding dependencies for Eclipse projects, see our [Getting Started Guide](https://github.com/mopub/mopub-android-sdk/wiki/Getting-Started#adding-the-support-libraries-to-your-project)

## License

We have launched a new license as of version 3.2.0. To view the full license, visit [http://www.mopub.com/legal/sdk-license-agreement/](http://www.mopub.com/legal/sdk-license-agreement/).
