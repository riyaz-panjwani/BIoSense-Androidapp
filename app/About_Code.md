## AndroidStudio Guide

1. **Open Android studio**
2. **Click on a new project**
3. **Select the type of template**
4. **Name the Application**
5. **Select Language**
6. **Select the Android version** (Here we have selected [API 19 ("KitKat"; Android 4.4)])
7. **User Interface:** We are going to make our user interface in `activity_main.xml`
8. **Permissions:** We make little changes in `AndroidManifest.xml` – This is to access camera permission
9. **Import Machine Learning Model:** Now we import our machine learning model into Android Studio
    - Right click on the top left app navigation folder
    - Click on New
    - At the end of the list we have Others click on it
    - Select TensorFlow Lite
    - Browse your Model i.e. Select your model
    - Click on Open
    - Now you have successfully loaded your machine learning model
10. **MainActivity Modifications:** Now for the machine learning model to work we are going to make changes in `MainActivity.java` file
11. **Run the Application:** After making appropriate changes we are ready to run our application on mobile
12. **Enable Developer Options:** To run your application on mobile we are going to enable Developer options on your phone
13. **Debugging:** Turn on USB Debugging or Wireless Debugging
14. **Connectivity:** And connect if it is wireless if USB wait till the connection is established
15. **Run Application:** After establishing the connection click on Run. Your phone is going to open the application which will look like this.
16. **Capture Image:** Click on Take Picture. You will then see image (i) and take a picture you will see image (ii)
17. **Result:** After you confirm the selection it will process the image and give the result with the percentages of likeliness on each type
