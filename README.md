# OCRN
Optical Character recognition based on Neural network
The objective of this work is to convert printed text or handwritten characters recorded offline using either scanning equipment or cameras into a machine-usable text by simulating a neural network so that it would improve the process of collecting and storing data by human workers. Another goal is to provide an alternate, better and faster algorithm with higher accuracy to recognize the characters. In this context, we choose artificial neural network and make it much more tolerant to anomalies in the recorded image or data. Common optical character recognition tasks involve identifying simple edge detection and matching them with predefined patterns. In this research, characters are recognized even when noise such as inclination and skewedness presents, by training the network to look for discrepancies in data and relate them using vocabulary, grammar and common recurrences that may occur after a character. Images are also masked in multiple ways and processed individually to increase the confidence level of prediction.

How to run :

Note:unzip testdata and traindata 

<b>python main.py</b>
 <br>
<b>
1.You can train the neural network.<br>
2. You can test neural net with test data.<br>
3. You need to give path of image -> data/testdata/(image neme)</b>


