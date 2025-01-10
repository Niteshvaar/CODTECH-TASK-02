NAME : NITESHVAAR K K 
COMPANY : CODTECH IT SOLUTIONS 
ID : CT12DS2873 
DOMAIN : MACHINE LEARNING 
DURATION : DECEMBER 2024 TO FEBRUARY 2025

OVERVIEW OF THE PROJECT

TITLE : 2.	To develop a text-to-speech conversion application that allows users to input text and generate corresponding audio output. The application should support multiple languages and voices, providing users with options to customize the speech synthesis according to their preferences.

OBJECTIVE
This project is designed to create a text-to-speech (TTS) conversion application that allows users to input text and generate corresponding audio output. The application provides two options for speech synthesis: online (using Google Text-to-Speech - gTTS) and offline (using pyttsx3). The application also supports multiple languages, and users can customize the speech synthesis parameters like voice selection, rate, and language.

KEY FEATURES
1.Multiple Speech Synthesis Options:
Google Text-to-Speech (gTTS): This method requires an internet connection and uses Google's cloud-based speech synthesis to generate high-quality audio output.
pyttsx3: This method works offline and uses the system's built-in text-to-speech engine to generate audio. It supports different voices and speech rates.

2.Language Detection:
The application automatically detects the language of the input text using the langdetect library, and users can either use the detected language or specify their preferred language code.

3.Voice Customization:
The pyttsx3 option allows users to choose from a list of available voices (e.g., male, female, or different accents/languages). Users can also adjust the speech rate (speed of speech) to suit their preferences.

4.Audio Playback:
The application plays the generated audio immediately after conversion using the playsound library, ensuring that the user can hear the output right away.
For the gTTS method, the audio is saved as an MP3 file and played back to the user.

5.User Interface:
The user interacts with the application through a command-line interface (CLI). The user is prompted to select between online and offline speech synthesis, input the text to convert, and customize various speech parameters like language, voice, and speech rate.

6.Error Handling:
The application includes basic error handling to manage issues like network errors (for gTTS) and invalid inputs from the user.

LIBRARIES USED:
pyttsx3: A Python library for offline text-to-speech conversion that supports multiple voices and speech rates.
gTTS (Google Text-to-Speech): A Python library that interfaces with Google’s TTS API to convert text to speech.
playsound: A library for playing audio files (MP3 format in this case).
langdetect: A language detection library used to identify the language of the input text.

FLOW OF APPLICATION:
1.The program prompts the user to choose between online (gTTS) or offline (pyttsx3) synthesis.
2.The user inputs the text they want to convert to speech.
3.The language of the input text is detected automatically, but users can specify a custom language code if desired.
4.Based on the user's choice, the appropriate text-to-speech method is used, and the audio is played back.
5.In the offline mode, users can customize the voice and speech rate before generating the speech.

CONCLUSION:
This TTS conversion application is highly customizable, offering users flexibility in terms of language, voice, and speech speed. It serves as a useful tool for various scenarios such as accessibility applications, language learning, or just for fun.

OUTPUT:

![image](https://github.com/user-attachments/assets/7edf59a6-142f-4f70-bad3-2a1fdf2826b0)





