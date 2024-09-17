# DailyMoods

**DailyMoods** is a simple and modern iOS app built with SwiftUI that helps users track their daily moods, follow their friends, and receive motivational quotes. The app uses the MVVM architecture to ensure a clean and maintainable codebase.

## Features

- **Welcome Screen**: A simple introduction to the app with a "Start Tracking" button.
- **Mood Tracking**: Users can select their current mood from a variety of emojis and log it.
- **Mood History**: A calendar view and graph view show the user's mood trends over time.
- **Mood Feed**: Users can follow others and view mood updates from people they follow.
- **Motivational Quotes**: A daily dose of inspiration tailored to the user's current mood.
- **User Preferences**: Manage notification settings, theme options, and more.

## Architecture

The app follows the **MVVM (Model-View-ViewModel)** architecture pattern:

- **Model**: Defines the data structure (e.g., `User`, `Mood`, `Quote`, `Post`).
- **View**: Represents the UI components (e.g., `WelcomeView`, `MoodTrackingView`, `MoodFeedView`).
- **ViewModel**: Manages the app's business logic and data manipulation (e.g., `MoodTrackingViewModel`, `MoodFeedViewModel`).
- **Service/Repository**: Handles data operations, including network requests and local storage (e.g., `MoodRepository`, `QuoteService`).

## Storage

The app uses a combination of local and remote storage solutions:

- **Core Data**: For managing complex, structured data like mood entries and mood posts.
- **UserDefaults**: For storing simple user preferences and settings.
- **Firebase Firestore** (optional): For real-time data synchronization and cloud-based storage.

## Requirements

- iOS 15.0+
- Xcode 14+
- Swift 5.5+

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DailyMoods.git
   cd DailyMoods

2.	Open the Xcode project:
    ```bash
  	open DailyMoods.xcodeproj

3.	Install dependencies (if using any package managers like CocoaPods or Swift Package Manager):
    ```bash
    pod install  # CocoaPods example

4.	Build and run the app on a simulator or a connected device.

Usage

	•	Start Tracking: Open the app and click on “Start Tracking” to begin logging your moods.
	•	Track Mood: Choose an emoji that best represents your current mood and click “Log Mood.”
	•	View History: Navigate to the Mood History screen to see your mood trends.
	•	Interact with Feed: Follow users and interact with their mood posts through likes and comments.
	•	Get Inspired: Head to the Motivational Quote section for your daily dose of inspiration.

Screenshots

To Be done

Contributing

	1.	Fork the repository.
	2.	Create a new branch (git checkout -b feature/your-feature-name).
	3.	Commit your changes (git commit -m 'Add a new feature').
	4.	Push to the branch (git push origin feature/your-feature-name).
	5.	Open a pull request.

Contact

For questions or suggestions, please contact me at taifmaldehbash@gmail.com.
