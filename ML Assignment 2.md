1. What is the concept of human learning? Please give two examples.

To define learning, it is necessary to analyze what happens to the individual. For example, an individual's way of perceiving, thinking, feeling, and doing may change as a result of a learning experience. Thus, learning can be defined as a change in behavior as a result of experience.

2. What different forms of human learning are there? Are there any machine learning equivalents?

Learning type 1: auditive learning (“by listening and speaking“), Learning type 2: visual learning (“through the eyes, by watching”), • Learning type 3: haptic learning (“by touching and feeling”), • Learning type 4: learning through the intellect.

There are three main approaches to machine learning: supervised, unsupervised, and reinforcement learning. There are also hybrid approaches including semi-supervised learning, which can be tailored to the problem a researcher is seeking to solve.

3. What is machine learning, and how does it work? What are the key responsibilities of machine learning?

Machine learning (ML) is a branch of artificial intelligence (AI) and computer science that focuses on the using data and algorithms to enable AI to imitate the way that humans learn, gradually improving its accuracy.

Key responsibilities will involve designing and constructing sophisticated machine learning models, as well as refining and updating existing systems.

4. Define the terms "penalty" and "reward" in the context of reinforcement learning.

This type of machine learning uses a reward-penalty method to teach an AI system. If it makes the right move, it gets rewarded. If it makes a mistake, it receives a penalty. In other words, reinforcement learning forces a system to learn and adapt quickly, or it otherwise loses serious numerical rewards.

5. Explain the term "learning as a search"?

We can think of concept learning as a search problem. The learner searches through a space of hypotheses (we will explain what they are), to find the best one.The best one would be the one that fits the training examples the best.

6. What are the various goals of machine learning? What is the relationship between these and human learning?

The goal of machine learning, closely coupled with the goal of AI, is to achieve a thorough understanding about the nature of learning process (both human learning and other forms of learning), about the computational aspects of learning behaviors, and to implant the learning capability in computer systems.

machine learning, which teaches computers to act in ways they are not explicitly programmed to perform, cannot replace human learning. It is proven that machine based knowledge far exceeds the capacity of the human brain as far as memorizing knowledge, understanding and comprehending are concerned.

7. Illustrate the various elements of machine learning using a real-life illustration.

1 Image Recognition:
Image recognition is a well-known and widespread example of machine learning in the real world. It can identify an object as a digital image, based on the intensity of the pixels in black and white images or colour images.

Real-world examples of image recognition:

Label an x-ray as cancerous or not
Assign a name to a photographed face (aka “tagging” on social media)
Recognise handwriting by segmenting a single letter into smaller images
Machine learning is also frequently used for facial recognition within an image. Using a database of people, the system can identify commonalities and match them to faces. This is often used in law enforcement.

2 Speech Recognition:
Machine learning can translate speech into text. Certain software applications can convert live voice and recorded speech into a text file. The speech can be segmented by intensities on time-frequency bands as well.

Real-world examples of speech recognition:

Voice search
Voice dialling
Appliance control
Some of the most common uses of speech recognition software are devices like Google Home or Amazon Alexa.

3. Medical Diagnosis:
Machine learning can help with the diagnosis of diseases. Many physicians use chatbots with speech recognition capabilities to discern patterns in symptoms.

Real-world examples for medical diagnosis:

Assisting in formulating a diagnosis or recommending a treatment option
Oncology and pathology use machine learning to recognise cancerous tissue
Analyse bodily fluids
In the case of rare diseases, the joint use of facial recognition software and machine learning helps scan patient photos and identify phenotypes that correlate with rare genetic diseases.

8. Provide an example of the abstraction method.

 Making coffee with a coffee machine is a good example of abstraction. You need to know how to use your coffee machine to make coffee. You need to provide water and coffee beans, switch it on and select the kind of coffee you want to get.

9. What is the concept of generalization? What function does it play in the machine learning process?

Generalization refers to your model's ability to adapt properly to new, previously unseen data, drawn from the same distribution as the one used to create the model. Develop intuition about overfitting. Determine whether a model is good or not. Divide a data set into a training set and a test set.

When we train a model on a dataset, and the model is provided with new data absent from the trained set, it may perform well. Such a model is generalizable.

10. What is classification, exactly? What are the main distinctions between classification and regression?

Classification is a supervised machine learning method where the model tries to predict the correct label of a given input data. In classification, the model is fully trained using the training data, and then it is evaluated on test data before being used to perform prediction on new unseen data.

The key distinction between Classification vs Regression algorithms is Regression algorithms are used to determine continuous values such as price, income, age, etc. and Classification algorithms are used to forecast or classify the distinct values such as Real or False, Male or Female, Spam or Not Spam, etc.

11. What is regression, and how does it work? Give an example of a real-world problem that was solved using regression.

