<h1 align='center'>🤖 MULTI-MODAL RAG APPLICATION 🤖</h1>
<h3 align='center'>Unlocking Personalized Knowledge with Multi-Modal Chatbots</h3>
<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6f2bc880-fd32-41e1-b3b6-913e1592ff0a" alt="Flowcharts (0)">
</p>

---

# 1. Overview
🌟 **Welcome to the Future of Interactive Knowledge!** 🌟

PKM (**Personal Knowledge Model**) takes a massive leap into the future of intelligent interaction. By blending multi-modal retrieval-augmented generation (RAG) technology, we're crafting a system that can retrieve, understand, and respond using text, images, videos, and PDFs. The PKM empowers users to create **personalized knowledge graphs** from their interactions and browsing data, stored and processed entirely on-device for unmatched privacy.

🚀 **Why Multi-Modal?**  
Multi-modal capabilities allow the chatbot to process inputs across various formats — whether it's extracting key insights from PDFs, answering questions about YouTube videos, or responding to images. This opens up a vast realm of possibilities, making information retrieval dynamic and highly contextual.

---

# 2. Multi-Modal Chatbot Architecture

- **PKM Core Architecture**
<p align="center">
  <img src="https://github.com/chakka-guna-sekhar-venkata-chennaiah/Mutli-Modal-RAG-ChaBot/assets/110555361/1cb2a4aa-1a11-4b6d-875b-d9676c98edc8" alt="PKM Core Architecture">
</p>

- **MMR-PDF (Multi-Modal RAG for PDF) Architecture**
<p align="center">
  <img src="https://github.com/chakka-guna-sekhar-venkata-chennaiah/Mutli-Modal-RAG-ChaBot/assets/110555361/8e0788c4-8b87-4221-9d5a-9707ccccfce4" alt="MMR-PDF Architecture">
</p>

- **MMR-Video (Multi-Modal RAG for Video) Architecture**
<p align="center">
  <img src="https://github.com/chakka-guna-sekhar-venkata-chennaiah/Mutli-Modal-RAG-ChaBot/assets/110555361/ce045df8-f3c5-4d26-adc4-8fdb2540aa1f" alt="MMR-Video Architecture">
</p>

---

# 3. Technology Stack
Our tech stack has been carefully selected to build a robust, efficient, and future-proof multi-modal chatbot:

- 🧠 **MindsDB OpenAI Endpoint** — For building custom LLMs with the help of AI models.  
- 🧩 **LangChain** — For creating chains of operations for natural language understanding.  
- 🖥️ **Streamlit** — To power the UI/UX of the chatbot in an easy-to-deploy format.  
- 🗂️ **FAISS** — Fast and efficient similarity search across embeddings, crucial for retrieving relevant data.

Here’s a sneak peek into the code that runs behind this chatbot, leveraging LangChain’s chain base class and MindsDB endpoints.

- **Custom LLM Creation:**


- **Custom Embedding Function:**


---

# 4. How to Set Up the Project
### Step 1: Clone the Repository
```bash
git clone https://github.com/varaprasadtarunkumar/MULTI-MODAL-RAG-CHATBOT.git
```

### Step 2: Navigate to the Project Directory
Change into the project directory:
```bash
cd MULTIMODAL_RAG_BOT
```
### Step 3: Install the Dependencies
Install all required libraries and packages:

```bash
python -m pip install -r requirements.txt
```
### Step 4: Add Secrets
Create a .streamlit folder in the project root, and inside it, create a secrets.toml file. 
Add your MindsDB API key:
```bash
api_key='your-minds-api-key'
```
### Step 5: Start the Application
Run the Streamlit application:
```bash
python -m streamlit run app.py
```
