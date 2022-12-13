# Data-Mining-Project

TOPIC: ARTIFICIAL INTELLIGENCE AND BUSINESS INTELLIGENCE PROJECT (Data Mining)

Introduction:

Data mining, sometimes referred to as knowledge discovery, is the method of gathering and analyzing large pre-existing sets of data from different perspectives and then converting it into useful information. It uses mathematical analysis to derive trends and patterns that exist in the accumulated data. Data mining technique has been used over the years to reveal relationship among the fields in database that is almost too complex to find using traditional data exploration method.

What Data Mining Can Do?

Although data mining is still in its infancy, companies in a wide range of industries including retail, finance, health care, manufacturing transportation, and aerospace and are already using data mining tools and techniques to take advantage of historical data. By using pattern recognition technologies and statistical and mathematical techniques to sift through warehoused information, data mining helps analysts recognize significant facts, relationships, trends, patterns, exceptions and anomalies that might otherwise go unnoticed.
For businesses, data mining is used to discover patterns and relationships in the data in order to help make better business decisions. 

HOW DATA MINING WORKS:

How is data mining able to tell you important things that you didn't know or what is going to happen next? That technique that is used to perform these feats is called modeling. Modeling is simply the act of building a model (a set of examples or a mathematical relationship) based on data from situations where the answer is known and then applying the model to other situations where the answers aren't known. Modeling techniques have been around for centuries, of course, but it is only recently that data storage and communication capabilities required to collect and store huge amounts of data, and the computational power to automate modeling techniques to work directly on the data, have been available.

Data Mining Project Experiment:
For this experiment, we have chosen dataset on “SuperMarket”.
In “SuperMarket” we are examining the sale of Shaving Product. For that we need to figure out how many people have beard? If yes, Do, they shave regularly, weekly, or monthly?
Using various classification operator, I have predicted weekly, monthly sales of “Shaving Product”.

Use Case link:

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/1.jpg

I have collected “Shaving Product” dataset for this experiment.

link of “Shaving Product” dataset:

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/2.jpg

First the dataset is fed into the system by importing its CSV file and then drag and drop the dataset in to the process window. Connect the “out” port of the dataset to the “result” port as shown in figure and then press “PLAY” button.

figure link: 

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/3.jpg

The result will be displayed showing the complete dataset. This dataset contains 9 attributes.

dataset contains 9 attributes link:

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/4.jpg

After that I will connect my input with “Multiply” operator which copies its input object to all connected output ports and does not modify the input object. After that “Remove useless attributes” operator is connected which removes useless attributes from an ExampleSet. Then “Filter Examples” operator is connected that filters which examples (i.e. rows) of an ExampleSet should be kept and which examples should be removed.

check in the link: 

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/5.jpg

Now connecting the output of “Multiply” operator with “Subprocess”operator, ”DecisionTree” operator and “Loop parameter” operator.

check in the link: 

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/6.jpg

