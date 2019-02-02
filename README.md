# Music-Classification
Classifies music into six different genres by use of neural network

## How it Works
First run CreateSpectrograms.ipynb to create the spectrogram images that will be passed through the neural network. This program will require the Librosa libaray that can be downloaded here https://librosa.github.io/librosa/install.html or with a simple "pip install librosa".

Next you have the choice of classifying the images via the neural network I have created or with the Inception V3 neural network developed by Google. Can you guess which one gets better results? The neural network I created is called MyNN.ipynb and uses the Keras library to make a sequential model that I then added convolution and pooling layers to. This network usually acheives an accuracy around 35-40%. To run the Inception network first run the retrain.ipynb file which will train the network and create the necessary bottlenecks. Then run test.ipynb to run the network against the test set. I have added some variables on to this program to keep track of values such as precision and recall which can be seen at the bottom.
