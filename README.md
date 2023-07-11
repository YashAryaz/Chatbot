# Chatbot
This is a chatbot application that can engage in conversations with users. The chatbot is designed to understand user input and provide appropriate responses based on predefined intents. It utilizes a deep learning model and natural language processing techniques. It is hosted on Replit and can be accessed at https://chatbot.yasharya5.repl.co/.

# Files
The project consists of the following files:

- templates folder: Contains the HTML template file for the chatbot user interface.
- chatbot_model.h5: The trained deep learning model file used for predicting intents.
- classes.pkl: A pickled file containing the classes of intents.
- intents.json: A JSON file that defines the intents and their associated patterns and responses.
- main.py: The main Python file that implements the chatbot functionality.
- words.pkl: A pickled file containing the tokenized words used in training the model.
# Technologies Used
- The chatbot application is built using the following technologies and libraries:

- Flask: A Python web framework used for creating the chatbot web application.
- Keras: A deep learning framework used for training and loading the chatbot model.
- nltk: A natural language processing library used for text preprocessing and tokenization.
- numpy: A library used for numerical operations in Python.
- wikipedia: A library used for searching and retrieving information from Wikipedia.
# Usage
Ensure that you have all the necessary files in the project directory, including the trained model, intents file, and other dependencies.

Run the main.py file to start the Flask web application.

shell
Copy code
python main.py
Access the chatbot user interface by visiting http://localhost:5000 in your web browser.

Start interacting with the chatbot by entering text messages in the input field.

The chatbot will analyze your input and provide appropriate responses based on the predefined intents. It will use the trained model to predict the intent of your message and generate a relevant response.

If you enter a message containing the word "search," the chatbot will attempt to search for the topic on Wikipedia and provide a summary. If there are multiple search results, the chatbot will prompt you to choose from the available options.

# Customization
You can customize the chatbot's behavior by modifying the intents.json file. This file defines the intents, patterns, and corresponding responses. You can add new intents, update existing ones, and adjust the patterns and responses to suit your requirements.

# Additional Notes
The chatbot leverages the power of deep learning and natural language processing techniques to understand and respond to user input. It uses a bag-of-words approach to represent text as numerical vectors and a neural network model to classify intents.

The chatbot also integrates with Wikipedia to provide additional information on topics of interest. If the user's message includes the word "search," the chatbot will attempt to retrieve a summary from Wikipedia.

The web application is built using the Flask framework, allowing for easy deployment and interaction with the chatbot through a user-friendly interface.

Please note that the chatbot's responses are based on the predefined intents and may not cover all possible user queries. The chatbot's accuracy and effectiveness can be improved by further training the model and expanding the intents and responses in the intents.json file.

Feel free to explore and enhance the chatbot application according to your specific needs and requirements.
