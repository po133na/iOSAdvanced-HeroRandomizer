# Superhero App

## Overview
This is a simple iOS app built with UIKit that lets users generate random superheroes and view their details. Users can also add their favorite heroes to a list.

## Features
- Generate a random superhero
- View superhero details (name, abilities, biography, appearance)
- Add heroes to favorites
- Dark mode support

## Implementation Details
- **UIKit**: Used for UI components.
- **Networking**: Fetches superhero data from an API.
- **Core Data**: Stores favorite heroes locally.
- **MVVM Architecture**: Keeps the code clean and structured.

## Challenges & Solutions
1. **Overlapping UI Elements**: Adjusted layout constraints to prevent buttons from covering hero details.
2. **API Response Time**: Implemented loading indicators for a better user experience.
3. **Data Persistence**: Used Core Data to ensure favorite heroes are saved even after app restarts.

## How to Run
1. Open the project in Xcode.
2. Select an iOS simulator or device.
3. Run the app (Cmd + R) and start generating heroes!

## Future Improvements
- Improve UI animations.
- Add search functionality for specific heroes.
- Implement more filtering options for favorite heroes.

Enjoy using the Superhero App! 

