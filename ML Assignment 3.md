1. Explain the term machine learning, and how does it work? Explain two machine learning applications in the business world. What are some of the ethical concerns that machine learning applications could raise?

Machine learning (ML) is a branch of artificial intelligence (AI) and computer science that focuses on the using data and algorithms to enable AI to imitate the way that humans learn, gradually improving its accuracy.

How does machine learning work?
Machine learning algorithm  has been break into three main parts.

A Decision Process: In general, machine learning algorithms are used to make a prediction or classification. Based on some input data, which can be labeled or unlabeled, your algorithm will produce an estimate about a pattern in the data.
An Error Function: An error function evaluates the prediction of the model. If there are known examples, an error function can make a comparison to assess the accuracy of the model.
A Model Optimization Process: If the model can fit better to the data points in the training set, then weights are adjusted to reduce the discrepancy between the known example and the model estimate. The algorithm will repeat this iterative “evaluate and optimize” process, updating weights autonomously until a threshold of accuracy has been met. 

Two ML applications:
Predicting customer churn
Machine learning can help companies understand the different costs for acquiring versus retaining existing customers, and how to calculate customer lifetime value, which is the average revenue that a customer generates before they churn.

Personalizing products for customers
Companies looking to better understand and serve their customers’ various habits and needs can use ML for customer segmentation and personalization.

General ethical issues in Machine Learning
1. Accuracy- The accuracy of an ML model is the proportion of examples for which it generates a correct output.
2. Bias.
3. Fairness.
4. Safety & Security.
5. Privacy.
6. Transparency.
7. Accountability.
8. Human Control and Decision-making.

2. Describe the process of human learning:
i. Under the supervision of experts

ii. With the assistance of experts in an indirect manner

iii. Self-education

i. Under the supervision of experts

Human-guided machine learning is a type of supervised learning, which uses a set of human-labeled training data to develop a model. In supervised learning, the algorithm learns a set of inputs along with corresponding correct outputs. The training data used to create a machine learning model is assumed to be ground truth, meaning that its validity is not questioned–however, the model must still be tested for accuracy before it can be deployed. There are also subsets of supervised learning known as active learning, or semi-supervised learning, where the machine learning model is improved with each additional correction or piece of information collected. This is where humans come in.

ii. With the assistance of experts in an indirect manner

Indirect learning refers to inferences drawn from the data.


iii. Self-education

self-learning models are AI models that, once deployed, can be optimised by training them on data that becomes more available over time.


3. Provide a few examples of various types of machine learning.

Facial recognition.

Product recommendations.

Email automation and spam filtering.

Financial accuracy.

Social media optimization.

Healthcare advancement.

Mobile voice to text and predictive text.

Predictive analytics.

4. Examine the various forms of machine learning.

Some of the main types of machine learning algorithms are as follows:

1. Supervised Machine Learning
2. Unsupervised Machine Learning
3. Semi-Supervised Machine Learning
4. Reinforcement Learning

1. Supervised Machine Learning
Supervised learning is defined as when a model gets trained on a “Labelled Dataset”. Labelled datasets have both input and output parameters. In Supervised Learning algorithms learn to map points between inputs and correct outputs. It has both training and validation datasets labelled.

2. Unsupervised Machine Learning
Unsupervised Learning Unsupervised learning is a type of machine learning technique in which an algorithm discovers patterns and relationships using unlabeled data. Unlike supervised learning, unsupervised learning doesn’t involve providing the algorithm with labeled target outputs. The primary goal of Unsupervised learning is often to discover hidden patterns, similarities, or clusters within the data, which can then be used for various purposes, such as data exploration, visualization, dimensionality reduction, and more.

3. Semi-Supervised Learning
Semi-Supervised learning is a machine learning algorithm that works between the supervised and unsupervised learning so it uses both labelled and unlabelled data. It’s particularly useful when obtaining labeled data is costly, time-consuming, or resource-intensive. This approach is useful when the dataset is expensive and time-consuming. Semi-supervised learning is chosen when labeled data requires skills and relevant resources in order to train or learn from it.

We use these techniques when we are dealing with data that is a little bit labeled and the rest large portion of it is unlabeled. We can use the unsupervised techniques to predict labels and then feed these labels to supervised techniques. This technique is mostly applicable in the case of image data sets where usually all images are not labeled. 

4. Reinforcement Machine Learning
Reinforcement machine learning algorithm is a learning method that interacts with the environment by producing actions and discovering errors. Trial, error, and delay are the most relevant characteristics of reinforcement learning. In this technique, the model keeps on increasing its performance using Reward Feedback to learn the behavior or pattern. These algorithms are specific to a particular problem e.g. Google Self Driving car, AlphaGo where a bot competes with humans and even itself to get better and better performers in Go Game. Each time we feed in data, they learn and add the data to their knowledge which is training data. So, the more it learns the better it gets trained and hence experienced. 

