#**DocChat: Where PDFs Open Up to Conversation**

DocChat is a Streamlit web application designed to facilitate conversation with indexed PDF documents. It allows users to upload PDF files, index them, and then query the indexed documents to obtain relevant information.

**Getting Started**

To run the DocChat application locally, follow these steps:

**Install the required dependencies** 
pip install -r requirements.txt

**Set up your OpenAI API key:**
Before running the application, ensure you have an OpenAI API key. You can set your API key by either:
Setting the OPENAI_API_KEY environment variable, or
Entering the API key when prompted upon running the application.

**Run the Streamlit application:**
streamlit run AskGita.py

**Access the application:**
Once the application is running, you can access it by opening a web browser and navigating to http://localhost:8501.

**Usage**
**Uploading Files**
Use the file uploader in the sidebar to upload PDF documents. Multiple files can be uploaded simultaneously.
Indexing Documents
Click on the "Index your files to get started" button in the sidebar to index the uploaded documents.
Once indexed, a success message will be displayed.
Asking Queries
Type your question in the input box labeled "Ask Your Question Here" and press Enter.
The application will search the indexed documents for relevant information related to your query.
The results will be displayed in the main area of the application.
**GITA Integration**
Additionally, the application allows querying against a predefined set of documents labeled as GITA. This functionality can be accessed by clicking the "Ask GITA" button in the sidebar.

**Dependencies**
streamlit: For building interactive web applications.
llama-index: For document indexing and querying.
openai: For integrating with the OpenAI API.
