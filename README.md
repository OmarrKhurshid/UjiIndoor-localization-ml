# indoor-localization-ml
Predict indoor localization accurately using machine learning models trained on Wi-Fi fingerprinting data. Explore and evaluate different methodologies for automatic user localization in indoor environments, overcoming the challenges posed by the absence of reliable GPS signals.

# Indoor Localization Machine Learning

This repository contains Python code for building and evaluating machine learning models to predict indoor localization based on Wi-Fi fingerprinting. The project aims to address the challenge of automatic user localization in indoor environments where GPS signals are not reliable, using WLAN fingerprint-based methods.

## Dataset Overview

The UJIIndoorLoc database is a comprehensive dataset created to facilitate research in indoor localization methodologies. It covers three buildings of Universitat Jaume I and includes more than 110,000 square meters of space. The dataset consists of Wi-Fi fingerprint data collected using over 25 Android devices by more than 20 different users.

### Data Set Information:

- **Localization Methodology:** WLAN fingerprint-based indoor positioning
- **Attributes:** 
  - Wi-Fi fingerprints (520 attributes)
  - Latitude, Longitude, Floor, Building ID (to be predicted)
  - Space ID, Relative Position, User ID, Phone ID, Timestamp
- **Attribute Details:** 
  - Intensity values for detected Wireless Access Points (WAPs) ranging from -104dBm to 0dBm, with 100 used to denote undetected WAPs
  - Latitude and Longitude as real values
  - Floor as integer values
  - Building ID as categorical integer values
  - Space ID, Relative Position, User ID, and Phone ID as categorical integer values
  - Timestamp in UNIX Time format

### Purpose:

The dataset can be utilized for classification tasks such as building and floor identification, or regression tasks such as longitude and latitude estimation. It serves as a valuable resource for evaluating and comparing different indoor localization methodologies based on Wi-Fi fingerprinting.

## Installation

To run this project, ensure you have Python installed on your machine. Install the required libraries using the following command:

pip install -r requirements.txt


## Usage

1. Clone this repository to your local machine.
2. Install the required libraries using the provided requirements.txt file.
3. Explore the dataset and preprocess the data as needed.
4. Train machine learning models to predict indoor localization based on Wi-Fi fingerprinting.
5. Evaluate model performance using appropriate metrics.
6. Visualize results and insights obtained from the analysis.

## Contributors

- Omar Khurshid

Contributions to this project are welcome! If you encounter any issues, have suggestions for improvements, or wish to contribute new features/models, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
