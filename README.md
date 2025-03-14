# Next word prediction with Deep Learning

### General goal
The goal of this project is to create deep learning models that predict the next words in a sentence.

Two approaches will be used: LSTM (Long Short Term Memory) RNN (Recurrent Neural Network) and a sequence model with Transformers architecture.

The models will be tailored for the use in completing Haiku poems.

The base textual dataset is the "Haiku Dataset" that can be found at Kaggle at: https://www.kaggle.com/datasets/hjhalani30/haiku-dataset

### Launching the environment

Suggested way to run the project It is suggested to run with docker, using the base image tensorflow/tensorflow:-gpu-jupyter. Adapt the following command:

`sudo docker run --name tensorflow-dev -p 8888:8888 -v {your_repository_dir}:/tf/classification  tensorflow/tensorflow:2.18.0-gpu-jupyter`

Then get the jupyter notebaook link by seeing the container logs:

`sudo docker logs tensorflow --details`

Side note - I had to run the following command the get GPU running:

`python3 -m pip install 'tensorflow[and-cuda]'`


#### Video with main steps for the project

https://www.youtube.com/watch?v=El0klIh6Dg4

#### Small demonstration of the LSTM predicting endings for some lines
![image](https://github.com/user-attachments/assets/4289f8ff-6692-4749-b189-43ee58a7be4d)
