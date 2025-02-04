# Privacy-Focused AI Chatbot with DeepSeek and OLLAMA

A local AI chatbot implementation that prioritizes privacy by running completely on your machine, using DeepSeek's R1 model with Langchain and OLLAMA integration.

## 🔑 Key Features
- Complete privacy: All processing happens locally on your machine
- No data sharing with external servers
- Works offline once model is downloaded
- Custom UI with Streamlit
- Flexible model selection
- Chat history management
- Temperature controls for response creativity

## 🛠️ Technologies Used
- DeepSeek R1 (1.5B parameters model)
- OLLAMA for local model deployment
- Langchain for framework integration
- Streamlit for user interface
- Python 3.x

## ⚙️ Setup Instructions
1. Install OLLAMA on your machine
2. Clone this repository
3. Create a virtual environment:
   ```python
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
4. Install requirements:
  pip install -r requirements.txt
5. Run the application:
  streamlit run app.py


🚀 Usage

Start chatting with the AI through the web interface
Use the sidebar to configure model settings
Ask questions, generate code, or create creative content
All interactions stay private on your machine

🔒 Privacy Features

Local execution
No data sent to external servers
Complete control over your data
Perfect for sensitive information

📝 Note
This project is designed for users who prioritize data privacy while wanting to leverage the power of AI. It's ideal for developers, businesses, and individuals who need to maintain control over their data.
