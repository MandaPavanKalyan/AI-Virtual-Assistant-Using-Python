# Virtual Assistant (VA)

## Steps Involved

### 1. Import Required Libraries
- **pyttsx3**: For text-to-speech conversion.
- **speechRecognition**: For speech recognition and voice command processing.
- **datetime**: To retrieve the current time.
- **wikipedia**: To fetch and summarize Wikipedia articles.
- **webbrowser**: To open websites.
- **os**: To manage file and application execution.
- **smtplib**: To send emails.

### 2. Initialize the Virtual Assistant
- Set up `pyttsx3` engine with a selected voice.
- Create a `speak()` function for text-to-speech conversion.

### 3. Greet the User
- Retrieve the current time.
- Wish the user based on the time of day.

### 4. Take Voice Commands
- Use `speechRecognition` to capture audio input.
- Convert the recognized speech into text.
- Handle errors and exceptions.

### 5. Execute Commands
- **Wikipedia Search**: Retrieve and read a summary of a topic.
- **Web Browsing**: Open YouTube, Google, Facebook, and Stack Overflow.
- **Play Music**: Open and play a song from a specified directory.
- **Check Time**: Retrieve and announce the current system time.
- **Open Files/Folders**: Open a specified code or photo directory.
- **Send Email**: Use `smtplib` to send an email.

---

## Features
- **Voice-Based Interaction**: Executes commands based on speech input.
- **Web Automation**: Opens popular websites.
- **Media Control**: Plays music.
- **File Access**: Opens specific folders and applications.
- **Email Functionality**: Sends emails via SMTP.

---

## Installation

### Prerequisites
Ensure Python is installed and install the required dependencies:

```bash
# Installation
pip install pyttsx3 SpeechRecognition wikipedia
```

---

## Model Performance
- **Speech recognition accuracy**: Depends on microphone quality and background noise.
- **Wikipedia search reliability**: Fetches relevant summaries.
- **Execution speed**: Commands are processed in real-time.

---

## Example Output

```plaintext
Listening...
Recognizing...
User said: "What time is it?"
Sir, the time is 15:30:12
```

```plaintext
Listening...
Recognizing...
User said: "Search Wikipedia for Python programming"
According to Wikipedia:
Python is an interpreted, high-level, general-purpose programming language...
```

---

## Future Enhancements
- Add **multi-language support**.
- Integrate **Google Assistant API** for improved NLP.
- Improve **email security** using OAuth instead of plaintext passwords.
- Add **GUI support** for better user interaction.

---

## Author
Developed by **[Manda Pavan Kalyan]**


