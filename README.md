# AI Chatbot

This repository contains a simple AI Chatbot built using Natural Language Processing (NLP) and machine learning techniques in Python. The chatbot utilizes Keras, a powerful Python deep learning library, to train a Sequential model on predefined intents and responses, which can be easily customized in the `intents.json` file. This allows the chatbot to understand and classify user text input, and respond accordingly.

The model consists of three main layers: an Embedding layer that turns words into corresponding dense vectors; a GlobalAveragePooling1D layer that down-samples the input representation by taking the average value over the time dimension; and a sequence of Dense layers that perform classification on the features extracted by the previous layers.

Once trained, the model, tokenizer, and label encoder are saved for future use. During interaction, the chatbot takes user input, passes it through the model, and selects the most appropriate response based on the model's classification.

The chatbot's conversation can be terminated with the input 'quit'. Please note that this is a basic implementation of an AI Chatbot, primarily intended for simple conversations. For more complex scenarios or deeper contextual understanding, the model may require further refinement and tuning. This project serves as a foundational starting point for anyone interested in developing their own AI Chatbot. Enjoy exploring and expanding on this code!

