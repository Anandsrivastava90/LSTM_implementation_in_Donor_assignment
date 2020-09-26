# LSTM_implementation_in_Donor_assignment
We don't think from  scratch . We always understand the things based on the previous understanding. In our daily life every action is based on the previous  information or experience that we have encountered . As you read this blog . You understand each word based on the understanding of previous words.We don't throw the past information.Sequential information is very important to undertand the context of the text. Let's take an example "Delhi is the capital of the India not USA " We understand the context of the text only when these words are in proper grammatical sequence, Imagine if I jumble the text "Not Delhi capital USA is India the" It doesn't make sense.

#Tradional neural network fails when we have input as sequence of infomations. Suppose we have input as :

Sequence of words 
Time series data 
Machine Translation
Speech Recognization
Image caption
The core idea is when output depends on the sequence of input not the set of inputs then We need to build a new type of the network which retains and leverages the sequence information.RNN addresses that issue.

The core idea is when output depends on the sequence of input not the set of inputs then We need to build a new type of the network which retains and leverages the sequence information.RNN addresses that issue.

Recurrent Neural Network:

Let's understand this with an example , Suppose We have some reviews as text data. Now understand how the recurrent neural network is connected with that text data. Let x1 ,,x2, x3 ,x4,x4 ,x5 are the words in the sentence .Total no. of the words =5 ,When we convert it into one hot encoding .we will get 5th dimensional data. Let w1 = Weight matrix taken randomly it's size is 5 X 5 because in each network there are five neurons and words in our sentence is 5. 

f = Activation function , It might be Tanh,Relu and Sigmoid

w' = Weight matrix associated with the output. Intially there is no output so some random weight matrix we can take

O = Output from the network 
