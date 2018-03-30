# Speech_Recognition


# You can go to your repository and open your terminal
# Then print: python
>>> import speech_recognition as sr
>>> from guessing_game import recognize_speech_from_mic
>>> r = sr.Recognizer()
>>> m = sr.Microphone()
>>> recognize_speech_from_mic(r, m)


# Press Enter and Talk to your PC.
# It will return:
{'success': True, 'error': None, 'transcription': 'THE WORD OR PHRASE THAT YOU'VE TOLD'}

Have fun!
