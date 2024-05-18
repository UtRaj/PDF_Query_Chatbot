#  __PDF Query Chatbot__

This project implements a chatbot that answers user questions based on text extracted from PDF files. It utilizes Streamlit for the user interface, Google GenerativeAI for embeddings, LangChain for text processing, and PyPDF2 for PDF parsing.

## **Features**

* Upload PDF files containing relevant information.
* Ask questions related to the content of the uploaded PDFs.
* Receive detailed answers based on the context provided in the PDFs.

## **Installation**

1. Clone the repository:

```
git clone https://github.com/UtRaj/PDF_Query_Chatbot.git
```

2. Navigate to the project directory:

```
cd pdf-query-chatbot
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

## **Usage**

1. Run the Streamlit application:

```
streamlit run app.py
```

2. Access the application through the provided link in the terminal.
   
3. Upload PDF files containing the relevant information.
   
4. Ask questions in the provided text input box.
   
5. Click on "Submit & Process" to process the uploaded PDFs.
   
6. Receive answers based on the context provided in the PDFs.


## **Configuration**

Before running the application, ensure you have set up your Google API key in a .env file as follows:

```
GOOGLE_API_KEY=your-google-api-key
```







