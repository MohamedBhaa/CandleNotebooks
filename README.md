# Machine Learning used in CandleApp

The machine learning model that are responsible for recognizing users' voice and convert the text to audio.

The datasets used for training are LJSpeech, SpeechRecognition, CTC Sequence Modeling and DeepSpeech 2

The platform used for training is Google Colab with TPU accelerators

Framework used for implementing the model and constructing the Neural Network Tensorflow with Kiras API

- Speech to Text model: This model is responsible for converting users' voice queries into text to use the result as a search query to download pdf books from the web.
  > Technologies that used in this model to create the neural network and train it on some of audio datasets that include transcripts are TensorFlow with Kiras API.
  > JIWER library was used to evaluate the model using WER (Word Error Rate).
- Text to Speech model: This model is resbonsible for converting the content of books from text to audio format.
  > Framework used in this model is TensorFlow_TTS which is built on TensorFlow that tuned to handle text to speech tasks specifically.
  > The Language models used in this model are melgan and FastSpeech 2.