A regression is a statistical technique that relates a dependent variable to one or more independent (explanatory) variables. A regression model is able to show whether changes observed in the dependent variable are associated with changes in one or more of the explanatory variables.

Regression has a wide range of real-life applications. It is essential for any machine learning problem that involves continuous numbers – this includes, but is not limited to, a host of examples, including: Financial forecasting (like house price estimates, or stock prices) Sales and promotions forecasting.

12. Describe the clustering mechanism in detail.

Clustering is the task of dividing the unlabeled data or data points into different clusters such that similar data points fall in the same cluster than those which differ from the others. In simple words, the aim of the clustering process is to segregate groups with similar traits and assign them into clusters.

13. Make brief observations on two of the following topics:

i. Machine learning algorithms are used
ii. Studying under supervision
iii. Studying without supervision

iv. Reinforcement learning is a form of learning based on positive reinforcement.

ii. Studying under supervision

Supervised learning involves machine learning algorithms that learn under the presence of a supervisor. 

Learning under supervision directly translates to being under guidance and learning from an entity that is in charge of providing feedback through this process. When training a machine, supervised learning refers to a category of methods in which we teach or train a machine learning algorithm using data, while guiding the algorithm model with labels associated with the data. However, it is essential for one to understand algorithm models and which ones should be applied in particular circumstances.

As humans, we consume a lot of information, but often don’t notice these data points. When we see a photo of an animal, for example, we instantly know what the animal is based on our prior experience. But what happens when the learner doesn’t instantly recognize the animal? 

When the learner makes a guess and predicts what the animal might be, we have the opportunity to objectively evaluate if the learner has given a correct answer or not. This is possible because we have the correct labels of input.

From now on, we’ll be referring to the machine learning algorithm as “the model.” Now, if the model gave a correct answer, then there is nothing for us to do. Our job is to correct the model when the output of the model is wrong. If this is the case, we need to make sure that the model makes necessary updates so that the next time a cat image is shown to the model, it can correctly identify the image. 

Examples of Supervised Learning
Example: House prices

One practical example of supervised learning problems is predicting house prices. How is this achieved?

First, we need data about the houses: square footage, number of rooms, features, whether a house has a garden or not, and so on. We then need to know the prices of these houses, i.e. the corresponding labels. By leveraging data coming from thousands of houses, their features and prices, we can now train a supervised machine learning model to predict a new house’s price based on the examples observed by the model. 

Example: Is it a cat or a dog?

Image classification is a popular problem in the computer vision field. Here, the goal is to predict what class an image belongs to. In this set of problems, we are interested in finding the class label of an image. More precisely: is the image of a car or a plane? A cat or a dog?



iii. Studying without supervision

In unsupervised learning, we lack this kind of signal. Therefore, we need to find our way without any supervision or guidance. This simply means that we are alone and need to figure out what is what by ourselves. 

However, we are not totally in the dark. We do this kind of learning every day. In unsupervised learning, even though we do not have any labels for data points, we do have the actual data points. This means we can draw references from observations in the input data. 

Imagine you are in a foreign country and you are visiting a food market, for example. You see a stall selling a fruit that you cannot identify. You don’t know the name of this fruit. However, you have your observations to rely on, and you can use these as a reference. In this case, you can easily the fruit apart from nearby vegetables or other food by identifying its various features like its shape, color, or size.

This is roughly how unsupervised learning happens. We use the data points as references to find meaningful structure and patterns in the observations. Unsupervised learning is commonly used for finding meaningful patterns and groupings inherent in data, extracting generative features, and exploratory purposes.

Examples of Unsupervised Learning
Example: Finding customer segments

Clustering is an unsupervised technique where the goal is to find natural groups or clusters in a feature space and interpret the input data. There are many different clustering algorithms in the field of data science. One common approach is to divide the data points in a way that each data point falls into a group that is similar to other data points in the same group based on a predefined similarity or distance metric in the feature space.

Clustering is commonly used for determining customer segments in marketing data. Being able to determine different segments of customers helps marketing teams approach these customer segments in unique ways. (Think of features like gender, location, age, education, income bracket, and so on.)

Example: Reducing the complexity of a problem

Dimensionality reduction is a commonly used unsupervised learning technique where the goal is to reduce the number of random variables under consideration. It has several practical applications. One of the most common uses of dimensionality reduction is to reduce the complexity of a problem by projecting the feature space to a lower-dimensional space so that less correlated variables are considered in a machine learning system. 

The most common approaches used in dimensionality reduction are PCA, t-SNE, and UMAP algorithms. They are especially useful for reducing the complexity of a problem and also visualizing the data instances in a better way. Before going into more detail about feature projection, let’s look at another important concept in machine learning: feature selection.
