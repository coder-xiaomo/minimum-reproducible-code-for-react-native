
```bash
# build apk
cd android && gradlew assembleRelease && cd ..

# install apk
adb uninstall com.awesomeproject
adb install -r -d android\app\build\outputs\apk\release\app-release.apk
```
