# Chatbot-with-deep-learning

## Implementation

* Read the description of the movie from the dataset.
* Convert the CSV into JSON.
* Collect intents require to train the model.
* Separate the pattern and response based on the data collected.
* Use tokenization that will grab the words from the sentence.
* create a bag of words that will represent an any given pattern(inputs).
* The neural network only understand numeric value rather than a word that's we need to convert them into numeric encoding.
* we create 1 hot encoding which will contain the 1 or 0 based on the word exist or not in the sentence.
* activation=softmax tells the probability of each neuron in the list (helps to finds the response).
* 8 fully connected hidden layer.
* Train the model using a changing number of epoch and batch sizes.
* Input the text and output will be a response based on the prediction and also the genre of the movie.

## Architecture

<div align="center" style="height:400px">
    <a href="https://towardsdatascience.com/word2vec-skip-gram-model-part-1-intuition-78614e4d6e0b"><img src='./assets/2.png'></a>
</div>



**INPUT DATA** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :arrow_right: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **HIDDEN LAYER** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:arrow_right:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **HIDDEN LAYER** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:arrow_right: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**OUTPUT DATA** <br> 
**45** input neurons &nbsp;&nbsp;&nbsp;&nbsp;:arrow_right:&nbsp;&nbsp;&nbsp;&nbsp; **8** fully connected neurons &nbsp;&nbsp;&nbsp;&nbsp;:arrow_right:&nbsp;&nbsp;&nbsp;&nbsp; **8** fully connected neurons &nbsp;&nbsp;&nbsp;&nbsp;:arrow_right: &nbsp;&nbsp;&nbsp;&nbsp;**6** neurons ("Softmax"). 

## Requirements

Install python package required is present [Here](https://gist.github.com/hritik5102/569333e9f89b9377315e33c2d2a7217d)

## Output 

<div align="center" style="height:400px">
    <img src='./assets/3.JPG'>
</div>

<br>
I know the responses which I trained is so weird 😜 .

## LICENSE
Licensed under the [MIT License](LICENSE) 