# Image-Colorization

# Image Colorization with Flask

This project uses a deep learning model to colorize black and white images. Built with Flask, the application allows users to upload black-and-white images, which are then processed and colorized using a pre-trained colorization model. The colorized images are displayed alongside the original image on the same page.

## Features
- Upload a black and white image
- Colorize the uploaded image using a pre-trained deep learning model
- Display the original and colorized images side by side
- Simple and responsive web interface

## Technologies Used
- **Python**: Backend logic
- **Flask**: Web framework
- **OpenCV**: Image processing and colorization
- **HTML/CSS**: Frontend design
- **Bootstrap (Optional)**: For better UI styling (if used in your project)

## Setup Instructions

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Steps to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dsatish1252/image-colorization.git
   cd image-colorization
Install dependencies: Create a virtual environment (optional but recommended) and install the required libraries.

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
The requirements.txt file should include the necessary packages, for example:

makefile
Copy code
Flask==2.1.0
numpy==1.21.0
opencv-python==4.5.3.56
Download the pre-trained model: You will need the following model files for the colorization process:

colorization_deploy_v2.prototxt
pts_in_hull.npy
colorization_release_v2.caffemodel
Place them in the model/ directory of your project. You can find these files here.

Run the application: After setting up everything, you can start the Flask server by running:

bash
Copy code
python app.py
Open your browser and go to http://127.0.0.1:5000 to access the app.

Usage
On the homepage, click the Choose File button to upload a black-and-white image.
Click the Colorize button to process the image.
The original and colorized images will be displayed side by side.
Contributing
If you'd like to contribute to the project, feel free to fork the repository and submit a pull request. Here are some ways you can contribute:

Improve the user interface with CSS or JavaScript
Optimize the image colorization process
Add more functionality or features
License
This project is open-source and available under the MIT License.

Acknowledgments
Thanks to the authors of the colorization model: richzhang/colorization
The OpenCV library was essential for image processing and model inference.
Flask was used to build the web framework for this application.
Feel free to reach out if you have any issues or questions! Happy coding! 🚀

vbnet
Copy code

### Notes:
- The `requirements.txt` mentioned above should contain the necessary dependencies, like Flask, OpenCV, and numpy. You can generate it by running `pip freeze > requirements.txt`.
- Make sure to replace the model download link if you have a different source for the model files.

This README file should help users understand how to set up and use your project. Let me know if you need any modifications!





