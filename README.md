# Blog Generator using Streamlit and LLaMA-2

This project is a web application that generates blog content based on user input. The application uses the LLaMA-2 model and is built with Streamlit for the front-end interface.

## Features

- **Input Fields**: Users can enter the blog topic and specify the number of words.
- **Blog Style Selection**: Users can choose the style of the blog (Researcher, Data Scientist, Common).
- **Blog Generation**: On clicking the "Generate" button, the app generates a blog using the LLaMA-2 model.
## Download the model from 
 https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main

## Requirements

- Python 3.9+
- Streamlit
- langchain
- CTransformers

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/blog-generator.git
   cd blog-generator
2. **Create and Activate Virtual Environment:**
   ```bash
   .\venv\Scripts\activate

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
4. **Run the Application:**
   ```bash
   streamlit run app.py
  
