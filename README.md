## README for Amunet Chatbot Project

### Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Contributors](#contributors)
8. [License](#license)

### Introduction
Amunet is a state-of-the-art chatbot designed to assist users with a wide range of queries and provide valuable information based on their input. Leveraging advanced natural language processing (NLP) and machine learning techniques, Amunet can understand and respond to user inquiries with high accuracy and relevance.

### Features
- Text and voice interaction
- Sentiment analysis to provide tailored responses
- Google search integration for fetching information
- Speech recognition for voice-based interactions
- Text-to-speech for bot responses

### Requirements
- Python 3.x
- Flask
- NLTK
- SpeechRecognition
- Pyttsx3
- BeautifulSoup4
- Requests
- Google search library (`googlesearch-python`)

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/shreyags2802/Amunet_bot.git
    cd amunet-chatbot
    ```

2. Set up a virtual environment (optional but recommended):
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Download NLTK data:
    ```python
    import nltk
    nltk.download('vader_lexicon')
    ```

### Usage
1. Run the Flask app:
    ```sh
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000/`.

3. Interact with Amunet either through text or voice, based on your preference.

### Project Structure
```
amunet-chatbot/
│
├── templates/
│   ├── about.html
│   ├── chat.html
│   └── index.html
│
├── static/
│   └── (Static assets like CSS, JS if needed)
│
├── app.py
├── requirements.txt
└── README.md
```

### Contributors
- Bilwananda (4MH21CS074)
- Shalom Raj (4MH21CS086)
- Shreya GS (4MH21CS091)
- Shreyas Gowda S (4MH21CS092)

### Additional Notes
- Ensure your microphone and speakers are functioning correctly for voice interactions.
- If you encounter any issues, please open an issue on the GitHub repository or contact the contributors.

Happy chatting with Amunet!
