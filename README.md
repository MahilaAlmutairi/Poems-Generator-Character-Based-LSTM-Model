# Poems generator(character based LSTM model)
A model generates Arabic praise poems. It composed of three layers:

•	An embedding layer that takes integers indices and turns them into dense vectors of 256 dimensions.\
•	A LSTM layer with 1024 units.\
•	A dense layer with size outputs equals to vocab size (46 characters). 

### Used Libraries and Technologies:
•	Tensorflow.\
•	Keras.\
•	Numpy.\
•	BLEU scores.\
•	LSTM Neural Network.

### Used Dataset:
The [dataset](https://bit.ly/PraisePoems) was collected from praise poems written by Muslim poets born and lived during different eras and countries. The data consisted of 34,466 verses of praise poems. It has been collected manually from the Diwan website. It was collected by collaborating with my team (Asmaa Hakami & Raneem Alqarni). 

### For more details:
Read our paper [here](https://bit.ly/paper-nlp).
