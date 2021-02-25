fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## Android
### android lint
```
fastlane android lint
```
Runs linter
### android test
```
fastlane android test
```
Runs all the tests
### android buildDebug
```
fastlane android buildDebug
```
build clean debug app
### android bumpUpVersion
```
fastlane android bumpUpVersion
```
Bump up App Version
### android gitCommit
```
fastlane android gitCommit
```
Commit Changes
### android sendInfoTelegram
```
fastlane android sendInfoTelegram
```
Send notification to Telegram
### android beta
```
fastlane android beta
```
Submit a new Beta Build to Firebase App Distribution
### android deploy
```
fastlane android deploy
```
Deploy a new version to the Google Play

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
