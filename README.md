# Tippy

# Overview
Tippy is a tip calculator app built in Android Studio using Kotlin. This app allows the user to enter a bill amount, adjust the tip percentage with a slider, 
and instantly see the tip amount and total amount update in real time. The app also shows a text description of the tip quality based on the selected percentage.

## Features
### Baseline Features
- Enter a bill amount
- Adjust tip percentage with a seek bar
- View tip amount in real time
- View total amount in real time
- View a tip description that chages based on the tip percentage
- Handles empty input without crashing

### Enhancements
-  **Reset Button:**
  Added a reset button so the user can quickly clear the calculator and return to default settings

- **Round Total Up Option:**
  Added a checkbox that allows the user to round the final total up to the next whole dollar.

### Setup / Run Steps
  1. Clone or download this repository.
  2. Open the project in Android Studio.
  3. Let Gradle sync completely.
  4. Run the app on an emulator or Android device.
  5. Enter a bill amount and adjust the tip percentage to test the app features.

## Screenshots

### Home Screen
<img width="388" height="796" alt="image" src="https://github.com/user-attachments/assets/fe149f83-467e-436f-9adb-67811671ce37" />

### Example Calculation
<img width="378" height="783" alt="image" src="https://github.com/user-attachments/assets/41e3b54f-2897-4364-a685-dd7fc720c86d" />

### Round Total Up Feature
<img width="370" height="792" alt="image" src="https://github.com/user-attachments/assets/2194063d-aea6-4461-8a40-bcf6c9b65d55" />

### Reset Button
<img width="393" height="802" alt="image" src="https://github.com/user-attachments/assets/989d2b76-97fd-4ef6-bd80-aa9ab3a0fbbc" />

## Demo Video
https://github.com/user-attachments/assets/15884933-2c28-4ce5-83c4-8c5c28d485cb

## Architecture / Trade-offs

### This app was built using:
- **Kotlin** for the app logic
- **XML** for the user interface
- **TextWatcher** to update values when the bill amount changes
- **SeekBar listener** to update values when the tip percentage changes
- **Button and CheckBox listeners** for the reset and round-up enchancements

### Trade-Offs
- I kept the app in a single activity to keep the project simple and easier to follow. This works well for a small app but for a larger app I would separate the logic more clearly from the UI
- Some values and UR behavior could be further moved into resources to make the app cleaner and easier to maintain.
## Reflection
- If I were to keep improving this project, I would separate the calculation logic from the activity to make the code easier to read, test and update. I would also improve the UI syling more and possibly add a bill spliting feature.  
