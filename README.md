# DeepFace Emotion Detection

This project implements facial emotion detection using the DeepFace library in a Google Colab environment. It allows users to upload an image and detect the dominant emotion of faces in the image.

## Features

- Face detection in uploaded images
- Emotion recognition using DeepFace
- Visual output with bounding boxes and emotion labels
- Designed for easy use in Google Colab

## Requirements

- Google Colab account
- Python 3.x
- OpenCV
- DeepFace
- Matplotlib

## Installation

No local installation is required. The notebook will install necessary libraries when run in Google Colab.

## Usage

1. Open the provided Jupyter notebook in Google Colab.
2. Run all cells in the notebook.
3. When prompted, upload an image containing one or more faces.
4. The script will process the image and display the result with detected emotions.

## How it works

1. The script installs required libraries (DeepFace and OpenCV).
2. It defines a function `detect_emotion()` that:
   - Analyzes the image using DeepFace
   - Detects faces using OpenCV's Haar Cascade classifier
   - Draws bounding boxes around detected faces
   - Labels each face with the detected emotion
3. The script prompts the user to upload an image.
4. The uploaded image is processed, and the result is displayed using Matplotlib.

## Limitations

- The accuracy of emotion detection depends on the quality and clarity of the input image.
- The script is designed for use in Google Colab and may require modifications for local use.

## Contributing

Contributions to improve the script or extend its functionality are welcome.
Please feel free to fork the repository and submit pull requests.

## License

This project is open-source and available under the MIT License.

## Acknowledgements

- [DeepFace](https://github.com/serengil/deepface) library for facial analysis
- OpenCV for image processing
- Google Colab for providing the runtime environment

## Contact

For any queries or suggestions, please open an issue in the GitHub repository.
