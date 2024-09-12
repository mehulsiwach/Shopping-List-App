# Shopping List App with Location Tagging

## Overview

This Android application allows users to create and manage a shopping list, and tag locations to each shopping item for easy navigation. The app integrates with the Google Maps API, allowing users to tag a location, and navigate to the corresponding store where the item can be purchased.

## Features

- **Add Shopping Items**: Users can add items to the shopping list along with details such as item name and description.
- **Location Tagging**: Each item in the shopping list can be tagged with a location (e.g., store or market) using Google Maps.
- **Navigation with Google Maps**: After tagging a location, users can use Google Maps to navigate to the location directly from the app.
- **Edit and Delete Items**: Users can edit or delete items from the shopping list.
- **User-friendly UI**: Intuitive user interface designed with Jetpack Compose.

## Tech Stack

- **Kotlin**: The app is built using Kotlin as the primary programming language.
- **Jetpack Compose**: UI is implemented using Jetpack Compose, ensuring a modern, reactive UI experience.
- **Google Maps API**: For location tagging and navigation functionality.
- **Room Database**: Used for local storage of shopping items and their associated locations.
- **MVVM Architecture**: The project follows the Model-View-ViewModel (MVVM) architecture to ensure clean separation of concerns and maintainability.
  
## Prerequisites

1. **Android Studio**: Download and install the latest version of Android Studio.
2. **Google Maps API Key**: You need to obtain a Google Maps API key to enable location tagging and navigation. You can do this by following the [Google Maps API documentation](https://developers.google.com/maps/gmp-get-started).
3. **Internet Connection**: The app requires an active internet connection to interact with Google Maps.

## Installation and Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/shopping-list-app.git
    ```

2. Open the project in Android Studio.

3. Obtain a Google Maps API key by following the [Google Maps API key setup](https://developers.google.com/maps/documentation/android-sdk/get-api-key).

4. Add your Google Maps API key to the `local.properties` file or directly in the `AndroidManifest.xml` file:

    ```xml
    <meta-data
        android:name="com.google.android.geo.API_KEY"
        android:value="YOUR_GOOGLE_MAPS_API_KEY" />
    ```

5. Build and run the project on your emulator or Android device.

## How to Use

1. **Add a Shopping Item**:
    - Click the **Add Item** button.
    - Enter the name of the item and other details.
    - Tag a location by clicking on the **Add Location** button, and selecting the store or market on the map.
  
2. **View and Navigate to Location**:
    - Once an item is added with a location, tap on the item in the list.
    - Use the **Navigate** button to open Google Maps and get directions to the tagged location.

3. **Edit/Delete Items**
