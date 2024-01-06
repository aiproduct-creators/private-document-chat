# 🗂️ Private Document Chat

Build a chatbot powered by LlamaIndex that augments GPT 4 with the content of your private documents. This versatile application allows you to interact with any document in a conversational manner, making it easier to find information or learn from the document's contents.

- Utilizes Streamlit's `st.chat_input` for taking user queries and `st.chat_message` for displaying both user queries and model responses.
- Leverages LlamaIndex to load, index your private documents, and create a chat engine. This engine retrieves context from the indexed data to respond to each user query effectively.


## Getting Started

### Obtain an OpenAI API Key

To interact with GPT 3.5, you'll need an OpenAI API key:

1. Visit [OpenAI API Keys](https://platform.openai.com/account/api-keys).
2. Click on the `+ Create new secret key` button.
3. Optionally, enter an identifier name and click on the `Create secret key` button.

### Running Locally

To run this app locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/bdhaval/private-document-chat
   cd private-document-chat
   ```

2. **Set Up a Python Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add Your Private Data:**
   
   Add your private data in the `data` folder

5. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

6. **Access the App:**

   Open your web browser and go to http://localhost:8501.

