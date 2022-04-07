# Machin learning basics
### Supervised learning
 Supervised learning is type of model training where the algorithm gets dataset that is already labelled, meaning input data also include there desirable output. Base on that, model is trained 'till it finds connections and patterns between input and output and then its able to products good enough results on unlabelled data.

  Some examples that are commonly used are spam filter,    
  photo recognition (algorithm is able to differentiate between the shapes of object or in other case It's also able to recognize dog from cat, just on data that is given with picture),    
  writing recognition (algorithm is able to transform handwritten text to typewritten text)    

There are to different categories of algorithms that are usually used for SL, Classification and Regression.

##### Classification
Classification algorithm takes the training data, observes it and then base on that it groups it into different classes(categories) for example: Yes or No, 0 or 1, Dog or Cat, or it can have multiple classes, depends on the algorithm.    

Specific algorithms used:
  - decision tree
  - K Nearest Neighbours

##### Regression
Regression algorithms examines the relationships of data and how is one changing base on the other. Those variables that are examine are called dependent (target) and independent (predictor). The target is changing in respond to the independent variable, the other independent variables remain unchanged. It can be used in prediction of temperature, age, price...   

Some specific examples:
   - linear regression
   - logistic regression

### Unsupervised learning
Unsupervised learning does have a luxury of getting already labelled dataset so it need to find it own connections in the data base on parameters it gets. Its goal is to find hidden structures, similarities and then output data that are group base on that.     

The Unsupervised learning algorithms can be divided into two categories Clustering and Association
- Clustering
   - DBSCAN
- Association
   - Apriori
   - Eclat



### Reinforcement learning
Where system, *agent*, examinates environment 'around' itself and then w enough observation
it selects the best action base on the its *policy* then according to how good choice did the
system make it either gets *reward* or *penalty*. It learns what's the best strategy(policy)
by analysing its actions and learning from them.

Its basically hit or miss situation, when you do it right, then you ger reward, if you do it wrong
r not good enough, you need to learn from your mistakes and try something different next time.
example: The way robots learnt to walk(DeepMind's AlphaGo)
