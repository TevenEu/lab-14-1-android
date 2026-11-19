# Image Labelling · Lab 14.1

Download the [Android Studio project](steeven_eugenio_lab14_1.zip), unzip it, and open the extracted project folder in Android Studio.

**Steeven Eugenio · Yachay Tech**

This Android app uses the bundled Google ML Kit model to label images. The user grants access to one image through Android's document picker. The app displays each label and its confidence when the score meets the 50% threshold. Inference runs on the device.

1. Open this directory in Android Studio and sync Gradle. Use JDK 17 or later and install Android SDK 35.
2. Start an Android Virtual Device (API 23 or later) or connect an Android phone.
3. Run `app`, tap **Choose an image**, and select a JPG or PNG. On an emulator, import an image first if its Downloads folder is empty.
4. Check the preview and the labels below it.

[Google ML Kit documentation](https://developers.google.com/ml-kit/vision/image-labeling/android)
