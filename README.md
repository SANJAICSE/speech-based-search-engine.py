
---

# 🎤 Speech-Based Search Engine

This Python script allows users to perform **Google searches using voice commands**. It uses speech recognition to capture spoken input, converts it to text, and opens the search results in a web browser.

---

## ✅ Features

* 🗣️ Voice-based input using your microphone
* 🔍 Automatic Google search with the spoken query
* 🗨️ Text-to-speech feedback to guide the user

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> **Note:** On some systems, installing `pyaudio` may require additional setup.

---

## 🚀 How to Run

Run the script in a Python environment with microphone access:

```bash
python "speech based search engine.py"
```

1. The system prompts you to speak a search query.
2. It listens and transcribes your speech.
3. A web browser opens with the search results.
4. The system speaks out the action it performed.

---

## 📂 Script Breakdown

* `take_command()`: Captures voice input and returns the transcribed text.
* `speak(text)`: Converts text to speech.
* `search_web(query)`: Opens a Google search using the query.

---

## 🛠 Example

```python
# Run the main function
if __name__ == "__main__":
    query = take_command()
    search_web(query)
```

---

## ⚠️ Notes

* Ensure your microphone is working and permissions are granted.
* The script uses Google's speech recognition API (requires internet).
* Can be adapted to search other websites or APIs by modifying the `search_web()` function.

---


