# ChatFlex - AI Chatbot Hub

ChatFlex is a modern, user-friendly AI chatbot interface that allows you to interact with multiple AI models through a single, intuitive platform. The application features a beautiful UI with customizable AI personalities and real-time chat statistics.

## Features

- 🤖 Multiple AI model support
- 🎭 Customizable AI personalities
- 💬 Real-time chat interface
- 📊 Chat statistics
- 🎨 Modern, responsive UI
- 🔄 Session management
- 🧹 Chat history clearing

## Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ChatFlex
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the project root directory and add your API keys:
```env
OPENAI_API_KEY=your_openai_api_key
# Add other API keys as needed
```

## Running the Application

1. Make sure your virtual environment is activated (if using one)

2. Start the Streamlit application:
```bash
streamlit run streamlit_app.py
```

3. Open your web browser and navigate to the URL shown in the terminal (typically http://localhost:8501)

## Usage

1. Select an AI model from the sidebar
2. Choose an AI personality or create a custom one
3. Click "Start Chat" to begin your conversation
4. Type your messages in the chat input at the bottom
5. Use the "Clear Chat" button to start a new conversation

## Project Structure

```
ChatFlex/
├── streamlit_app.py      # Main Streamlit application
├── mainV02.py           # AI model management and core functionality
├── requirements.txt     # Project dependencies
├── .env                # Environment variables (create this file)
└── README.md           # This file
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
