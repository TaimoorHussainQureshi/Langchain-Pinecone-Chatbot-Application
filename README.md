
# Langchain Pinecone Chatbot Application

## Overview
This application is a chatbot built using Streamlit, Langchain, Pinecone, and OpenAI's GPT models. It leverages the capabilities of these tools and APIs to create an interactive chat interface.

## Features
- **Streamlit**: For creating the web application interface.
- **Langchain**: Utilized for chat model interactions.
- **Pinecone**: Integrated for indexing and querying data.
- **OpenAI GPT Models**: Powers the conversational AI capabilities.

## Installation
To set up this project, you will need Python and the necessary packages listed in `requirements.txt`.

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Install Dependencies**: Run the following command to install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the application:

1. Navigate to the project directory.

2. Run the following command:
   ```bash
   streamlit run main.py
   ```

3. The application should now be running on your local server, and you can interact with it via the provided web interface.

## Configuration
- **OpenAI API Key**: Ensure you have set your OpenAI API key in `utils.py` or as an environment variable for the application to function correctly.
- **Pinecone API Key**: Set your Pinecone API key in `utils.py`.

## File Descriptions
- `main.py`: The main script for running the Streamlit application.
- `utils.py`: Contains utility functions for the chatbot, including API calls to OpenAI and Pinecone.
- `requirements.txt`: Lists all the Python packages that need to be installed.

## Contributing
Feel free to fork this project and submit pull requests. You can also open issues for any bugs found or feature requests.
