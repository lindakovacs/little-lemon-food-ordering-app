# Little Lemon Food Ordering App

- The application is a React Native Expo Food app.
- Users will be able of signing up on the Little Lemon restaurant app.
- Users will have to go through a registration process.
- Once they successfully complete that phase, they are redirected to a home screen.
- Home screen will represent the landing screen after completing the onboarding flow, displaying a header, a banner with a search bar and a list of menu items where a user can filter each categories.
- User can also customize their name, email, photo and and other user preferences through a Profile Screen.
- Profile screen also contains four checkboxes enable specific email notifications, like order status, password changes,special offers, and newsletters.
- Use AsyncStorage module to preserve the chosen preferences even when the user quits the application
- When clicking the Logout button, user will redirect back to login page, clearing all data saved from Profile.
- Use SQLite Database to populate, query and filter menu items.


### How to use the project

##### npm install && npm start
##### Then, a QR Code wil appear on your terminal.
##### On IOS Scan QR code through Camera app.
##### On Android: Scan QR code through Expo Go app.

### Built with

- [React Native](https://reactnative.dev/docs/environment-setup) - React Native app built with expo
- [SQLite](https://docs.expo.dev/versions/latest/sdk/sqlite/) - For storing restaurant's menu items.
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/docs/api/) - For storing user preferences.
- [StyleSheet](https://reactnative.dev/docs/stylesheet) - For styles
