# Machin learning basics
### Supervised learning
Is When the data you use in training already include the answer you want
algorithm to get. Example: spam filter, you have many examples of
email that are already marked “spam” and “not spam” so algorithm
learns how to classify new emails. Another can be guessing prices of
 products base on their different features called predictors

##### Classification

   - decision tree
   - K Nearest Neighbours

##### Regression

   - linear regression
   - logistic regression

##### Advantages

- With previous experience of the similar t
- Can be easily use for the basic algorithms.

##### Disadvantages

- Can't solve stuff that aren't classified into groups in training
dataset, their group wasn't included in when the system was learning,
so it can't label it correctly.
- There needs to be previous knowledge of classes of object.
- Need lot of computation time.



### Unsupervised learning
Data doesn’t have answers attached to them and program is trying to
learn on its own. For example clustering algorithm is trying to find
connections between ‘objects’ and them group together once that are
similar.
- clustering
   - DBSCAN
- Association rule learning
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
