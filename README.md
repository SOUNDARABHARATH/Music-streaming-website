

# Music Streaming Web Application

## Features
- **User Authentication**: Secure login and registration using Firebase Authentication.
- **Song Metadata and Streaming**: Stream music files and display metadata such as artist, album, and song title.
- **Playlists**: Create and manage personalized playlists.
- **Real-Time Updates**: Receive real-time updates for new songs, playlists, and user activities.
- **Audio File Storage**: Store audio files securely using Firebase Storage.
- **Responsive Interface**: User-friendly and mobile-responsive design for a seamless experience across devices.
- **Song Browsing and Search**: Efficient search and browse features to discover music.
- **Music Playback**: Full-featured music player with play, pause, skip, and volume control.

## Technologies Used
1. **Node.js**: Backend runtime environment for building server-side applications.
2. **Express.js**: Web framework for Node.js to manage API routes and server logic.
3. **Firebase Authentication**: Secure user authentication for login and registration.
4. **MongoDB**: Database for storing user data, playlists, and song metadata.
5. **Firebase Storage**: Store and manage audio files for streaming.
6. **React.js**: Frontend library for building user interfaces and components.

## Firebase Setup

### 1. Create Firebase Account and Project
1. Go to [Firebase Console](https://console.firebase.google.com/).
2. Log in with your Google account or create a new one if needed.
3. Click **Add Project** and follow the steps to create a new Firebase project.
4. Enable Firebase Authentication:
    - Navigate to the **Authentication** section from the left-hand menu.
    - Click **Get Started**, then choose **Email/Password** and enable it.
5. Enable Firebase Storage:
    - Navigate to the **Storage** section and click **Get Started** to set up Firebase Storage for your app.

### 2. Download Firebase JSON File for Authentication
1. In your Firebase project, go to **Project Settings** by clicking on the gear icon at the top left of the Firebase Console.
2. Scroll down to the **Your Apps** section and click on the **</>** (Web) icon to register your web app.
3. After registering the app, you’ll be presented with Firebase SDK credentials.
4. Download the `google-services.json` file:
    - Under the **Firebase SDK Snippet**, click **Download the config file**.
    - Save this file in the root of your project directory.


## Build Instructions

### 1. Server Setup
1. Navigate to the `src/` directory using your terminal.
2. Install the necessary dependencies:
    ```bash
    npm install
    ```
3. Start the server:
    ```bash
    npm start
    ```

### 2. Client Setup
1. Open another terminal window.
2. Navigate to the client directory.
3. Install the necessary dependencies:
    ```bash
    npm install
    ```
4. Start the client:
    ```bash
    npm start
    ```

### 3. Testing the Application
- You can test the application locally or deploy it to a live server for online testing.

---

This README now includes the steps for setting up Firebase, enabling authentication, and integrating the JSON file for authentication into your project.
