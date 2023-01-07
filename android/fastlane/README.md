fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android increment_firebase_version

```sh
[bundle exec] fastlane android increment_firebase_version
```

Runs all the tests

Increment the version from the latest firebase release

### android increment_playstore_version

```sh
[bundle exec] fastlane android increment_playstore_version
```

Increment the version from the latest playstore release - In progress

### android beta

```sh
[bundle exec] fastlane android beta
```

Submit a new Beta Build to firebase distribution

### android deploy

```sh
[bundle exec] fastlane android deploy
```

Deploy a new version to the Google Play - In progress

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
