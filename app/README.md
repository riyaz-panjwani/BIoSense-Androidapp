## Android Studio Setup

1. **Launch Android Studio:** Open Android Studio to begin the project setup.
2. **Create a New Project:** Click on "New Project" to initiate the project creation process.
3. **Choose Project Template:** Select the appropriate template for your project.
4. **Name Your Application:** Provide a suitable name for your application.
5. **Select Programming Language:** Choose Java as the preferred language for development.
6. **Specify Android Version:** Opt for [API 19 ("KitKat"; Android 4.4)] as the target Android version.

### User Interface
- **Activity Layout:** Design the user interface using the `activity_main.xml` file.
- to navigate to it click on <a href="https://github.com/riyaz-panjwani/BIoSense-Androidapp/blob/b40990c5d30bc3930d7ecc511cde79db89c82605/app/src/main/res/layout/activity_main.xml">activity_main.xml</a>
or <a href="app/src/main/res/layout/activity_main.xml">click here</a>

### Camera Access Configuration
- **Android Manifest Modification:** Make necessary adjustments in the `AndroidManifest.xml` file to grant camera access.
- to navigate to it click on <a href="https://github.com/riyaz-panjwani/BIoSense-Androidapp/blob/b40990c5d30bc3930d7ecc511cde79db89c82605/app/src/main/AndroidManifest.xml">AndroidManifest.xml</a>

### Integration of Machine Learning Model
- **Importing the Model:** Follow these steps to import your machine learning model into Android Studio:
    - Right-click on the app navigation folder located at the top-left corner.
    - Select "New" from the options.
    - Choose "Others" from the end of the list.
    - Opt for "TensorFlow Lite."
    - Browse and select your model file.
    - Click "Open" to successfully upload your machine learning model.

## Application Workflow

### MainActivity Configuration
- **Functionality Setup:** Implement necessary changes in the `MainActivity.java` file to ensure proper functioning of the application.
- to navigate to it click on <a href="https://github.com/riyaz-panjwani/BIoSense-Androidapp/blob/b40990c5d30bc3930d7ecc511cde79db89c82605/app/src/main/java/com/ad/biosense/MainActivity.java">MainActivity.java</a>

### Running the Application
- **Enable Developer Options:** Enable Developer options on your mobile device for application deployment.
- **Debugging Setup:** Turn on USB Debugging or Wireless Debugging as per your preference.
- **Establish Connection:** If using wireless connectivity, wait until the connection is established.
- **Initiate Application:** Click on "Run" to launch the application on your mobile device.

Upon Launch:
1. Initial Page: Upon launch, the application displays a basic page.
2. Camera Access: Clicking on "Take Picture" opens the camera interface.
3. Image Capture: After capturing a photo, the application prompts for confirmation to proceed.
4. Result Display: Upon confirmation, the application redirects to the user interface displaying the likelihood of each category.


Author - Riyaz Panjwani
