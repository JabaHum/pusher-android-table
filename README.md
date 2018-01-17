# pusher-android-table
In this application we will be utilizing the Pusher Android SDK's client-side library to quickly build a real-time data table.

The flow of the app is that when the user launches the app, (s)he will  fill out a form to add a new employee to an employees table and click a “save” button. This will send a POST request to our server. In this tutorial, we will use a simple NodeJS server to provide a single API endpoint.
Once our server receives the POST request, it will render the data to all connected clients, which will show the data on their tables in realtime.

To Set Up this project in your machine you'll need to take a few steps.
1. Install Android Studio if you haven't already
2. Clone this repo and open in AS
3. Sync the project and import all required dependencies
4. Create two drawable files called buttonstyle.xml and layoutstyle.xml and copy the attached codes into the respective files. 
5. Create a Pusher Account and get your credentials ready for use
6. Set up a simple Node.js server with your pusher credentials to handle your requests
7. And finally run the app and give it a spin 



buttonstyle.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">

    <stroke android:color="#000"
            android:width="2dp"/>
    <corners android:radius="15dp"/>
    <solid android:color="#2a2d93"/>

</shape>
```

layoutstyle.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">

    <stroke android:color="#000"
            android:width="2dp"/>
    <corners android:radius="15dp"/>

</shape>
```
