# Fruit Freshness Detector App 🍎🍌🍇

This is an iOS app designed to classify the freshness of fruits using **Core ML** and **SwiftUI**. The app leverages a machine learning model to determine whether fruits are `Fresh`, `Semi-Fresh`, or `Not Fresh` based on images provided by the user.

---

## Features 🚀

- **Image Classification**: Classify fruit freshness using a trained Core ML model.
- **Camera Integration**: Capture photos directly using the device camera for classification.
- **Photo Library Support**: Select images from the device’s photo library for classification.
- **Result Saving**: Save classification results for future reference.
- **Export Results**: Export saved results as a `.txt` file or share them via available options.
- **User-Friendly Interface**: Built using SwiftUI for a simple and intuitive design.

---

## Screenshots 📸

_Add screenshots of your app here to showcase the functionality (e.g., camera view, classification results, etc.)._

---

## How It Works 🔧

1. The user selects or captures an image of a fruit.
2. The app processes the image using a trained Core ML model (`FruitFreshnessClassifier`).
3. The model predicts the freshness class (`Fresh`, `Semi-Fresh`, `Not Fresh`) and provides a confidence percentage.
4. Results are displayed and can be saved/exported by the user.

---

## Technologies Used 🧪

- **Swift 5**: Programming language for iOS development.
- **SwiftUI**: Framework for creating the user interface.
- **Core ML**: Framework for running machine learning models on-device.
- **Vision**: Framework for image analysis and preprocessing.

---

## Requirements ✅

- **iOS 14.0** or later
- Xcode 13.0 or later
- A physical iOS device for testing the camera feature

---

## Setup Instructions 🔧

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/FruitFreshnessDetector.git
   cd FruitFreshnessDetector
   ```

2. Open the project in Xcode:
   ```bash
   open FreshnessDetector.xcodeproj
   ```

3. Ensure your development team is set up for code signing in **Xcode > Signing & Capabilities**.

4. Build and run the app on a physical iOS device.

---

## File Structure 🗁

```
FreshnessDetector/
├── Assets/                          # Contains app assets (e.g., icons)
├── ContentView.swift                # Main SwiftUI view
├── CoreMLManager.swift              # Core ML integration logic
├── ImagePicker.swift                # Handles image selection and camera functionality
├── FoodFreshnessClassifier.mlmodel  # Trained Core ML model
├── FreshnessDetectorApp.swift       # App entry point
```

---

## How to Train the Model 🎓

1. Use the **Create ML** app to train an **Image Classifier** model.
2. Dataset structure:
   ```
   Dataset/
   ├── Fresh/
   ├── Semi-Fresh/
   └── Not Fresh/
   ```
3. Export the trained model as a `.mlmodel` file and add it to the Xcode project.

---

## Future Enhancements ✨

- Add support for detecting multiple fruits in the same image.
- Implement real-time classification using a live camera feed.
- Add multi-language support for global users.

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact 💬

If you have any questions or feedback, feel free to reach out:

- **Email**: xxthatbbxx@gmail.com
- **GitHub**: [@jigglewiggle101](https://github.com/jigglewiggle101)

