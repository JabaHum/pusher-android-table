# Realtime Table Demo in Android with Pusher
In this application we will be utilizing the Pusher Android SDK's client-side library to quickly build a real-time data table.

The flow of the app is that when the user launches the app, (s)he will  fill out a form to add a new employee to an employees table and click a “save” button. This will send a POST request to our server. In this tutorial, we will use a simple NodeJS server to provide a single API endpoint.
Once our server receives the POST request, it will render the data to all connected clients, which will show the data on their tables in realtime.

To Set Up this project in your machine you'll need to take a few steps.
1. Install Android Studio if you haven't already
2. Clone this repo and open in AS
3. Sync the project and import all required dependencies
4. Create a Pusher Account and get your credentials ready for use
5. Set up a simple Node.js server with your pusher credentials to handle your requests as described in the article
6. Update your [package.json](https://gist.github.com/christiannwamba/60729a0b3c3e54558ae1bbc224615a6e) with the neccesary dependencies
7. Run the node server with the  [app.js](https://gist.github.com/christiannwamba/e821e83f5cd4461cdcc831331746d10b) file also linked in the article, do update it with your own credentials
8. Update the java code with your own pusher credentials
7. And finally run the app and give it a spin 


