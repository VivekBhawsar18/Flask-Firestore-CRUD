Sure, here's an updated version of the README file:

# Flask CRUD API

This repository contains a Flask application that provides a CRUD (Create, Read, Update, Delete) API for interacting with Google Firestore, a NoSQL document database.

## Features

- Allows users to add, retrieve, update, and delete documents in the Firestore database.
- Provides RESTful endpoints for each CRUD operation.
- Utilizes Flask, a lightweight web framework, for building the API.
- Demonstrates how to integrate Firebase Admin SDK for Python to interact with Firestore.

## Usage

### Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.x
- Flask
- Firebase Admin SDK for Python
- Google Cloud Platform account with Firestore enabled

### Installation

1. Clone the repository:

```bash
git clone https://github.com/VivekBhawsar18/Flask-crud-api.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set up Firebase:

   - Create a project on Google Cloud Platform.
   - Enable Firestore in the Firebase console.
   - Generate a service account key and download the JSON file (`Key.json`).
   - Place the `Key.json` file in the root directory of the project.

### Running the Application

1. Start the Flask server:

```bash
python app.py
```

2. Access the API endpoints:

   - To add a document: `POST /add`
   - To retrieve a document: `GET /list?id=<document_id>`
   - To update a document: `POST /update` or `PUT /update`
   - To delete a document: `GET /delete?id=<document_id>`

## Deployment

You can deploy this Flask application on various platforms, including:

- Google Cloud Run
- Heroku
- AWS Elastic Beanstalk

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any suggestions, bug reports, or enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

[![Run on Google Cloud](https://storage.googleapis.com/cloudrun/button.svg)](https://console.cloud.google.com/cloudshell/editor?shellonly=true&cloudshell_image=gcr.io/cloudrun/button&cloudshell_git_repo=https://github.com/VivekBhawsar18/Flask-crud-api.git)

---

Feel free to adjust the content as needed and let me know if you need further assistance!
