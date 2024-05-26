# 🌐 Bidirectional Translation System

Welcome to the Bidirectional Translation System! This funky project uses the awesome power of the M5 Atom Echo, OpenAI GPT-4, and OpenAI Whisper to deliver seamless bidirectional translation. Speak into the M5 Atom Echo, and watch (or rather, listen) as your words get transcribed, translated, and spoken back in another language. All with a simple push of a button! 🎉

## Features
- 🎤 Speech Recognition: Leveraging OpenAI Whisper for top-notch transcription.
- 🌐 Translation: Utilizing OpenAI GPT-4 for accurate and context-aware translations.
- 🗣️ Text-to-Speech: Transforming translated text back to spoken words.
- 🔄 Bidirectional Communication: Supports smooth back-and-forth conversations between two languages.

## Hardware Requirements
- M5 Atom Echo: A compact and versatile microcontroller with a built-in microphone and speaker.

## Software Requirements
- Python: Our main programming language.
- OpenAI GPT-4 API: For translation services.
- OpenAI Whisper: For speech-to-text transcription.
- Text-to-Speech (TTS) System: For converting text back to speech.

## 🚀 Getting Started
### Prerequisites
- M5 Atom Echo: Ensure it's set up and connected.
- OpenAI API Keys: Get your keys for both GPT-4 and Whisper.
- Python Environment: Make sure you have Python and the necessary libraries.

### Installation
1. Clone the Repository:
    ```bash
    git clone https://github.com/yourusername/bidirectional-translation-system.git
    cd bidirectional-translation-system
    ```

2. Install Dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Configuration
#### API Keys:
1. Create a `.env` file in the project root.
2. Add your API keys:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

#### Hardware Setup:
- Ensure your M5 Atom Echo is connected and recognized.

### Running the System
1. Start the Translation Service:
    ```bash
    python main.py
    ```

2. **Interaction**:
   - Press the button on the M5 Atom Echo to speak.
   - The system transcribes, translates, and vocalizes the translation.
   - Press again to listen and respond, creating a back-and-forth conversation.

## 🎉 Usage
- 🎙️ **Push-to-Talk**: Press the button to start speaking.
- 🗣️ **Translation & Response**: Listen to the translation and press the button to respond.

## 🤝 Contributing
We welcome contributions from the community! Have ideas or features to add? Open an issue or submit a pull request.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 🙏 Acknowledgements
- OpenAI: For providing GPT-4 and Whisper APIs.
- M5Stack: For creating the M5 Atom Echo.

## 📬 Contact
For questions or support, reach out at yourname@example.com.
