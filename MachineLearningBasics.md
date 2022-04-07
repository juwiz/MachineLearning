# Machin learning basics
### Supervised learning
 Supervised learning is type of model training where the algorithm gets a dataset that is already labelled, meaning input data also includes its desirable output. Base on that, model is trained untill it finds connections and patterns between input and output and then it's able to produce good enough results on unlabelled data.

  Some examples that are commonly used are spam filter,    
  photo recognition (algorithm is able to differentiate between the shapes of object or in other case, It's also able to distinguish dogs from cats),    
  writing recognition (algorithm is able to transform handwritten text to typewritten text)    

There are to different categories of algorithms that are usually used for SL, Classification and Regression.

##### Classification
Classification algorithms take the training data, observes it and then based on that it groups it into different classes(categories) for example: Yes or No, 0 or 1, Dog or Cat, or it can have multiple classes, depending on the algorithm.    

Specific algorithms used:
  - decision tree
  - K Nearest Neighbours

##### Regression
Regression algorithms examines the relationships of data and how is one sample changes based on another. Those variables that are examined are called dependent (target) and independent (predictor). The target is changing in response to the independent variable, the other independent variables remain unchanged. It can be used in prediction of temperature, age, price...   

Some specific examples:
   - linear regression
   - logistic regression

### Unsupervised learning
Unsupervised learning doesn't have the luxury of getting already labelled dataset so it need to find it own connections in the data based on parameters it gets. Its goal is to find hidden structures, similarities and then output data which is grouped base on that.     

The Unsupervised learning algorithms can be divided into two categories Clustering and Association
##### Clustering    
Clustering, method which groups data points into clusters, in each cluster are always the data points that are the most similar to each other.

  Here is a example:
   - Partitioning Clustering    

##### Association    
Association is looking for the dependency of one data item to another and then it makes connections and maps the results. Its for example used in Market Basket analysis so the retail can make association between different products people buy. That can help with choosing the lay out of the store.

There are examples of algorithms:
   - Apriori
   - Eclat



### Reinforcement learning
Reinforcement learning is, when a system, or *agent*, examines the environment
'around' itself and then with enough observations, it selects the best action based on the its *policy*.
Then, according to how good the choice performed, the system is either *rewarded* or *penalized*.
It learns what the best strategy(policy) is by analysing its actions and learning from them.

It's basically hit or miss situation: When you do it right, then you get rewarded, if you do it wrong,
or not good enough, you need to learn from your mistakes and try something different the next time.
For example, the way robots learned to walk.

Algorithms example:
 - State Action Reward State action
 - Q-learning    


 PS: I'm aware that it's horrible, It's probably pain to even read it and I apologise for that, but this is what I came up with after, well apparently not enough time of research. 
