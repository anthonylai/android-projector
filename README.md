### Instructions
- Install Android SDK
- Download [AndroidProjector.jar](https://github.com/anthonylai/android-projector/blob/master/build/jar/AndroidProjector.jar) and [android-projector](https://raw.githubusercontent.com/anthonylai/android-projector/master/build/jar/android-projector) from build/jar into the same directory

### To start screen projection
#### Single Android device only
- ./android-projector

#### Multiple Android devices
- adb devices 
Example output:
adb devices
List of devices attached 
0119CBF00B009006 device
0149CBF00B009222 device

- ./android-projector 0149CBF00B009006
- ./android-projector 0149CBF00B009222
