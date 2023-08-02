# chatter

This project encompasses the creation of an interactive chatbot system. It involves two key components:

>Training Code (train_chatbot.py): 
This code handles the training process of the chatbot. It preprocesses user patterns, constructs a dataset, and utilizes a neural network model to predict user intents and generate appropriate responses. The trained model is then saved as 'chatbot_model.h5'.

>GUI Interface (chatgui.py): 
The GUI code employs the tkinter library to establish an interactive platform for users to engage with the chatbot. It facilitates user input, showcases the chat history in the ChatLog text box, manages messages, triggers chatbot responses, and updates the conversation display.

>Supporting Files:

>intents.json: This file contains a collection of user intents and associated patterns for training the chatbot.

>words.pkl: A pickled file storing the processed vocabulary of lemmatized words used in the training.

>chatbot_model.h5: The trained neural network model saved as a file, enabling the chatbot to predict intents and generate appropriate responses based on user input.



Overall, this project results in an interactive chatbot system that users can engage with through a graphical user interface, facilitating natural conversations based on pre-trained patterns and responses.
