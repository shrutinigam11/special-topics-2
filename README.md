# Special Topics - 2
Special project completed during the 3rd year of my undergrad: Programming Assistance Chatbot with Neural Networks and NLP

Developed an AI-powered chatbot using PyTorch and NLP that aids in answering C programming-related queries, using PyTorch for neural network training with ReLU and optimizer adjustments for effective error handling.
Leveraged the 1st year’s Fundamentals of Programming Lab’s C programs for the dataset. Final epoch loss range: 0.0015 - 0.0043.

This project focuses on the development of a chatbot using PyTorch and Natural Language Processing techniques. The primary goal was to build a conversational agent capable of responding to user queries in a meaningful way. The project utilized a dataset (the 1st year Fundamentals of Programming Lab's C Programs) containing intents and their corresponding patterns and responses, stored in a JSON format.

The implementation involved several key steps. Firstly, the dataset was preprocessed, including tokenization, stemming, and the creation of a bag-of-words representation for each sentence. Next, a feedforward neural network model was constructed using PyTorch, consisting of three linear layers with ReLU activation functions.

The model was trained using the cleaned dataset, employing the Adam optimizer and CrossEntropyLoss function. Training was conducted over multiple epochs to optimize the model's performance. Once training was completed, the trained model along with relevant metadata such as input size, hidden size, output size, and word tags were saved to a file for future use.

Finally, the chatbot was deployed for interaction with users. It processed user input, predicted the appropriate tag, and generated a response based on the trained model's output. Users could engage with the chatbot by typing messages, receiving responses tailored to the intents provided in the dataset.
