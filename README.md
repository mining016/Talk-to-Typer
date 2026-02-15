# 🎈 Talk to Typer 🤖
A fun, kid-friendly voice-to-text web application designed for educational and domestic use. It features a colorful "WhatsApp-style" chat interface where kids can speak and see their words appear as message bubbles.

## ✨ Features

*   **🎙️ Voice Typing**: Speak to type using the Web Speech API.
*   **💬 Chat Style UI**: Text appears in bubbles on the right, just like a chat app.
*   **🌍 Multi-Language Support**:
    *   **English** (🇬🇧)
    *   **Hindi** (🇮🇳 हिंदी)
    *   **Gujarati** (🇮🇳 ગુજરાતી)
    *   *Check out the [Official Chrome Web Speech API Demo](https://www.google.com/intl/en/chrome/demos/speech.html) to see all supported languages.*
*   **😁 Kid-Friendly Design**: Big buttons, bright colors, and simple controls.
*   **🔒 Privacy Focused**: Runs locally in your browser. No login or signup required.

## 🎯 Use Cases & Safety

*   **📝 Writing Aid**: Helps kids writing text by speaking.
*   **🔤 Spelling Identification**: See how words are spelled as you speak.
*   **🛡️ Kids Safe**:
    *   **100% Local**: Designed for domestic use on your machine.
    *   **No External AI**: Does not require third-party AI API keys or subscriptions.

## 🚀 How to Run

You can run this project easily using a local web server.

### Prerequisites

*   A modern web browser (Chrome, Edge, Safari, Brave).
*   Correct microphone permissions accepted in the browser.

### Running with `npx` (Recommended)

1.  Open your terminal or command prompt in the project folder.
2.  Run the following command:
    ```bash
    npx http-server
    ```
3.  Open your browser and go to: `http://localhost:8080`

## 🛠️ Usage

1.  **Select Language**: Click the language button (bottom left) to toggle between **English**, **Hindi**, and **Gujarati**.
2.  **Start Speaking**: Click the big **Mic Button** (🎤) in the center. It will turn red and pulse.
3.  **Stop Speaking**: Click the Mic button again or wait (it's in continuous mode).
4.  **Clear**: Click the **Clear** button (🗑️) to delete all messages.

## 📝 Notes

*   This app uses the **Web Speech API**. It works best in **Google Chrome** or **Microsoft Edge**.
*   Network connection is required for the speech recognition engine in Chrome.