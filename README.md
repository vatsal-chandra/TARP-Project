# Speech-to-Sign-language-Translator
**An application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.**
- Front-end using EasyGui.
- Speech as input through microphone using PyAudio. 
- Speech recognition using Google Speech API and Sphix(for offline use).
- Text Preprocessing using NLP.
- Dictionary based Machine Translation.

## Algorithm
Audio to Sign Language Translator
1. Start
2. Getting the Speech
   1. Listen for 1 second and calibrate the energy threshold for ambient noise
levels.
   2. Listen the Speech using Microphone.
Now the energy threshold is already set to a good value, and we can
reliably catch speech right away.
3. Recognise the Speech.
4. Convert Speech to Text.
   1. Make the Text to lowercase for further manipulation.
5. Detected Text
   1. If “goodbye” then exit.
   2.Else if Detected Text in predefined Dictionary Words. Display
respective GIFs of the Phrase.
   3. Else Count the Letters of the Word/Phrase.
      1. Display the Visual of the phrase with some delay of Actions.
   4. Continue all the steps from Step 3, and continue till the Speech Ends.
6. If Error in Step 2, That is if no Speech Detected then display error message
“Could not listen”.

**Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these specially abled people, creating a communication gap. Thus the Audio to Sign Language converter is important and significant because it helps in providing information access and services to deaf people in Indian sign language and develops a scalable project which can be extended to capture whole vocabulary of ISL through manual and non-manual signs. It also can be developed as a desktop or mobile application to enable specially abled people to communicate easily and effectively with others.**
