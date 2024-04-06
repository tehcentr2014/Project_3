## Content Marketing Assistant

### Run the App:

[On HEROKU]([https://website-name.com](https://content-manager-p3-52a70c663149.herokuapp.com/])

or

[For Free on Streamlit]([[https://website-name.com])

### Overview
Working quite often with marketing advertising campaigns and to speed up the process, I came up with an idea of ​​creating a product description generator. And today I want to introduce you the Content Marketing Assistant. This is a Python App designed to aid in the automatic generation of product descriptions using OpenAI Assistans API. This application simplifies the process by taking provided keywords and generating concise descriptions based on predefined criteria.

![image](https://github.com/tehcentr2014/Project_3/assets/161617022/b7cfa2f0-a15d-4ca1-88a7-d33e7e0dfb10)

### Features
- **Keyword Input**: Users can input keywords related to the product for which they want to generate descriptions.
- **Duplicate Removal**: The application provides a functionality to remove duplicate keywords entered by the user.
- **Description Generation**: Using the provided keywords, the application generates product descriptions consisting of a title, bullet points, and a detailed description, adhering to specified character limits.
- **Streamlit Interface**: The application offers a user-friendly interface powered by Streamlit, making it accessible and easy to use.

### Installation
1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up OpenAI API access by creating a `.env` file in the root directory and adding your OpenAI API key:

    ```
    OPENAI_API_KEY=<your-openai-api-key>
    ```

### Usage
1. Run the application:

    ```bash
    python main.py
    ```

2. Access the application through the provided URL in your browser.
3. Follow the on-screen instructions to enter keywords and generate product descriptions.
4. Click the "Create description" button to initiate the description generation process.
5. Wait for the application to generate the description based on the provided keywords.
6. The generated description will be displayed on the interface.

### Acknowledgments
- This project utilizes the OpenAI API for natural language processing.
- Streamlit is used for creating the user interface.

