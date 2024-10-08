# WhisperText

# Whisper Text: A Flask App for Exploring Data Collection (Educational Purposes Only)
Whisper Text is a Flask-based application designed for educational purposes to demonstrate how information can be collected from users without their explicit knowledge. This app is not intended for real-world use and serves solely as a learning tool to understand the potential risks and ethical considerations associated with data collection.

# Features:

# Simulates a "NGL"-like experience but this app anonymously fetch their usernames, they think that they are sending messages anonymously but their usernames are getting fetch automatically

Hidden data collection: The app collects usernames and messages without the user's awareness.
Database storage: User data is stored in a SQLite database for demonstration purposes.
Viewable messages: Users can view a list of all submitted messages.
# Important Disclaimers:

This app is strictly for educational purposes. Do not use it in any way that violates privacy or ethical guidelines.
The app does not collect real user information. It simulates data collection for educational purposes only.
The app is not a real-world application. The code and functionality are simplified for educational demonstration.
Learning Objectives:

Understand how data can be collected without user consent.
Explore the ethical concerns surrounding data collection practices.
Learn about the security implications of hidden data collection.
Contributing:

Feel free to contribute to this project to enhance its educational value. You can add new features, improve the UI, or provide more detailed documentation.

Remember, data privacy is crucial. Use this project to learn about the importance of informed consent and responsible data handling.

# Note: Please use this app responsibly and ethically. This is a learning tool, and its use should always be aligned with ethical considerations.

# IMPORTANT:
Flask==2.2.3
Flask-SQLAlchemy==3.0.3
Flask-Cors==3.0.10
datetime==5.0
This requirements.txt file includes the following packages:

Flask (2.2.3): The core Flask web framework.
Flask-SQLAlchemy (3.0.3): An extension that adds support for SQLAlchemy, a Python SQL toolkit and Object-Relational Mapper (ORM), to your Flask application.
Flask-Cors (3.0.10): A Flask extension for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible.
datetime (5.0): The built-in Python module for working with dates and times.
To install these dependencies, you can use the following command in your terminal (make sure your virtual environment is activated):

# YOU HAVE TO CREATE A VIRTUAL ENV FIRST THEN INSTALL THESE DEPENDENCIES THERE.

# YOU CAN OPEN DATABASE TO CHECK WHO MESSAGED YOU BY WRITING SQLITE3 COMMAND ON YOUR TERMINAL WHICH SHOULD BE LIKE THIS

sqlite3 D:\WhisperText\instance\messages.db (you have to write your directory here, in my case my directory was like this)
sqlite3> .excel
sqlite3> select * from message
    ...> ;
   # NOW AFTER THIS COMMAND YOUR DATABASE WILL BE OPENED AS AN MICROSOFT EXCEL FILE

pip install -r requirements.txt
