Flask File Upload Example

This is a simple Flask application that demonstrates how to implement file upload functionality using Flask and Flask-WTF. Users can upload files, and the uploaded files are saved in a designated folder on the server.

Prerequisites

Before running the application, ensure you have the following dependencies installed:

Python (version 3.6 or higher)
Flask
Flask-WTF
You can install the required dependencies by running the following command:

Copy code
pip install Flask Flask-WTF
Getting Started

Clone the repository or download the source code.
Open a terminal and navigate to the project directory.
Set up a virtual environment (optional but recommended):
bash
Copy code
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
Run the Flask application:
bash
Copy code
python app.py
Open a web browser and access the application at http://localhost:5000.
Usage

The home page displays a form with a file input field and an "Upload File" button.
Select a file using the file input field and click the "Upload File" button.
The uploaded file will be saved in the static/files folder.
Upon successful upload, a confirmation message will be displayed.
Customization

You can customize the application according to your requirements:

Upload Folder: By default, uploaded files are saved in the static/files folder. You can change the folder by modifying the UPLOAD_FOLDER configuration variable in the app.py file.
Form Validation: The example code includes an InputRequired validator for the file input field. You can add or modify the validators in the UploadFileForm class in the app.py file.
Styling and Templates: The provided example uses a basic HTML template (index.html). You can modify the template or create additional templates to suit your application's design requirements.
