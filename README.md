# Coffee & WiFi API
This project showcases a fully functional REST API built from scratch using Flask. It provides information about coffee shops and their Wi-Fi services, making it a useful resource for coffee enthusiasts and remote workers looking for the perfect spot to enjoy a cup of coffee while staying connected.

## Table of Contents
- Prerequisites
- Project Structure
- Getting Started
- API Endpoints
- Authentication
- Contributing
- License
- Acknowledgments

## Prerequisites
Before you dive into this project, ensure you have the following prerequisites set up:
1. Python: You'll need Python installed on your system. You can download it from python.org.
2. Pip: Pip is the Python package manager. It should come with your Python installation, but you can update it using python -m pip install --upgrade pip.
3. Virtual Environment (Optional): It's a good practice to create a virtual environment for your project to isolate dependencies. You can create one using python -m venv venv and activate it using the appropriate command for your operating system.
4. Text Editor/IDE: You'll need a text editor or integrated development environment (IDE) for writing code. Popular choices include Visual Studio Code, PyCharm, or Sublime Text.

## Getting Started
1. Clone the repository:
   `git clone https://github.com/tiffanivick/cafe-api.git`
2. Change your working directory:
   `cd cafe-api`
3. Create and activate a virtual environment (optional):
   `python -m venv venv source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
4. Install project dependencies:
   `pip install -r requirements.txt`
5. Run the Flask development server:
   `python app.py`
6. Visit http://localhost:5000 in your web browser to access the API.

## API Endpoints
- GET /coffee-shops: Get a list of coffee shops with Wi-Fi information.
- GET /coffee-shop/<int:id>: Get details of a specific coffee shop by ID.
- POST /coffee-shop: Create a new coffee shop entry (requires authentication).
- PUT /coffee-shop/<int:id>: Update information for a specific coffee shop (requires authentication).
- DELETE /coffee-shop/<int:id>: Delete a coffee shop entry (requires authentication).

## License
This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit/) file for details.

Happy coding, and enjoy building your Coffee & WiFi API with Flask!

