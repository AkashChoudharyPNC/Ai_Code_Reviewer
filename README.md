# AI Code Reviewer

This is a Streamlit application that uses Google's Generative AI to review code, detect bugs, and provide solutions with detailed explanations. The AI model is configured to act as an advanced AI code reviewer.

## Features

- User-friendly interface to input code queries.
- Analyzes code for logical, syntax, performance, and security issues.
- Provides detailed explanations and optimized solutions for detected issues.
- Confirms correctness and suggests best practices or optimizations for correct code.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/AkashChoudharyPNC/Ai_Code_Reviewer.git
    cd your-repo-name
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Navigate to the directory containing [app.py](http://_vscodecontentref_/0):
    ```sh
    cd Ai_Code_Reviewer
    ```

2. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

3. Open your web browser and go to `http://localhost:8501` to access the application.

## Configuration

- Replace the placeholder API key in [app.py](http://_vscodecontentref_/1) with your valid Google Generative AI API key:
    ```python
    genai.configure(api_key=st.secrets["api_key"])
    ```

## File Structure

         Ai_Code_Reviewer/ 
                         │ ├── app.py # Main application file 
                           ├── requirements.txt # List of required packages 
                           └── venv/ # Virtual environment directory