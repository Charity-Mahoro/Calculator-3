This Flutter project demonstrates the implementation of several key features including Broadcast Receivers, Shared Preferences for theme management,
and Authentication APIs for user sign-up and sign-in functionalities. The project covers the following requirements:
Broadcast Receivers:

Detects Internet connectivity changes and displays a toast message.
Monitors battery charging status and displays a toast message when the battery reaches a specified threshold (e.g., 90%).
Shared Preferences:

Implements Light and Dark mode switching using shared preferences to persist the user's theme choice.
Authentication API:

Implements sign-up and sign-in functionalities using email and password authentication via Firebase.
Integrates social media authentication (e.g., Google).
Manages user authentication state and profile information.
Implementation Details
1. Broadcast Receivers
Internet Connectivity Detection: Utilizes connectivity_plus to monitor network changes and displays a toast message using fluttertoast.
Battery Status Monitoring: Custom BroadcastReceiver listens for battery status changes and shows a toast message when the battery level reaches 90%.
2. Shared Preferences
Theme Management: Uses shared_preferences to store and retrieve user's theme preference, providing a toggle button to switch between Light and Dark modes.
3. Authentication API
Email and Password Authentication: Implements sign-up and sign-in using Firebase Authentication with form validation.
Social Media Authentication: Integrates Google sign-in via Firebase.
User Management: Manages authentication state and provides user profile information.
