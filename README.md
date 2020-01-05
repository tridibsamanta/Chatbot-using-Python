# Chatbot-using-Python
Build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

:white_check_mark: ## Getting Started 

- [x] Download all the files

- [x] Open Command Prompt

- [x] Get the control to the folder where your files are present

- [x] Make sure your system has the following modules installed - 
tensorflow, keras, nltk, pickle. If not, then install the modules using the command - {pip install module_name}. If your system already has the module, it will show "Requirement already satisfied".

- [x] Now we have to train and create the model. Hence execute the "train_chatbot.py" file using the following command - {python train_chatbot.py}. If the training is successful it will show model created. 

- [x] To open the GUI window and start conversation with the chatbot execute the "chatgui.py" file using the following command - {python chatgui.py}. It will open the GUI  window. 

- [x] Write your text in the section on the right to the send button and click on "Send". Enjoy the responses !  


!!! ERROR GUIDE !!!

While executing the file "train_chatbot.py" if you get some error like - "ImportError: cannot import name 'tf_utils'", uninstall keras using the command - {pip uninstall keras}, then reinstall keras using the command - {pip install keras==2.2.0}. Try executing the file, i hope it works properly ! 
