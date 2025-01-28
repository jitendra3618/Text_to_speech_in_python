# 🗣️ Text-to-Speech (TTS) Application

This project is a user-friendly **Text-to-Speech (TTS)** application built using Python. The application integrates a graphical user interface (GUI) designed with `tkinter` and utilizes the `pyttsx3` library for speech synthesis.

---

## 🌟 Features

- ✅ Interactive and visually appealing GUI.
- ✅ Converts user-input text into speech seamlessly.
- ✅ Platform-independent functionality (Windows, macOS, Linux).
- ✅ Offline support for TTS functionality (no internet required).

---

## 📚 Libraries Used

- **[tkinter](https://docs.python.org/3/library/tkinter.html)**: For designing the GUI.
- **[pyttsx3](https://pypi.org/project/pyttsx3/)**: For text-to-speech conversion.

---

## ⚙️ How It Works

1. **Graphical Interface**:
   - Built with Python’s built-in GUI library, `tkinter`.
   - Includes:
     - A structured **`LabelFrame`** for organization.
     - An **`Entry`** widget for text input.
     - A **Button** to trigger the speech functionality.
   - Styled with padding, fonts, and dimensions for better usability and aesthetic appeal.

2. **Text-to-Speech Functionality**:
   - `pyttsx3` is used to convert the text entered in the input field into speech.
   - The `speaknow()` function:
     - Retrieves user input.
     - Initializes the TTS engine.
     - Plays the audio output.
   - The library supports speech queuing, initialization, and stopping, ensuring a smooth user experience.

---

## 🛠️ Installation

1. Install Python (version 3.6 or higher).
2. Install the required library using `pip`:
   ```bash
   pip install pyttsx3
Clone or download this repository.
## Usage
Run the Python script:
bash
Copy
Edit
python main.py
Enter your text in the input field.
Click the Speak button to hear the text spoken aloud.
## Highlights
This project demonstrates Python’s simplicity and versatility by combining GUI development and speech synthesis. It highlights the ease of integrating multiple libraries to solve real-world problems with minimal code.

Through this project, I enhanced my skills in:

🖼️ GUI design with tkinter.
🔊 Using external libraries like pyttsx3 for advanced functionality.
