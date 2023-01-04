# :musical_note: Music Genre Classification

To put into practice the knowledge learned in the univesity course **Deep Learning for AI**, my colleague Fabrizio Niro(@fabrizio-n) and I, decided to try to implement a neural network that was able to recognize the genre of a song that is passed to it as input.

The Dataset that we used is the famous [GTZAN dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification). It contains 1000 audio files, all having length of 30 seconds.

The most common way of performing deep learning on audio data is by the use of convolutional architectures on the spectrograms of audio features. By the way, in this project we are trying to model the data as time dependent sequences, for this reason we will use a RNN(Recurrent Neural Network), in particular a **Gated Recurent Unit(GRU)**.

Below the slides we used to present what we did and the results we achieved.

<img src="https://user-images.githubusercontent.com/109806659/210553365-ea9f974a-268c-48b4-b283-f56e3ea9fa6a.png" width=1000 />

<p float="left">
  <img src="https://user-images.githubusercontent.com/109806659/210553820-9fdc3c50-4ce3-4cb6-bc39-bd609e66486a.png" width="500" />
  <img src="https://user-images.githubusercontent.com/109806659/210553884-793face7-b9d4-44e5-9855-065759fae57a.png" width="500" /> 
</p>

<p float="left">
  <img src="https://user-images.githubusercontent.com/109806659/210554367-7db87760-ad37-4876-b451-278763f775e0.png" width="500" />
  <img src="https://user-images.githubusercontent.com/109806659/210554157-1470c4cd-06ed-4bdd-bbe9-df3326f676d7.png" width="500" /> 
</p>

<p float="left">
  <img src="https://user-images.githubusercontent.com/109806659/210554801-92441099-7410-494b-95b1-2b294727b2c4.png" width="500" />
  <img src="https://user-images.githubusercontent.com/109806659/210554875-5f15b206-cdb7-4521-87f0-fe12a1a0e414.png" width="500" /> 
</p>


<p float="left">
  <img src="https://user-images.githubusercontent.com/109806659/210555241-fbf987e7-96fb-493e-a4d3-368e5c039ad6.png" width="500" />
  <img src="https://user-images.githubusercontent.com/109806659/210555289-41247820-9d39-4306-9907-753e05379ebf.png" width="500" /> 
</p>


<img src="https://user-images.githubusercontent.com/109806659/210558720-2b57876b-5600-47fd-8076-e63ebeefaf2a.png" width=1000 />

