# Fine-Tune GPT-2 for Mental Health Support

This project demonstrates how to fine-tune the GPT-2 model on a mental health dataset and deploy a chatbot using a Telegram bot. The model is trained to provide answers related to mental health queries.

## Description

This repository contains code for fine-tuning the GPT-2 model with a custom dataset and creating a Telegram bot to interact with users. The dataset includes question-answer pairs related to mental health topics. The fine-tuned model is then used to generate responses to user queries through a Telegram bot.

## Technologies Used

- **Transformers**: For loading and fine-tuning the GPT-2 model.
- **Pandas**: For handling data and saving it to a CSV file.
- **Datasets**: For dataset management.
- **Telebot**: For creating the Telegram bot.
- **OpenAI API**: For generating responses to user queries.

## Installation

To set up the environment and run the code, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Swarnak27/Mental-health-chatbot
   cd Mental-health-chatbot

## Install the required libraries:
 ```bash
-pip install transformers==4.28.0 pandas datasets telebot openai
 ```
## Set up your OpenAI API key:
-Replace the placeholder API key in the code with your own OpenAI API key.

## Usage
* Fine-Tuning the Model
* Create a dataset of question-answer pairs related to mental health.
* Convert the dataset into a CSV file.
* Fine-tune the GPT-2 model using the dataset.
* Running the Telegram Bot
* Replace the placeholder Telegram bot token and OpenAI API key in the code.

## Run the script to start the Telegram bot:

* python your_script_name.py
* Interact with the bot on Telegram to ask mental health-related questions and receive responses.

## Example
* question = "What is mental health?"
* answer = ask_question(question, fine_tuned_model, tokenizer)
* print(f"Question: {question}\nAnswer: {answer}")

## Contributing
* If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## Issues
* If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub Issues page.

## Acknowledgments
* Hugging Face Transformers
* Telegram Bot API
* OpenAI API
