# Chat with Multiple PDF using Gemini

This is a Streamlit web application that allows users to interactively chat with PDF documents using the Gemini model.

## Description

This application leverages the Gemini model from Google's GenerativeAI to enable users to ask questions about uploaded PDF documents. The PDF documents are processed to extract text, which is then split into smaller chunks for efficient processing. The text chunks are embedded using GoogleGenerativeAIEmbeddings and indexed using FAISS for fast similarity search. Users can then ask questions about the content of the PDF documents, and the application provides detailed answers based on the provided context.

## Features

- Upload multiple PDF documents for processing.
- Ask questions about the content of the PDF documents.
- Receive detailed answers based on the provided context.
- Utilizes Google's GenerativeAI model for conversational responses.

## Installation

1. Clone this repository:

    ```
    git clone https://github.com/raghulajithn/pdfQuery.git
    ```

2. Navigate to the project directory:

    ```
    cd pdfQuery
    ```

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Set up your Google API key by creating a `.env` file and adding your API key:

    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

## Usage

1. Run the Streamlit app:

    ```
    streamlit run app.py
    ```

2. Upload your PDF files using the file uploader.
   
3. Click the "Submit & Process" button to process the uploaded PDF files.
   
4. Enter your question in the text input field and press Enter to get a response.

## Example
![example](https://github.com/raghulajithn/pdfQuery/assets/96931716/4c16b527-345e-4f0f-9a74-deed474305ba)


## Credits

- This application utilizes the Gemini model from Google's GenerativeAI.
- It also uses the Streamlit library for building interactive web apps.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
