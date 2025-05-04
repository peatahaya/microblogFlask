Flask Mega Tutorial

This repository contains the code for a microblog application built as part of the Flask Mega Tutorial by Miguel Grinberg. The tutorial guides you through creating a fully-featured web application using the Flask framework. This project is based on the concepts introduced in Part 1, 2, 3 and 4.

Features





Basic Flask application setup.



Simple "Hello, World!" route.



Modular project structure for scalability.



Introduction to Flask's core concepts like routing and templates.

Technologies Used





Flask: Lightweight Python web framework.



Python: Core programming language.



Jinja2: Templating engine for rendering HTML.



Werkzeug: WSGI utility library for Flask.

Installation





Clone the repository:

git clone https://github.com/yourusername/flask-mega-tutorial.git
cd flask-mega-tutorial



Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate



Install dependencies:

pip install -r requirements.txt



Set the Flask environment variables:

export FLASK_APP=microblog.py  # On Windows: set FLASK_APP=microblog.py



Run the application:

flask run



Open your browser and navigate to http://127.0.0.1:5000 to see the "Hello, World!" page.

Usage





The initial application displays a simple "Hello, World!" message.



Follow the Flask Mega Tutorial to extend the application with additional features like user authentication, database integration, and more.

Project Structure

flask-mega-tutorial/
├── app/
│   ├── __init__.py         # Application factory
│   ├── routes.py           # Route definitions
│   └── templates/          # HTML templates (added in later parts)
├── microblog.py            # Main application entry point
├── requirements.txt        # Project dependencies
└── README.md               # This file

Contributing

Contributions are welcome! To contribute:





Fork the repository.



Create a new branch (git checkout -b feature-branch).



Make your changes and commit (git commit -m "Add feature").



Push to the branch (git push origin feature-branch).



Open a Pull Request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments





This project is based on the Flask Mega Tutorial by Miguel Grinberg.



Special thanks to the Flask community for their excellent documentation and support.

Contact

For questions or feedback, open an issue or contact the maintainer at [your.email@example.com].
