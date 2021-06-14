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
## iOS
### ios runtests
```
fastlane ios runtests
```
Test The 
### ios build
```
fastlane ios build
```
Build and send app to Firebase App Distribution
### ios sign_app_and_upload
```
fastlane ios sign_app_and_upload
```
Sign apps and upload to Firebase/AppStore/AppCenter etc

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
