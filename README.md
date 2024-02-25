![WhatsApp Image 2024-02-25 at 11 52 00_c8a851a4](https://github.com/Darshan0902/SSD-for-License-plate-detection./assets/77969007/b22a4256-ddba-44ea-a3fe-6910f30d40f9)


Step by step breakdown  :
# License Plate Detection using Flask

This is a Flask web application for detecting license plates in images using OpenCV and EasyOCR.

## Description

The application allows users to upload images containing license plates. Upon upload, the application detects license plates in the images and extracts the text from them using EasyOCR. It then saves the detected information, including the name, phone number, detected license plate text, and timestamp, into a CSV file. Users can view the uploaded images and the corresponding detected information on the web interface.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Darshan0902/license-plate-detection.git
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the pre-trained Cascade Classifier for license plate detection from OpenCV's GitHub repository: [haarcascade_russian_plate_number.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_russian_plate_number.xml). Place this file in the same directory as `app.py`.

## Usage

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open a web browser and navigate to `http://localhost:5000` to access the web interface.

3. Enter the name, phone number, and upload an image containing a license plate.

4. Click on the "Upload" button to detect license plates in the image.

5. The detected information will be displayed on the web interface.

## Credits

- OpenCV: [https://opencv.org/](https://opencv.org/)
- EasyOCR: [https://github.com/JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR)
- Flask: [https://flask.palletsprojects.com/](https://flask.palletsprojects.com/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
