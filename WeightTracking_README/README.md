# Weight Tracking Application

## Project Overview

The Weight Tracking Application is an Android mobile application I originally developed for CS 360: Mobile Architecture and Programming at Southern New Hampshire University. The application allows users to record their weight, monitor changes over time, and track progress toward a personal weight goal.

I developed the application using **Java, Android Studio, and SQLite** for local data storage. For my CS 499 Computer Science Capstone, I enhanced the original application to improve its functionality, input validation, navigation, and overall user experience.

## Application Features

The enhanced application includes:

- **User Accounts:** Users can create an account and log in with a username and password. Additional validation prevents duplicate usernames and enforces stronger password requirements.
- **Weight Tracking:** Users can enter and save weight measurements, which are stored locally using SQLite.
- **Progress Dashboard:** Displays starting weight, current weight, goal weight, total weight change, remaining weight, and percentage of progress toward the goal.
- **Weight History Chart:** A line chart allows users to visualize weight changes over time.
- **Goal Management:** Users can establish and update their target weight.
- **SMS Notifications:** Users can enable or disable SMS notifications and enter a phone number for weight goal notifications.
- **Input Validation:** Weight entries are restricted to a valid range of 50.0 to 1,000.0 pounds, with additional checks for invalid input.
- **Improved Navigation:** Consistent bottom navigation allows users to move between application screens.

## Technologies Used

- Java
- Android Studio
- SQLite
- Android SDK
- XML for user interface layouts

## Original Application and Enhancements

The original application provided the foundation for tracking weight measurements and managing user information.

For my capstone enhancement, I expanded the application's capabilities by introducing a more detailed progress dashboard, visual weight history, improved user account validation, and additional settings for goal management and notifications.

I also improved navigation between activities and added validation to prevent invalid or incomplete data from being entered. These changes made the application more functional and easier to use while allowing me to apply additional software development practices to an existing project.

## How to Access and Run the Application

The repository contains two versions of the application:

- **WeightTrackingApplication_Original.zip:** The original application developed in CS 360.
- **WeightTrackingApplication_Enhanced.zip:** The enhanced application completed for CS 499.

### Requirements

To open and run the application, you will need:

- Android Studio
- Android SDK
- An Android emulator or a compatible physical Android device
- Java support provided through Android Studio

### Setup Instructions

1. Download the ZIP file for the version you want to review.
2. Extract the ZIP file to a folder on your computer.
3. Open Android Studio.
4. Select **Open** from the Android Studio welcome screen, or select **File > Open** if Android
