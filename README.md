# try-flutter-webview-app
## Set up
Installing Flutter  
https://docs.flutter.dev/get-started/install

## Run a webview app for dev.
```zsh
# run a Next.js web app.
cd web-app
npm ci
npm run dev

# run a Flutter iOS app.
cd ../native_app
open -a Simulator
flutter pub get
flutter run
```
