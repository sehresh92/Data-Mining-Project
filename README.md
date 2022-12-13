# Data-Mining-Project

TOPIC: ARTIFICIAL INTELLIGENCE AND BUSINESS INTELLIGENCE PROJECT (Data Mining)

Introduction:

Data mining, sometimes referred to as knowledge discovery, is the method of gathering and analyzing large pre-existing sets of data from different perspectives and then converting it into useful information. It uses mathematical analysis to derive trends and patterns that exist in the accumulated data. Data mining technique has been used over the years to reveal relationship among the fields in database that is almost too complex to find using traditional data exploration method.

What Data Mining Can Do?

Although data mining is still in its infancy, companies in a wide range of industries including retail, finance, health care, manufacturing transportation, and aerospace and are already using data mining tools and techniques to take advantage of historical data. By using pattern recognition technologies and statistical and mathematical techniques to sift through warehoused information, data mining helps analysts recognize significant facts, relationships, trends, patterns, exceptions and anomalies that might otherwise go unnoticed. For businesses, data mining is used to discover patterns and relationships in the data in order to help make better business decisions. 

Data Mining Project Experiment:

For this experiment, we have chosen dataset on “SuperMarket”.
In “SuperMarket” we are examining the sale of Shaving Product. For that we need to figure out how many people have beard? If yes, Do, they shave regularly, weekly, or monthly?

Using various classification operator, I have predicted weekly, monthly sales of “Shaving Product”.

Case link:

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

When working with “Decision Tree”, you need to make sure that your data only contains attribute and label types which are allowed in Decision Tree operator. The Decision Tree operator just accepts Polynomial, Numerical and Binomial attribute and Binomial and Polynomial labels (target attributes). So, if your target data is a numeric variable you may modify it to the accepted type by categorizing it into several intervals and then defining dummy binomial attributes for each interval.

check in the link: 

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/7.jpg

“Subprocess” operator introduces a process within a process. Whenever a Subprocess operator is reached during a process execution, first the entire subprocess is executed. Once the subprocess execution is complete, the flow is returned to the process (the parent process). A subprocess can be considered as a small unit of a process.

“Loop Parameter” operator iterates over its subprocess for all the defined parameter combinations.
After that my “Loop Parameter” is connected with “Subprocess” operator and “Select” operator. The “Select” operator returns the specified single object from the given collection of objects.

check in the link: 

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/8.jpg

In the end connecting two subprocesses with “Branch” operator as it executes only one subprocess at a time depending upon the condition. This operator is similar to the 'if-then-else' statement, where one of the two options is selected depending upon the results of the specified condition.

check in the link: 

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/9.jpg

RESULT:

The results obtained from the above performed experiment are as follows:

Decision Tree – Graphical Representation link:

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/10.jpg

This model describes how to characterize your customers as responders or non- responders.

Plot View link:

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/11.jpg

Learning Curve link:

https://github.com/sehresh92/Data-Mining-Project/blob/main/Project/12.jpg


