# Image-Transmission-via-Python-Flask
NOTE: In order for the project to work, both the client and serer devices need to be on the same network.
The repository consists of two main folders:
* **Flask Server**: The device on which the image is to be received and is the Python-based server using Flask
* **Android Client**: The Android Studio project which creates an apk working as a client. It is run from the android device from which the image is to be transmitted.

To successfully run the project, follow the steps mentioned:
* Open the Android Studio Project, run the application. This will create the APK that would work as the client.
* Then, run the Python Flask-server based file on the console of the device
* Once the server is running, then go back to the Android app. Choose the image you would like to transmit.
* Edit the box of the IPv4 address and port number to the current IPv4 address and port number of the server visible on the console.
* Click on the Connect to Server button to transmit the image to the device set up as the server
