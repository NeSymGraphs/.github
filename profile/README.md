# Neurosymbolic AI for Reasoning on Graph Structures: The GitHub Organization

This is the Github organization where we fork all the GitHub repositories featured in our survey paper, 

[*Neurosymbolic AI for Reasoning on Graph Structures: A Survey*](https://arxiv.org/abs/2302.07200)

## Summary:

In this paper, we survey the methods which combine symbolic methods with deep learning to accomplish reasoning tasks over graph structures. This hybrid style is called **neurosymbolic AI** :robot: , a relatively new type of AI.

We break these methods down into the following hierarchy:

![hierarchy](https://github.com/hdj2ld/.github/blob/main/hierarchy.png)

**Logically-Informed Embedding Approaches** are the most straightforward: they augment a graph with logical inference, and then feed the augmented graph into a Knowledge Graph embedding method to learn patterns and make predictions:

![cat1](https://github.com/hdj2ld/.github/blob/main/cat1.png)

The methods under **Learning with Logical Constraints** essentially restrict the training of some sort of graph embedding method with logic. They typically accomplish this by imposing some sort of regularizing transformation on the embedding space or by imposing a penalty term onto the loss function whenever logical rules are violated:

![cat2](https://github.com/hdj2ld/.github/blob/main/cat2.png)

Finally, methods which **Learn Rules for Graph Reasoning** often learn rule confidences, or weights, using an iterative, back-and-forth method. In many of these cases, the model interchangeably trains a graph embedding method and performs logical inference. The results of the embedding method are used to update the weights of the rule base, and the results of logical inference are used to guide the embedding method. Some of these methods even alter the pool of rules so that each iteration has a different rule set:

![cat3](https://github.com/hdj2ld/.github/blob/main/cat3.png)

To read more, our paper is currently on [arxiv](https://arxiv.org/abs/2302.07200). 

## Contact

Feel free to contact us for the following maintenance:

:heavy_plus_sign: If you would like us to add GitHub repository containing a published method for neurosymbolic reasoning on graph structures

:arrows_counterclockwise: If you'd like us to fork a more recent version of your repository than we have here

### Contact Information:

:woman_technologist: [Lauren Nicole DeLong](https://github.com/laurendelong21)

:mailbox_with_mail: L.N.DELONG@sms.ed.ac.uk
