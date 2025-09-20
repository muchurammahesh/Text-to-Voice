# Text-to-Voice Application

A lightweight web application that converts written text into spoken words using only HTML, CSS, and JavaScript.

## Overview

This app uses the browser's built-in Web Speech API to transform any typed text into natural-sounding speech. You can enter text, choose voice options like pitch and speed, and listen to the spoken version instantly. It's a great tool for accessibility, learning, or just having fun with speech synthesis—all without needing any backend or external service.

<img width="1889" height="910" alt="TextToVoice" src="https://github.com/user-attachments/assets/410f9a5f-4ed3-4107-a1d5-61fe6d00fc66" />

🚀 Check out the deployed application here:  
👉 [Live Demo](https://text-to-voice-by-mahi.netlify.app/  )
## Features

- **Text input:** Type or paste any text you want to hear.
- **Voice selection:** Choose from available voices installed on your device/browser.
- **Adjustable settings:** Control speech rate (speed) and pitch to customize voice output.
- **Play and stop controls:** Start and stop speech easily.
- **No server needed:** Runs completely in the browser using the Web Speech API.
- **Responsive design:** Works on desktop and mobile browsers that support speech synthesis.

## How It Works

- The app uses JavaScript’s Web Speech API’s `SpeechSynthesis` interface to convert text to speech.
- When you input text and press the "Speak" button, JavaScript sends the text to the speech synthesis engine.
- You can customize how the speech sounds by changing the pitch and rate sliders.
- The browser handles all speech processing, so no internet connection or server is required.

## How to Use

1. Open the `index.html` file in a modern web browser that supports the Web Speech API (like Chrome, Firefox, or Edge).
2. Type the text you want spoken into the input box.
3. Select a voice from the dropdown menu.
4. Adjust the pitch and speed sliders if desired.
5. Click the "Speak" button to hear the text aloud.
6. Use the "Stop" button to halt speech anytime.

## Technologies Used

- HTML5
- CSS3
- JavaScript (Web Speech API - SpeechSynthesis)

## License

This project is licensed under the MIT License.
