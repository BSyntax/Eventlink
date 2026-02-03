# EventLink

EventLink is a mobile app designed to keep rural and small-town communities connected and informed by providing real-time access to local events, news, and announcements all in one place! Created with the aim of bridging communication gaps in communities like Mthatha, EventLink empowers residents to stay in the loop and engage more fully with their community.

---

## Screenshots

|                                               Onboarding                                                |                                                  Login                                                  |                                                Home Feed                                                |
| :-----------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/user-attachments/assets/99d0994d-4b4f-4a62-9b16-cf62ae5975dc" width="200"> | <img src="https://github.com/user-attachments/assets/3d89c8d7-3a1f-4299-8baf-b8c1654740a6" width="200"> | <img src="https://github.com/user-attachments/assets/d70fc4b2-7aff-47fb-8ea3-20fcbedc587e" width="200"> |

|                                              Event Details                                              |                                              Create Event                                               |                                              User Profile                                               |
| :-----------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/user-attachments/assets/bae58bf6-9abb-42cb-a3a7-2239a2b7e35a" width="200"> | <img src="https://github.com/user-attachments/assets/17b51d08-0e62-4873-a3e2-47f099d22eef" width="200"> | <img src="https://github.com/user-attachments/assets/b5deee56-c629-47fb-9da9-b223d647592a" width="200"> |

---

## Key Features

- **Browse Local Events & News**: Get quick access to all local events and important community announcements.
- **Post and Share Events**: Easily publish events for community activities and keep others informed.
- **Stay Notified**: Users receive real-time notifications for newly posted events and news via Firebase Cloud Messaging.
- **Community-Centric**: Encourages participation by allowing users to submit their own events.
- **Search & Filter**: Find specific events by title or category.

---

## Tech Stack

- **Framework**: [Flutter](https://flutter.dev/) (SDK ^3.5.1) - Cross-platform development for Android & iOS.
- **Backend**: [Firebase](https://firebase.google.com/)
  - **Authentication**: Secure email/password login and user management.
  - **Cloud Firestore**: NoSQL database for storing events and user profiles.
  - **Cloud Messaging (FCM)**: Push notifications for real-time updates.
- **State Management**: [Provider](https://pub.dev/packages/provider) - For efficient state management across the app.
- **Architecture**: MVC (Model-View-Controller) pattern.

---

## Getting Started

### Prerequisites

- Flutter SDK installed
- A Firebase project set up

### Installation

1.  **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/EventLink.git
    cd EventLink
    ```

2.  **Install dependencies**

    ```bash
    flutter pub get
    ```

3.  **⚠️ IMPORTANT: Add Firebase Configuration**
    This project relies on Firebase, but the configuration files are not included in the repository for security reasons. You must add them manually:
    - **Android**: Download `google-services.json` from your Firebase Console and place it in `android/app/`.
    - **iOS**: Download `GoogleService-Info.plist` from your Firebase Console and place it in `ios/Runner/`.

    > **Note**: Without these files, the app will fail to build on Android and crash on iOS.

4.  **Run the app**
    ```bash
    flutter run
    ```

---

## Key Learning

This project was a fantastic opportunity to apply the **MVC (Model-View-Controller)** architecture, separating the logic from the UI to keep the codebase clean and manageable. The MVC pattern made it easy to maintain and extend the app's functionality, ensuring it remains adaptable as the project grows.

---

## Future Enhancements

- **Enhanced Filters**: Add more filters to refine event search results.
- **User Roles & Moderation**: Implement roles for users to help moderate posts.
- **Community Insights**: Show community engagement trends based on likes or participation.

---

## Resources

This app was inspired and shaped by invaluable resources:

- **Mitch Koko (YouTube Channel)** - Practical Flutter development tutorials.
- **Beginning Flutter: A Hands-On Guide to App Development** by Marco L. Napoli.
