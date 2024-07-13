Multilingual Translation Application
Overview
This project is a client-server application that allows users to translate text from any language to English. The client side features a graphical user interface (GUI) developed using Tkinter, while the server handles translation requests using the Google Translate API.

Features
User-Friendly GUI: Input text, select the input language, and specify the server IP address.
Language Selection: Dropdown menu to select from the list of languages supported by Google Translate.
Real-Time Translation: Sends text to the server for translation and receives the translated text instantly.
Concurrent Connections: Server handles multiple client connections concurrently using multi-threading.
Data Logging: Server logs translation requests for record-keeping.
Technologies Used
Python: Core programming language.
Tkinter: For creating the client-side GUI.
Socket Programming: For TCP communication between client and server.
Google Translate API: For translation services.
Threading: To handle multiple client connections simultaneously on the server.
