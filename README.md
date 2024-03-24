# twitter : a social media app

## Components and Package Dependencies:
- 1.Firebase:
Firebase provides a backend infrastructure, authentication, and real-time database services. It's used for handling user authentication, storing data, and managing real-time updates.

- 2.Firestore:
Firestore is a flexible, scalable database for mobile, web, and server development from Firebase and Google Cloud Platform. It's used for storing structured data in the form of documents within collections, allowing efficient querying and real-time updates.

- 3.KingFisher:
KingFisher is a powerful, pure-Swift library for downloading and caching images from the web. It simplifies the process of loading images asynchronously and efficiently managing image caching.

## Concept:
- Utils: The Utils component typically includes utility functions and helpers that are commonly used across the application. These can include functions for date formatting, image manipulation, string operations, etc.

- Authentication: This component handles user authentication-related functionalities such as sign-in, sign-up, password reset, and user session management. It interacts with Firebase Authentication to authenticate users securely.

- UploadTweet: UploadTweet manages the functionality related to composing and uploading tweets. It includes the user interface for composing tweets and the logic for uploading them to Firestore, along with any associated media like images or videos.

- SideMenu: The SideMenu component is responsible for displaying and managing the side menu/navigation drawer in the application. It typically contains options for navigation, settings, user profile, etc.

- Profile: Profile deals with displaying user profiles, including information such as username, bio, followers, following, and user-generated content like tweets or posts.

- Explore: Explore facilitates the discovery users to follow

- Notification: Notification manages the notifications functionality, including displaying notifications for various events such as mentions, likes, retweets, and new followers.

- Messages: Messages handles the messaging or direct messaging feature of the app, allowing users to send private messages to each other.

- Components: Components typically consist of reusable UI elements or custom SwiftUI components that are used across multiple views within the app. These can include buttons, cards, input fields, etc.

- MainTab: The MainTab component represents the main navigation interface of the app, typically implemented as a tab bar. It allows users to navigate between different sections of the app, such as home, explore, notifications, messages, etc.

- Model: The Model component consists of data models that represent the structure of data used within the application. These models define the properties and relationships of various entities like users, tweets, notifications, etc.

- Service: The Service component encapsulates networking-related functionalities such as making API requests, handling responses, and other backend interactions. It abstracts away the networking implementation details from the rest of the application, promoting modularity and maintainability.

## Animation :
- for the circle animation I haven't used any type of extensions , just I have given the limit of frames and its motion and made isAnimating boolean as true so that it always animates to-fro
- I may use the Rive or spline animation but for that I need to import extra package dependencies but it may cause unnecessery bigger size of the app, so I made it simpler.

## to know all about the work flow , just take a look on the video :


