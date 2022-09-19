# MachineLearning

You’re trying to teach a child what an apple is so you show them pictures of different types of red apples every day for 6 days. By the end of the 7th day, they will be able to judge whether a fruit is an apple or not. This is the same sort of process used in Machine Learning (ML). Machine Learning is a branch of Artificial Intelligence where algorithms learn patterns in data.
 
Machine learning is the process by which algorithms study and “learn” from past experiences. These experiences come in the form of data sets ranging from millions to billions of unique data points. Algorithms use computationally heavy methods to learn information from datasets to create predictive models.
 
There are 3 types of ML techniques: supervised learning, unsupervised learning, and reinforcement learning. Supervised machine algorithms develop predictive models based on labelled input and output data. Unsupervised machine learning algorithms do not get labelled data instead learn from patterns within the data. Reinforcement learning is different from the other two techniques because in this approach an “intelligent agent” (the algorithm) takes actions to maximize rewards earned hence getting the most optimal solution. Any of these methods can be used in machine learning, it depends on the question being asked.
 
There are many examples of ML in everyday life such as tagging fraudulent bank transactions, self-driving cars, recommendation systems, and handwriting recognition software are some of them. Self-driving cars are an example of reinforcement learning whereas, all the others are examples can use either  supervised or unsupervised learning.
 
Machine Learning is as close as we can get to magic but it comes with its challenges. There are numerous things to consider when taking on an ML project such as but not limited to: is there enough data, is the data of high quality, does the data represent all facets of the given problem, and what sort of statistical analysis should be performed?
 
Let’s take handwriting recognition software as an example. How do we get a data set of millions of handwritten digit examples in different styles and pen strokes? If this was new research we would have to take time and build our own database however, due to the time and effort other people have put into this project we actually have good datasets available for use online including this one on Kaggle.com.
 
If the data set is too small the algorithm won’t learn enough information, if it’s too big then it will learn too much and be too specific with its predictions. Say our dataset consists of photos of numbers 0-9 and letters A-Z as the following:

<img width="332" alt="image" src="https://user-images.githubusercontent.com/73089638/190937615-36144561-b66c-4c2f-92fd-0a90a2ed8e78.png">

Now let's say that the algorithm learned what an an S and the number 5 look like from only the following two images:

<img width="275" alt="image" src="https://user-images.githubusercontent.com/73089638/190937711-7a42c179-7489-4f14-a6b9-527ee1742264.png">

<img width="177" alt="image" src="https://user-images.githubusercontent.com/73089638/190937714-ac5460b4-b185-4bd8-bd82-711ef22c8138.png">


What would the algorithm predict the following to be, an S or the number 5?

<img width="53" alt="image" src="https://user-images.githubusercontent.com/73089638/190937744-d73923a4-399a-4584-ba42-826a6df9c591.png">


It could go either way but it would most likely predict that to be the number 5 but in fact it is an S.

<img width="30" alt="image" src="https://user-images.githubusercontent.com/73089638/190937817-ad9d7307-d074-40a9-adc6-3949f22e3f14.png">


This is why the size and quality of data we collect matters. We want a data set large enough that we recognize a wide range of the number 5 so that the algorithm doesn’t get confused between the number 5 and the letter S. 

We also want to consider all the possible statistical analyses we can perform on our algorithm. Some of the most common analyses are accuracy, precision, F1 score and recall score. One may give more information than the others depending on the problem and the question but all can and should be used in conjunction with each other for a clearer picture of how well the algorithm is performing. 
 
Machine Learning is teaching computers to think. If we can do that successfully then we can solve problems that up until now are still unsolvable. DeepMind is using techniques in Machine Learning and Artificial Intelligence to perhaps solve the Protein Folding problem which is considered an NP-Hard problem. The better we get at collecting data and training models, the closer we get to solving problems that have been unsolvable until now.  



















