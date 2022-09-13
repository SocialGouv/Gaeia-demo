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

### ios IncrementBuildNumber

```sh
[bundle exec] fastlane ios IncrementBuildNumber
```

Auto Increment BuildNumber

### ios SetVersiondNameToMatchPackageJson

```sh
[bundle exec] fastlane ios SetVersiondNameToMatchPackageJson
```

Set version number

### ios beta

```sh
[bundle exec] fastlane ios beta
```

Push a new beta build to TestFlight

### ios betaGithub

```sh
[bundle exec] fastlane ios betaGithub
```

Push a new beta build to TestFlight via github actions

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
