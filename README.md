# Expo Camera Preview Freeze on Android

This repository demonstrates a bug in the Expo Camera API where the camera preview freezes on certain Android devices. The preview may show a black screen, and the `onCameraReady` callback is not fired. The behavior is inconsistent and there are no clear error messages.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app on an affected Android device (see devices listed in the issue). 
4. Observe that the camera preview freezes and `onCameraReady` is not triggered.

## Potential Causes

The cause of this bug is currently unknown, but it may be related to specific Android device configurations or Expo SDK versions. We are actively investigating this.