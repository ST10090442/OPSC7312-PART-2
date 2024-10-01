Balance Buddy

Overview
Balance Buddy is a productivity and wellness app designed to help users set goals, track habits, add notes, use timers, manage settings, and sign in securely with Google Single Sign-On (SSO).

How to create
You will need enough knowledge regarding android studio and how to build certain apps with certain features
You will need to learn Kotlin

Features
- Google SSO for easy and secure login.
- Add Habits: Track your daily habits.
- Add Notes: Capture and categorize notes.
- Timer: Use a timer for tasks or meditation.
- Settings: Customize user settings.
- Logout: Securely sign out.

Prerequisites
- Android Studio installed.
- An Android device or emulator.

2. Open in Android Studio:
    - Open Android Studio.
    - Build app and run.

3. **Configure Firebase**:
    - Set up Firebase Authentication.

4. **Dependencies**:
    Ensure the following dependencies are included in `build.gradle`:
    ```gradle
    implementation 'com.google.firebase:firebase-auth'
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
    ```

5. **Sync and Compile**:
    - Sync the Gradle files by clicking "Sync Now" in Android Studio.
    - Select a device (emulator or connected Android device) and click the **Run** button.

How to Use
1. Sign in with Google: 
   - On app launch, sign in using Google SSO.
   
2. Dashboard:
   - Navigate to the dashboard.

3. Add a Habit:
   - Go to the Habits section, add a new habit, set goals, and track your progress.

4. Add a Note:
   - Open the Notes section, type in your thoughts or tasks, and categorize them.

5. Timer:
   - Access the timer in the Tools section, and use it for tasks like Pomodoro or meditation.

6. Settings:
   - Modify user preferences 

7. Logout:
   - Use the Logout option to securely exit the app.

An API has been created for this app using node.js and express and VS Code to edit the API
The API was deployed on Vercel
The API was suppose to be integrated in the android studio app however there were some complications with the URL and servers