5. Can you explain what a well-posed learning problem is? Explain the main characteristics that must be present to identify a learning problem properly.

Well Posed Learning Problem – A computer program is said to learn from experience E in context to some task T and some performance measure P, if its performance on T, as was measured by P, upgrades with experience E. 

Any problem can be segregated as well-posed learning problem if it has three traits – 

Task
Performance Measure 
Experience 

Example:
Face Recognition Problem

Task – predicting different types of faces
Performance Measure – able to predict maximum types of faces
Experience – training machine with maximum amount of datasets of different face images

6. Is machine learning capable of solving all problems? Give a detailed explanation of your answer.

While machine learning is a powerful tool for solving problems, improving business operations and automating tasks, it's also a complex and challenging technology, requiring deep expertise and significant resources. Choosing the right algorithm for a task calls for a strong grasp of mathematics and statistics.

7. What are the various methods and technologies for solving machine learning problems? Any two of them should be defined in detail.

There are two main methods to guide your machine learning model—supervised and unsupervised learning. Depending on what data is available and what question is asked, the algorithm will be trained to generate an outcome using one of these methods.

There are four types of machine learning algorithms: supervised, semi-supervised, unsupervised and reinforcement.

Tools: TensorFlow,PyTorch,BigML, Scikit-learn,Colab,Keras,Project Jupyter,Apache Spark

Supervised ML:
Supervised learning, as the name indicates, has the presence of a supervisor as a teacher. Supervised learning is when we teach or train the machine using data that is well-labelled. Which means some data is already tagged with the correct answer. After that, the machine is provided with a new set of examples(data) so that the supervised learning algorithm analyses the training data(set of training examples) and produces a correct outcome from labeled data.

For example, a labeled dataset of images of Elephant, Camel and Cow would have each image tagged with either “Elephant” , “Camel”or “Cow.”

Key Points:

Supervised learning involves training a machine from labeled data.
Labeled data consists of examples with the correct answer or classification.
The machine learns the relationship between inputs (fruit images) and outputs (fruit labels).
The trained machine can then make predictions on new, unlabeled data.

Unsupervised learning:
Unsupervised learning is a type of machine learning that learns from unlabeled data. This means that the data does not have any pre-existing labels or categories. The goal of unsupervised learning is to discover patterns and relationships in the data without any explicit guidance.

Unsupervised learning is the training of a machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance. Here the task of the machine is to group unsorted information according to similarities, patterns, and differences without any prior training of data. 

Unlike supervised learning, no teacher is provided that means no training will be given to the machine. Therefore the machine is restricted to find the hidden structure in unlabeled data by itself. 

You can use unsupervised learning to examine the animal data that has been gathered and distinguish between several groups according to the traits and actions of the animals. These groupings might correspond to various animal species, providing you to categorize the creatures without depending on labels that already exist.

Key Points

Unsupervised learning allows the model to discover patterns and relationships in unlabeled data.
Clustering algorithms group similar data points together based on their inherent characteristics.
Feature extraction captures essential information from the data, enabling the model to make meaningful distinctions.
Label association assigns categories to the clusters based on the extracted patterns and characteristics.



8. Can you explain the various forms of supervised learning? Explain each one with an example application.

Types of Supervised Learning
Supervised learning is classified into two categories of algorithms: 

Regression: A regression problem is when the output variable is a real value, such as “dollars” or “weight”.
Classification: A classification problem is when the output variable is a category, such as “Red” or “blue” , “disease” or “no disease”.
Supervised learning deals with or learns with “labeled” data. This implies that some data is already tagged with the correct answer.

1- Regression
Regression is a type of supervised learning that is used to predict continuous values, such as house prices, stock prices, or customer churn. Regression algorithms learn a function that maps from the input features to the output value.

Some common regression algorithms include:

Linear Regression
Polynomial Regression
Support Vector Machine Regression
Decision Tree Regression
Random Forest Regression

2- Classification
Classification is a type of supervised learning that is used to predict categorical values, such as whether a customer will churn or not, whether an email is spam or not, or whether a medical image shows a tumor or not. Classification algorithms learn a function that maps from the input features to a probability distribution over the output classes.

Some common classification algorithms include:

Logistic Regression
Support Vector Machines
Decision Trees
Random Forests
Naive Baye

9. What is the difference between supervised and unsupervised learning? With a sample application in each region, explain the differences.

Supervised learning:

Supervised learning algorithms are trained using labeled data.	

Supervised learning model takes direct feedback to check if it is predicting correct output or not.	

Supervised learning model predicts the output.

