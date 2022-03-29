# Siya
Siya is an AI Chatbot which can be implemented to any e-commerce website or can also be used as a chatting bot. <br>
<h2><p align="center">
   Interface of Siya
</p></h2>
<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/93676625/160544848-2583388e-5911-4c5d-ae85-b85e35bb4c1a.png" >
</p>
<h2>Overview</h2><br>
<p>A deep learning sequentail model is used for training the model. The data used in intents.json file has a defined structure on which we train our Sequential model. In training phase, first step was the open and read the dataset, then using tokenizer, we are seprating each word which finally gives us a set of words(set i.e. no defined pattern, words doesn't really make any sense here), finally in training phase, model learns how to map the given patterns to particular 'tags' given in the dataset. Now when we ask any query, the model try n find the tag related to it, then randomly choose the answer belonging to that perticular tag.</p>
<h2>Implementation</h2><br>
<p>All the required files need to be forked from this repo and linked to the target website.</p>
<h2>Sample Responses</h2><br>
<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/93676625/160546691-d78c8c1a-643e-41c8-9346-f836f03cd20a.png" >
</p>
<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/93676625/160547181-eec1af83-78d0-4087-b22a-5d3a14c6085a.png" >
</p>
<p><strong>Note</strong>:  Siya is in working phase</p>
