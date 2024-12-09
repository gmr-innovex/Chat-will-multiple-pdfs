# Chat with PDF using Gemini 💁 - README

## Setup Instructions

### 1: Creating a Virtual Environment
1. Open a terminal.
2. Navigate to the project directory.
3. Run the following command to create a virtual environment:
   ```bash
   python -m venv venv
4. Activate the virtual environment:
   Windows:
    ```bash
    venv\Scripts\activate
   Mac/Linux:
    ```bash
    source venv/bin/activate

### 2: Installing Libraries and Packages

 1. After activating the virtual environment, install the required packages using pip:
    ```bash
    pip install streamlit PyPDF2 langchain google-generativeai faiss-cpu python-dotenv

### 3. Setting Up the .env File

 1. Create a .env file in the project root directory.
 2. Add your Google API key in the following format:
    ```bash
      GOOGLE_API_KEY=your_google_api_key_here

### 4. Setting Up the .env File

1. Ensure the virtual environment is activated.
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
3. Open the URL displayed in the terminal to access the app in your browser.








    


         
