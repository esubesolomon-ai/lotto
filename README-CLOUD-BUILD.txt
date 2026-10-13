ETHIO LOTTERY DEMO — BUILD APK WITHOUT INSTALLING ANDROID STUDIO

This package contains:
- EthioLotteryDemo-Android-Source.zip (the Android project)
- .github/workflows/build-apk.yml (a cloud build workflow)

You will need a GitHub account and an internet connection. GitHub will build the APK on its servers; Android Studio is not required on your computer.

STEPS
1. Sign in to github.com and create a new repository, e.g. ethio-lottery-demo. A free account is enough. Choose Public or Private.
2. Upload EthioLotteryDemo-Android-Source.zip to the repository and commit it.
3. In GitHub, choose Add file > Create new file. For the filename enter exactly:
   .github/workflows/build-apk.yml
4. Open the build-apk.yml file included in this package with a text editor, copy all its contents into the GitHub editor, and commit the new file.
5. Open the repository's Actions tab. Choose “Build Ethio Lottery APK” from the workflows list and click “Run workflow”.
6. Wait for the workflow to finish successfully. Open the completed run, scroll to Artifacts, and download “Ethio-Lottery-Demo-APK”.
7. Extract that downloaded artifact ZIP. It contains app-debug.apk. Transfer it to your Android phone and install it. Android may ask you to allow installation from that source.

IMPORTANT
- This is only the simulated-payment demo. It is not a real-money lottery.
- The app is not production ready. Data resets when the app process closes, and ticket uniqueness is only local to the current app session.
- If the cloud build fails, open the workflow run and share the error log so it can be fixed.
