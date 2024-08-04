# PDF Sage

PDF Sage is an interactive web application that allows users to upload PDF files and ask questions based on the content of those PDFs. The application uses advanced AI technologies to process and understand the text within the PDFs, providing accurate and detailed answers to user queries.

## Demo

![PDF Sage Demo](https://github.com/easyvansh/PDF-Sage/blob/main/demo.gif)  


### How It Works
1. **Upload PDFs:** Users can upload multiple PDF files through the user-friendly interface.
2. **Process PDFs:** The app extracts text from the uploaded PDFs and processes it to create text chunks.
3. **Ask Questions:** Users can input questions related to the content of the uploaded PDFs.
4. **Get Answers:** The app uses AI models to find and display answers based on the PDF content.

## Technologies Used

### Streamlit
- **Purpose:** Streamlit is a framework for building interactive web applications in Python.
- **Usage:** Creates the user interface, allowing users to upload PDF files and interact with the application.

### Google Generative AI
- **Purpose:** Provides advanced AI capabilities, including text generation and embeddings.
- **Usage:** Generates embeddings and conversational models to understand and answer user questions based on PDF content.

### Langchain
- **Purpose:** Framework for building applications with language models.
- **Usage:** Creates and manages conversational chains, integrating AI models to process and answer queries.

### PyPDF2
- **Purpose:** Library for reading and manipulating PDF files in Python.
- **Usage:** Extracts text from uploaded PDF files for processing.

### FAISS (Facebook AI Similarity Search)
- **Purpose:** Library for efficient similarity search and clustering of dense vectors.
- **Usage:** Stores and retrieves text embeddings for fast and accurate similarity searches on PDF text chunks.

### langchain_google_genai
- **Purpose:** Integration between Langchain and Google Generative AI.
- **Usage:** Leverages Google Generative AI’s embedding and conversational capabilities within the Langchain framework.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/easyvansh/PDF-Sage.git
    cd pdf-sage
    ```

2. **Create and activate a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**
    - Create a `.env` file in the root directory and add your Google API key:
        ```env
        GOOGLE_API_KEY=your_google_api_key_here
        ```

5. **Run the application:**
    ```sh
    streamlit run app.py
    ```

## Usage

1. **Upload your PDF files** using the sidebar menu.
2. **Click "Submit & Process"** to analyze the files.
3. **Ask any question** related to the content of the PDF files in the provided text input box.
4. **Receive detailed answers** based on the PDF content.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the developers of the libraries and frameworks used in this project.

---
