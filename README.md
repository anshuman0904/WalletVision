# WalletVision

WalletVision is an Android application designed to assist visually impaired individuals in identifying Indian currency notes. The app leverages deep learning and computer vision to provide real-time currency detection using the device's camera.

## Features

- **Real-Time Currency Detection**: Uses the device's camera to detect and identify Indian currency notes.
- **High Accuracy**: A deep learning model trained on 1,000 images achieves an accuracy of **99.59%**.
- **Optimized for Mobile**: The model is converted and optimized using TensorFlow Lite (TFLite) for efficient on-device inference.
- **User-Friendly Interface**: Built with Flutter for a seamless and intuitive user experience.

## Technologies Used

- **Frontend**: Dart (Flutter)
- **Backend**: TensorFlow/Keras, Pandas, NumPy
- **Model Optimization**: TensorFlow Lite (TFLite)

## How It Works

1. **Model Training**: A Convolutional Neural Network (CNN) is trained on a dataset of 1,000 images of Indian currency notes.
2. **Model Conversion**: The trained model is converted and optimized using TFLite for efficient on-device inference.
3. **Integration**: The optimized model is integrated into a Flutter application for real-time currency detection.
4. **Real-Time Detection**: Users can point their device's camera at a currency note, and the app will identify the note in real-time.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/anshuman0904/WalletVision.git
   cd WalletVision
   ```

2. **Install Dependencies**:

   Ensure you have Flutter installed. Then, run:
  ```bash
  flutter pub get
  ```

3. **Run the App**:

  Connect an Android device or emulator and run:
  ```bash
  flutter run
  ```

## Model Training Details

- **Dataset**: 1,000 images of Indian currency notes.
- **Model**: Convolutional Neural Network (CNN).
- **Accuracy**: 99.59% on the validation set.
- **Optimization**: Converted to TFLite for mobile deployment.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

## Acknowledgments

- Thanks to the TensorFlow and Flutter communities for their excellent tools and resources.
- Special thanks to [Satyam](https://github.com/satyam-sm/) who made this project possible.

## Contact

For any questions or feedback, feel free to reach out:

- GitHub: [anshuman0904](https://github.com/anshuman0904)
- Email: anshuman@engineer.com

*Note: This project is a proof of concept and may require further optimization for production use.*


