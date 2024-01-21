
# LLM Q&A Chatbot - Documentation

## Overview

This Streamlit Q&A Chatbot is built using the Langchain library and OpenAI API. It allows users to input questions and receive responses from the OpenAI model.

## Prerequisites

- Python 3.x
- OpenAI API key
- Streamlit
- Langchain
- HuggingFace Hub

## Setup

1. Clone the repository:

```bash
   git clone https://github.com/your_username/your_repository.git
```
2. Create and activate the virtual environment:
```bash
python -m venv venv
```
Activate the virtual environment (In Windows):
```bash
.\venv\Scripts\activate
```
3. Install dependencies:

```bash
pip install -r requirements.txt
```
4. Create a .env file in the project root and add your OpenAI API key:
```bash
OPENAI_API_KEY=your_openai_api_key_here
```
## Usage
#### Run the Streamlit app:

```bash
streamlit run app.py
```
- Enter your question in the provided input field.

- Click the "Ask the question" button to get the AI-generated response.

## Code Structure
- app.py: Main Streamlit application file.
- langchain.llms.OpenAI: Langchain OpenAI wrapper for interaction with the OpenAI API.
- get_openai_response(): Function to send a question to OpenAI and receive a response.
- Streamlit components for UI: st.set_page_config(), st.header(), st.text_input(), st.button(), st.subheader(), and st.write().
## Important Note
- The OpenAI model text-davinci-003 has been deprecated. 
- The code has been modified to use the gpt-3.5-turbo-instruct model. Ensure your OpenAI API key is valid and replace the model name if needed.

For the latest updates and deprecations, refer to the OpenAI documentation.

## Contributing
Feel free to contribute to this project by submitting pull requests or reporting issues.
## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Authors

- [@shamimkhaled](https://www.github.com/shamimkhaled)

