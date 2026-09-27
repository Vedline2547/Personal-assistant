# 🎙️ Personal Voice Assistant using Python

A Python-based voice-controlled personal assistant that interacts with users through speech recognition and text-to-speech. The assistant listens to voice commands, responds verbally, tells the current time, performs Google searches, and opens YouTube.

## 🚀 Features

* **Voice Recognition:** Recognizes spoken commands using SpeechRecognition.
* **Text-to-Speech:** Responds verbally using pyttsx3.
* **Greeting System:** Responds to greetings such as "Hello" and "Hi".
* **Time Announcement:** Announces the current time.
* **Google Search:** Searches Google using voice commands.
* **YouTube Integration:** Opens YouTube through the default web browser.
* **Voice-Controlled Exit:** Ends the assistant when the user says "Bye", "Exit", or "Quit".

## 🛠️ Technologies Used

| Technology        | Purpose                    |
| ----------------- | -------------------------- |
| Python            | Main programming language  |
| SpeechRecognition | Converts speech into text  |
| PyAudio           | Microphone access          |
| pyttsx3           | Text-to-speech conversion  |
| datetime          | Retrieves the current time |
| webbrowser        | Opens Google and YouTube   |

## 📂 Project Structure

```text
Personal-assistant/
│
├── main.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Vedline2547/Personal-assistant.git
```

### 2. Navigate to the project directory

```bash
cd Personal-assistant
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

For Windows PowerShell:

```powershell
.venv\Scripts\Activate
```

### 5. Install dependencies

```bash
pip install SpeechRecognition pyttsx3 PyAudio
```

Alternatively, if you have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 6. Run the assistant

```bash
python main.py
```

Make sure your microphone is connected and that Python has permission to access it.

## 🎤 Voice Commands

| Voice Command     | Action                                        |
| ----------------- | --------------------------------------------- |
| Hello / Hi        | Greets the user                               |
| What is the time? | Announces the current time                    |
| Search            | Asks what you want to search and opens Google |
| YouTube           | Opens YouTube in the default browser          |
| Bye               | Says goodbye and exits                        |
| Exit / Quit       | Terminates the assistant                      |

## 🧠 How It Works

1. The `pyttsx3` engine initializes the text-to-speech functionality.
2. The microphone captures audio using PyAudio.
3. SpeechRecognition sends the recorded audio to Google's speech recognition service for transcription.
4. The recognized text is converted to lowercase and passed to the `respond()` function.
5. The assistant identifies the command and executes the appropriate action.
6. The assistant responds through speech using `speak()`.

## 📦 Requirements

* Python 3.x
* A working microphone
* Internet connection for Google speech recognition and web searches
* SpeechRecognition
* PyAudio
* pyttsx3

## 🔮 Future Improvements

* Integrate an AI language model for intelligent conversational responses.
* Add weather forecasts and news updates.
* Launch desktop applications using voice commands.
* Implement offline speech recognition.
* Add improved error handling and background noise reduction.
* Add a graphical user interface using Flask or Tkinter.

## 🎯 Learning Objectives

Through this project, I practiced:

* Python functions, conditional statements, and loops.
* Speech recognition and text-to-speech integration.
* Working with Python libraries and external services.
* Voice-controlled automation.
* Opening websites programmatically using Python.

## 👨‍💻 Author

**Vedline Ochieng**

* GitHub: [@Vedline2547](https://github.com/Vedline2547)

---

⭐ If you find this project interesting, feel free to star the repository!
