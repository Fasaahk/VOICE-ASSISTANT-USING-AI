Description of Modules and Components


Pyttsx3 -
•	pyttsx3 is a Python library that provides text-to-speech functionality.
•	It's a wrapper around the text-to-speech engine called Microsoft Speech API (SAPI).
 
•	pyttsx3 supports both oﬄine and online (internet-connected) text-to- speech.
•	It's cross-platform and works on Windows, Linux, and macOS operating systems.
•	The library supports a variety of voices and languages, which can be configured through its API.
•	pyttsx3 also provides various features such as changing the rate, pitch, and volume of the speech, and the ability to set callbacks for events such as the start and end of a spoken sentence.
•	It's easy to install using pip, and the library has good documentation and examples to get started quickly.
•	pyttsx3 is open-source and actively maintained, so it's reliable and secure to use.




Speech Recognizer-



•	The speech_recognition module is a Python library that allows developers to easily recognize speech from audio files or live audio input.
•	It supports several popular speech recognition engines, including Google Speech Recognition, Microsoft Bing Voice Recognition, and IBM Speech to Text.
•	The module can handle audio files in various formats, such as WAV, AIFF, FLAC, and MP3.
•	It can also work with audio data from microphones or other audio input devices, making it useful for real-time speech recognition applications.
•	The module provides a simple API for recognizing speech, which involves creating a Recognizer object and calling its recognize_*() methods to perform the recognition.


METHODOLOGY


•	We used the following methodology to develop our voice assistant:
•	Installed pyttsx3 library using pip package manager
•	Defined a function to convert text to speech using pyttsx3
•	Used speech recognition library to capture user voice commands
•	Processed	user	commands	using	regular	expressions	and	if-else statements to determine the appropriate action
•	Integrated	the	voice	assistant	with	external	APIs	such	as OpenWeatherMap and Wikipedia to provide relevant information
