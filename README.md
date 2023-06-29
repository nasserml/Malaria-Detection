# Malaria Detection

This project is a Malaria Detection application built using Flask, a Python web framework. It uses a Convolutional Neural Network (CNN) model trained on a Malaria dataset to classify whether an image contains malaria parasites or not.

## Installation

1. Clone the repository:

   
   git clone [https://github.com/nasserml/Malaria-Detection.git](https://github.com/nasserml/Malaria-Detection.git)
   

2. Navigate to the project directory:

   ```bash
   cd Malaria-Detection
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   flask run
   ```

5. Open your web browser and go to [http://localhost:5000](http://localhost:5000) to access the Malaria Detection application.

## Project Structure

The project repository has the following structure:

- `app.py`: The main Flask application file that defines the routes and handles the image classification.
- `malariadetection.py`: Python script containing the code for image preprocessing and model prediction.
- `templates/`: Directory containing the HTML templates for the web pages.
- `quantized_model.h5`: Pre-trained CNN model in a quantized format for faster inference.
- `Dataset.zip`: Compressed file containing the Malaria dataset used for training and evaluation.
- `README.md`: This file, providing information and instructions for the project.
- `LICENSE`: The license file for the project.
- `Procfile`: A file used by Heroku for application deployment.

## Usage

1. Upload an image to the Malaria Detection application.
2. Click the "Detect" button to perform malaria parasite detection on the uploaded image.
3. The application will process the image using the pre-trained model and display the result.

## License

This project is licensed under the MIT License.
