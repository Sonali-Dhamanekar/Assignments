# ML ASSIGNMENT 1

1. What does one mean by the term "machine learning"?

ML typically stands for "Machine Learning." Machine Learning is asubset of artificial intelligence (AI) that focuses on developingalgorithms and models that enable computers to learn from dataand make predictions or decisions without being explicitlyprogrammed for a specific task. The goal of machine learning is toallow computers to identify patterns, learn from experiences, andimprove their performance over time.The performance will rise inproportion to the quantity of information we provide.



2. Can you think of 4 distinct types of issues where it shines?

Machine learning algorithms shines on problems such has spam detection in email, cancer diagnosis, fraudulent credit card transactions, and automatically driving vehicles.

3. What is a labeled training set, and how does it work?

A labeled training set is a collection of input data samples, where each sample is associated with one or more output labels that serve as the ground truth for the problem at hand.

4. What are the two most important tasks that are supervised?

The two most common tasks in supervised learning are classification and regression

5. Can you think of four examples of unsupervised tasks?

Four common unsupervised tasks inclused clustering, visualization, dimensionality reduction , and association rule learning.

6. State the machine learning model that would be best to make a robot walk through various unfamiliar terrains?

The best Machine Learning algorithm to allow a robot to walk in unknown terrain is Reinforced Learning, where the robot can learn from response of the terrain to optimize itself.

7. Which algorithm will you use to divide your customers into different groups?

The goal of cluster analysis in marketing is to accurately segment customers in order to achieve more effective customer marketing via personalization. A common cluster analysis method is a mathematical algorithm known as k-means cluster analysis, sometimes referred to as scientific segmentation.

8. Will you consider the problem of spam detection to be a supervised or unsupervised learning problem?

Spam detection is a supervised learning problem because the labels are known (spam or no spam).

9. What is the concept of an online learning system?

Online Learning (sometimes also referred to as Distance Learning or Distance Education) is education that delivers instruction to students who are separated from the instructor or instructors, and that supports regular and substantive interaction between students and instructor(s) either synchronously (students are required to log in and participate in class at a specified time each week) or asynchronously (online learning that allows students to view instructional materials each week at any time). Technologies used for instruction may include the following: Internet; one-way and two-way transmissions through open broadcasts, closed circuit, cable, microwave, broadband lines, fiber optics, satellite, or wireless communication devices; audio conferencing; and video cassette, DVDs and CD-ROMS, if the cassette, DVDs, and CD-ROMs are used in a course in conjunction with the technologies listed above.


10. What is out-of-core learning, and how does it differ from core learning?

Out-of-core learning refers to a set of algorithms designed to handle data that exceeds the capacity of a machine's primary memory (RAM). These algorithms work by reading small mini-batches of data from the disk, processing them, and then discarding them to free up memory for the next batch.

“It is a way to train your model on data that cannot fit your core memory.” Out-of-core learning refers to the machine learning algorithms working with data that cannot fit into a single machine's memory but can easily fit into some data storage, such as a local hard disk or web repository.

11. What kind of learning algorithm makes predictions using a similarity measure?

instance-based algorithm
Learning algorithm that relies on a similarity measure to make predictions is instance-based algorithm.

12. Whats the difference between a model parameter and a hyperparameter in a learning algorithm?

Model parameters are internal to the model and estimated from data automatically, whereas Hyperparameters are set manually and are used in the optimization of the model and help in estimating the model parameters.

13. What are the criteria that model-based learning algorithms look for? What is the most popular method they use to achieve success? What method do they use to make predictions?

The goal for a model-based algorithm is to be able to generalize to new examples. To do this, model based algorithms search for optimal values for the model's parameters, often called theta . This searching, or "learning", is what machine learning is all about.

There are two main methods to guide your machine learning model—supervised and unsupervised learning. Depending on what data is available and what question is asked, the algorithm will be trained to generate an outcome using one of these methods.

Model based learning algorithm search for the optimal value of parameters in a model that will give the best results for the new instances. We often use a cost function or similar to determine what the parameter value has to be in order to minimize the function.

14. Can you name four of the most important Machine Learning challenges?

Four main challenges in Machine Learning include overfitting the data (using a model too complicated), underfitting the data (using a simple model), lacking in data and nonrepresentative data.

15. What happens if the model performs well on the training data but fails to generalize the results to new situations? Can you think of three different options?

Model is overfitting your training data when you see that the model performs well on the training data but does not perform well on the evaluation data. This is because the model is memorizing the data it has seen and is unable to generalize to unseen examples.n other words, the model learned patterns specific to the training data, which are irrelevant in other data.

We can identify overfitting by looking at validation metrics, like loss or accuracy.

There are several manners in which we can reduce overfitting in deep learning models. The best option is to get more training data. Unfortunately, in real-world situations, you often do not have this possibility due to time, budget or technical constraints.

Another way to reduce overfitting is to lower the capacity of the model to memorize the training data. As such, the model will need to focus on the relevant patterns in the training data, which results in better generalization.


16. What exactly is a test set, and why would you need one?

Test set—a subset used to put the trained model to the test
Your goal is to develop a model that generalizes well to new data, assuming your test set fits the two constraints mentioned above. Our test set acts as a stand-in for new information. Let's say that the model learned for the training data is really basic.

17. What is a validation set's purpose?

The validation set uses a subset of the training data to provide an unbiased evaluation of a model. The validation data set contrasts with training and test sets in that it is an intermediate phase used for choosing the best model and optimizing it. It is in this phase that hyperparameter tuning occurs.


18. What precisely is the train-dev kit, when will you need it, how do you put it to use?

The Training set is used for training. The Dev set (often called “validation set”) is used for adjusting the model. The Test set is a final check of your completed model. If you don't have these three tasks using separate sets of data, you will have overfitting and not make good predictions on new data.

The goal of dev-set is to rank the models in term of their accuracy and helps us decide which model to proceed further with. Using Dev set we rank all our models in terms of their accuracy and pick the best performing model. i.e. dev set ranks models similar to a search engine like google rank pages and then pick the top model and hence act as a filter to remove bad models.

Choices of parameters are made by learning algorithm and choice of model is made by us by intentionally picking the best model performing well on dev-set.

So when you have successfully consumed train and dev set while building a machine learning system you are left with the final best model out of all the ideas you tried.

Once the final model is available we need to be confident about the fact if this is a good model or not or how much accuracy we can expect it once we deploy it in the real world. We use test-set as a proxy for unseen data and evaluate our model on test-set.

19. What could go wrong if you use the test set to tune hyperparameters?

Selection bias can result in poor generalization performance, as the model may not be able to perform well on new data that is different from the test set. Limited Data: The test set is usually a small subset of the overall data, and using it for hyperparameter tuning can result in overfitting due to limited data.
