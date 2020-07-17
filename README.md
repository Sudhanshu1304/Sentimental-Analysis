# *NATURAL LANGUAGE PROCESSING*

<br/>
<br/>

>USING  TensorFlow ,Recurrent Neural Network (RNN) and Word Embedding Model

### Purpose Of This Repository

<br/>

This Model is Trained To understand the Emotion behind any Sentence .
Basically this  Model Understand Reviews given by the Customers of a 
Restaurant and Classify them as Positive or Negative Vote.
<br/> 
<br/>

### Working Of The Model 
<br/>

-  Being a Supervised Learning Problem We provide it with a labeled Dataset 
from Restaurant_Reviews.tsv.
- At First we do the Prepossessing of the Text data and Convert it into Machines Understandable Language

- Here We are using Embedding -

<br/>

> In Layman's terms *Embeddings* Basically Refers to a process by which we train meahine to learn 
> Understand the Meaning of Words As Humans do and Not just as Numbers.

- For these whole process I have Used the **RNN** Model together with **LSTM** .
- LSTM are Best For Training Sequential Dependent Data .

>### **RESULT**
<br/>
Here  I have Tested the Model on Custom made Sentences.
<br/>
<br/>

![](Annotation%202020-07-17%20193800.png)

<br/>

Here The Only the *6'th*  Sentence Is Interpreted Wrong,and Everyone is Coorect
Which shows that the Model Work's very well.