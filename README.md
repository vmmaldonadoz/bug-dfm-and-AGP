## [Android] Bug with DFM (Dynamic Feature Modules) and AGP 4.1 with Gradle cache enabled.

This repo reproduces the bug reported here:
https://issuetracker.google.com/issues/171907683

### How to reproduce?
Run `./gradlew clean :app:bundleQa --build-cache`

### Scenario:
* Gradle version: 6.5
* AGP version: 4.1
* minifyEnabled: true
* Gradle Cache Enabled? Yes
* Gradle scan: https://scans.gradle.com/s/a775vgdapin7w