In supervised learning, input data is provided to the model along with the output.

The goal of supervised learning is to train the model so that it can predict the output when it is given new data.

Supervised learning needs supervision to train the model.

Supervised learning can be categorized in Classification and Regression problems.

Supervised learning can be used for those cases where we know the input as well as corresponding outputs.

Unsupervised learning:

Unsupervised learning algorithms are trained using unlabeled data.

Unsupervised learning model does not take any feedback.

Unsupervised learning model finds the hidden patterns in data.

In unsupervised learning, only input data is provided to the model.

The goal of unsupervised learning is to find the hidden patterns and useful insights from the unknown dataset.

Unsupervised learning does not need any supervision to train the model.

Unsupervised Learning can be classified in Clustering and Associations problems.

Unsupervised learning can be used for those cases where we have only input data and no corresponding output data.

For example, a supervised model might be used to predict flight times based on specific parameters, such as weather conditions, airport traffic, peak flight hours, and more. On the other hand, unsupervised learning is more helpful for discovering new patterns and relationships in raw, unlabeled data.

10. Describe the machine learning process in depth.

a. Make brief notes on any two of the following:

MATLAB is one of the most widely used programming languages.

ii. Deep learning applications in healthcare

iii. Study of the market basket

iv. Linear regression (simple)

ii. Deep learning applications in healthcare

Deep learning is a subset of machine learning that uses multi-layered neural networks, called deep neural networks, to simulate the complex decision-making power of the human brain. Some form of deep learning powers most of the artificial intelligence (AI) in our lives today.

Healthcare data analytics
Deep learning models can analyze electronic health records (EHR) that contain structured and unstructured data, including clinical notes, laboratory test results, diagnosis, and medications at exceptional speeds with the most possible accuracy.

Also, smartphones and wearable devices provide useful information about lifestyle. They have the potential to transform data by using mobile apps to monitor medical risk factors for deep learning models. In 2019, Current Health’s AI wearable device became one of the first AI medical monitoring wearables approved by Food and Drug Administration (FDA) for use at home. This device can measure the pulse, respiration, oxygen saturation, temperature, and mobility of patients.

Mental health chatbots
The use of AI-based mental health apps (including chatbots) such as Happify, Moodkit, Woebot, Wysa is increasing. Some of these chatbots can leverage deep learning models for more realistic conversations with patients. A study by Stanford University shows that an intelligent conversational agent can significantly decrease depression and anxiety symptoms in students and it is an efficient and engaging way to deliver mental health support.

Personalized medical treatments
Deep learning solutions allow healthcare organizations to deliver personalized patient care by analyzing patients’ medical history, symptoms, and tests. Natural language processing (NLP) provides insights from free-text medical information for most relevant medical treatments.

iv. Linear regression (simple)

Simple linear regression is used to estimate the relationship between two quantitative variables. You can use simple linear regression when you want to know:

How strong the relationship is between two variables (e.g., the relationship between rainfall and soil erosion).
The value of the dependent variable at a certain value of the independent variable (e.g., the amount of soil erosion at a certain level of rainfall).
Regression models describe the relationship between variables by fitting a line to the observed data. Linear regression models use a straight line, while logistic and nonlinear regression models use a curved line. Regression allows you to estimate how a dependent variable changes as the independent variable(s) change.

Simple linear regression example
You are a social researcher interested in the relationship between income and happiness. You survey 500 people whose incomes range from 15k to 75k and ask them to rank their happiness on a scale from 1 to 10.
Your independent variable (income) and dependent variable (happiness) are both quantitative, so you can do a regression analysis to see if there is a linear relationship between them.

11. Make a comparison between:-

  1. Generalization and abstraction

  2. Learning that is guided and unsupervised

  3. Regression and classification


1. Generalization and abstraction

Abstraction is the skill of understanding the world by thinking about the characteristics that things possess rather than those things themselves. Generalization is the application of abstract characteristics to an entire class of things. Generalization allows us to make broad claims about the natural world.

2. Learning that is guided and unsupervised

Supervised learning thrives on labeled data to make accurate predictions, while unsupervised learning explores the uncharted territories of data patterns. Understanding their differences and applications will empower you to choose the appropriate approach for your use case.

3. Regression and classification

Classification

In this problem statement, the target variables are discrete.

Problems like Spam Email Classification, Disease prediction like problems are solved using Classification Algorithms.	

In this algorithm, we try to find the best possible decision boundary which can separate the two classes with the maximum possible separation.	

Regression:
In this problem statement, the target variables are continuous.

Problems like House Price Prediction, Rainfall Prediction like problems are solved using regression Algorithms.

In this algorithm, we try to find the best-fit line which can represent the overall trend in the data.
