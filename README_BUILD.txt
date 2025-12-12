APK-READY Project - PrediksiBolaAI

How to build (Android Studio):
1. Unzip project
2. Open with Android Studio (File -> Open -> select folder)
3. Let Gradle sync
4. Build -> Build APK(s) -> Locate app-debug.apk in app/build/outputs/apk/debug/

How to build using Codemagic:
- Upload this repo to GitLab/GitHub and connect to Codemagic
- Codemagic will run codemagic.yaml and produce app-debug.apk artifact

Replace assets/proxy_meta.tflite and proxy_ou.tflite with real TFLite models before using offline inference.
