fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios signing

```sh
[bundle exec] fastlane ios signing
```

Signs the iOS application with the proper certificate and installs proper provisioning profiles

### ios build_debug

```sh
[bundle exec] fastlane ios build_debug
```

Building WTHR ipa file

### ios build_adhoc

```sh
[bundle exec] fastlane ios build_adhoc
```

Build ad-hoc app version for firebase

### ios release

```sh
[bundle exec] fastlane ios release
```

Release IPA to firebase

### ios sync_certificates

```sh
[bundle exec] fastlane ios sync_certificates
```

Sync certificates from the GIT repo

### ios create_certificates

```sh
[bundle exec] fastlane ios create_certificates
```

Generate new certificates and profiles

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
