# **tru.ID** React Native Example Application

[![License][license-image]][license-url]

## Run example

- For iOS: Require XCode >12
- For Android:
    - Require JDK 14 (Java version 14.02 / Gradle v6.3).
    - Android Studio or Android SDK manager via [Android developer downloads](https://developer.android.com/studio).
    - Set `ANDROID_HOME` environment variable (ie `export ANDROID_HOME=~/Library/Android/sdk`). Although `$ANDROID_HOME` is apparently deprecated it is still required.
    - Accepted the SDK licenses `$ANDROID_HOME/tools/bin/sdkmanager --licenses` or `$ANDROID_SDK_ROOT/tools/bin/sdkmanager --licenses`
- For metro bundler, require node version > 10
- Setup and run the [tru.ID example server](https://github.com/tru-ID/server-example-node)
- Install dependencies: `yarn install`
- Create configuration `cp .env.example .env` and update the `BASE_URL` value in the `.env` file to point to your running example server
- To run on iOS run `yarn ios` or to run on Android run `yarn android`


## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## Meta

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/tru-ID](https://github.com/tru-ID)

[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE