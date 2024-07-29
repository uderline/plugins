# Local Notifications Plugin library for NativeScript Android apps

## Building the framework
- Change anything needed
- Clean and build the project `./gradlew clean && ./gradlew build`
- Copy the release .aar to the `platforms` folder. In `packages/local-notifications` run:
  ```bash
  cp native-src/android/app/build/outputs/aar/app-release.aar platforms/android/
  ``` 
