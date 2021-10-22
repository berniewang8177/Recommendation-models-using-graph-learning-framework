# Draft of Intro

### What’s the problem we’re solving,	(citation needed)
- We’re trying to use graph learning model to generate graph that GNN can work on to do general recommendationsuch as link prediction<br/>(given a new user, map him to existed movies with proper ratings ). 

### Why using graph to represent data?
- There are natural graph structure “embedded” in the data used for recommendation. For example, User specific data (age, gender, ..)<br/>and film (director, keywords, ..) can interacted by the rating behavior performed by user. Thus, an bi-partite graph is naturally constructed.

### How does this benefit ML?	Why using GNN?
- As we mentioned above, the dataset can naturally represent as an bipartite-
graph. Thus, it is natural to apply graph neural network on it too.
	

### why it is important?	(citation needed)
- Since state-of-art are specialized and complicated, they may not have the flexibility to generalize well ( really??). Our graph representation is more simple and general.
By using a less-specialized and flexible graph representation approach, we argue that the system has the ability to generalize, trained in a shorter time, and gives a reasonable recommendation compared to the state-of-art DLRM.



Other people’s approach, why they fall short?
- They do no fall short, they are much smarter than me ….


### My current plan for this:
1. get a dataset. (user data + movie data and user rating for each movie)
2. Construct a bipartite graph ( We can do it manually, does graph learning model 
necessary)
3. Put a GNN, GCNN on top	 (DLG library is helpful)
4. prediction
