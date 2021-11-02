# firebase-gtk-web-checkpoint1-c4ptke

<!-- [Edit on StackBlitz ⚡️](https://stackblitz.com/edit/firebase-gtk-web-checkpoint1-c4ptke) -->

[Demo App](https://firebase-gtk-web-checkpoint1-c4ptke.stackblitz.io/)

Firebase provides detailed documentation and cross-platform SDKs to help you build and ship apps on Android, iOS, the web, C++, and Unity.

## You've used Firebase to build an interactive, real-time web application!

### What we've covered
- Firebase Authentication
- FirebaseUI
- Cloud Firestore
- Firebase Security Rules

Email Sign-in was enabled for Firebase Authentication

Since the web app uses [Cloud Firestore](https://firebase.google.com/docs/firestore/) to save chat messages and recieve new chat messages.  Cloud Firestore was also enabled in test mode.

Cloud Firestore is a NoSQL database, and data stored in the database is split into collections, documents, fields, and subcollections. Each message is stored in the chat as a document in a top-level collection called guestbook. Security rules were added so only those signed in are able to see the messages.