
# Spotify Clone

This project is a Spotify clone built using Firebase for authentication and integrates with the Spotify API. It allows users to log in, interact with their Spotify account, and enjoy a seamless experience.


## Author

- **GitHub Repository:** [whenslynady/firebase-spotify](https://github.com/whenslynady/firebase-spotify.git)
- **YouTube Channel:** [Firebase Spotify Tutorial](https://www.youtube.com/watch?v=4TFbXepOjLI)

## How to Run the Project

To run this project, follow these steps:

Install Node.js using [nvm-windows](https://github.com/coreybutler/nvm-windows). Then, install the Firebase CLI via npm by running:
```bash
npm install -g firebase-tools  
firebase --version  
```  

Log in to Firebase with your Google account by running:
```bash
firebase login  
firebase logout  
```  

Verify the Firebase CLI installation and list your Firebase projects by running:
```bash
firebase projects:list  
```  

Go to the [Firebase Console](https://console.firebase.google.com/), select your project, and add Flutter under "Get Started." From any directory, activate the FlutterFire CLI by running:
```bash
dart pub global activate flutterfire_cli  
```  

In your Flutter project directory, configure FlutterFire by running:
```bash
flutterfire configure --project=andy-87a84  
```  

This will automatically register platform-specific apps with Firebase and add the `lib/firebase_options.dart` file to your project.

Next, clone this repository:
```bash
git clone https://github.com/whenslynady/firebase-spotify.git  
cd firebase-spotify  
```  

Install the project dependencies using:
```bash
npm install  
```  

Finally, start the application by running:
```bash
flutter run -d chrome  
```  

Once the server is running, open your browser and navigate to `http://localhost:3000`.  
Enjoy using Firebase Spotify!
```  


