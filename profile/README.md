# Neurosymbolic AI for Reasoning on Graph Structures: The GitHub Organization

This is the Github organization where we fork all the GitHub repositories featured in our survey paper, 

*Neurosymbolic AI for Reasoning on Graph Structures: A Survey*

## Summary:

In this paper, we survey the methods which combine symbolic methods with deep learning to accomplish reasoning tasks over graph structures. This hybrid style is called **neurosymbolic AI** :robot: , a relatively new type of AI.

We break these methods down into the following hierarchy:

**Figure to come**

![hierarchy](https://github.com/hdj2ld/.github/blob/main/sample.png)

**Logically-Informed Embedding Approaches** are the most straightforward: they augment a graph with logical inference, and then feed the augmented graph into a Knowledge Graph embedding method to learn patterns and make predictions:

**Figure to come**

![hierarchy](https://github.com/hdj2ld/.github/blob/main/sample.png)

The methods under **Learning with Logical Constraints** essentially restrict the training of some sort of graph embedding method with logic. They typically accomplish this by imposing some sort of regularizing transformation on the embedding space or by imposing a penalty term onto the loss function whenever logical rules are violated:

**Figure to come**

![hierarchy](https://github.com/hdj2ld/.github/blob/main/sample.png)

Finally, methods which **Learn Rules for Graph Reasoning** often learn rule confidences, or weights, using an iterative, back-and-forth method. In many of these cases, the model interchangeably trains a graph embedding method and performs logical inference. The results of the embedding method are used to update the weights of the rule base, and the results of logical inference are used to guide the embedding method. Some of these methods even alter the pool of rules so that each iteration has a different rule set:

**Figure to come**

![hierarchy](https://github.com/hdj2ld/.github/blob/main/sample.png)

To read more, our paper is currently on arxiv. 

## Contact

Feel free to contact us for the following maintainence:

:heavy_plus_sign: If you would like us to add GitHub repository containing a published method for neurosymbolic reasoning on graph structures

:arrows_counterclockwise: If you'd like us to fork a more recent version of your repository than we have here

### Contact Information:

:woman_technologist: [Lauren Nicole DeLong](https://github.com/laurendelong21)

:mailbox_with_mail: L.N.DELONG@sms.ed.ac.uk
