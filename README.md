# CodeConverse

CodeConverse is a repository that enables seamless communication with your code repository by providing memory and high-quality responses. It allows you to explore and interact with the contents of a GitHub repository using OpenAI's GPT-3 language model.

## Prerequisites

- Python 3.6+
- OpenAI API key (set in the environment variable `OPENAI_API_KEY`)

## Usage
1. Set the OpenAI API key as an environment variable `OPENAI_API_KEY`.
2. Run the script: `app.py`
3. Enter the GitHub URL of the repository you want to explore.
4. Ask questions or interact with the language model. Type `exit()` to quit.
5. Create documentation from the generated responses about your code.
6. Send the document using confluence_upload.py to your confluence project

## Key Features
- Clones and indexes the contents of a GitHub repository.
- Supports various file types, including code, text, and Jupyter Notebook files.
- Generates detailed answers to user queries based on the repository's contents.
- Uses OpenAI's language model for generating responses.
- Supports interactive conversation with the language model.
- Presents top relevant documents for each question.

**Note:** The `confluence_upload.py` file is run separately and is responsible for sending the created documentation to Confluence after applying necessary cleaning and formatting. It facilitates the integration between CodeConverse and Confluence, allowing for the seamless transfer of documentation.
