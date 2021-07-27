# cnn-music-classifier
This is a simple convolutional neural network that helps classify a song's genre. The genres can be jazz, reggae, rock, blues, hip-hop, country, metal, classical, disco, and pop. The user will provide a song, which must be in WAV format. The model will process the audio file, predict the genre, and display the prediction to the user.

## Technologies

* Python
* Flask - provides the framework
* Librosa - processess the audio files
* Tensorflow - used to train and test the model
* Keras - Used to create the model itself
* Heroku - PaaS which hosts the site

## URL for the Application
[CNN-Music-Classifier](https://cnn-music-classifier.herokuapp.com/)

## How to launch the program locally (not recommended)

1. Clone or download this repo locally
2. From the CLI, access the directory where the repo was extracted to
3. Traverse to the `/web` directory of the file
4. Run `pip install -r requirements.text`
5. Run the flask server with `python app.py`
6. Access http://127.0.0.1:5000/ or http://localhost:5000/ from your browser
7. The web application should be up and running!
