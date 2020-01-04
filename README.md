# Assistive Technology: Object Detection

## Description

Create an object detection application that will work on a mobile platform. This application will assist a blind user detect 3 objects of interest: car, chair and person.

Our team reused Pre-trained model of Tensorflow Lite with a quantized MobileNet SSD model trained on the COCO dataset. From the Tensorflow Lite, my team developed three more functions: Estimating the distance of an object from the camera, their relative position and text to speech function.

## Members

* Anh The Nguyen
* Srinivas Shashank Mulugu
* Monica Selvam
* Nikhillesh Sadassivam

## Build the demo using Android Studio[1]

### Prerequisites

* If you don't have already, install **[Android Studio](https://developer.android.com/studio/index.html)**, following the instructions on the website.

* You need an Android device and Android development environment with minimum API 21.
* Android Studio 3.2 or later.

### Building
* Open Android Studio, and from the Welcome screen, select Open an existing Android Studio project.

* From the Open File or Project window that appears, navigate to and select the tensorflow-lite/examples/object_detection/android directory from wherever you cloned the TensorFlow Lite sample GitHub repo. Click OK.

* If it asks you to do a Gradle Sync, click OK.

* You may also need to install various platforms and tools, if you get errors like "Failed to find target with hash string 'android-21'" and similar.
Click the Run button (the green arrow) or select Run > Run 'android' from the top menu. You may need to rebuild the project using Build > Rebuild Project.

* If it asks you to use Instant Run, click Proceed Without Instant Run.

* Also, you need to have an Android device plugged in with developer options enabled at this point. See **[here](https://developer.android.com/studio/run/device)** for more details on setting up developer devices.

## Using the APK file to install
You can copy the Object-Detection.apk file in the Installation folder to your phone and then install it to run the program.

## References

[1] Lian, Tian, Copybara-Service. TensorFlow Lite Object Detection Android Demo. 2019. https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android
