# Attribution-Model
Hi, this is a simple but efficient application of a Markov chains based attribution model to study the relation between different web analytics channels.

Markov chain is in a nutshell a model describing a sequence of possible events in which the probability of each event depends only on the current state. Despite not having a final conversion variable for the attribution model, it is still possible to use this approach to understand the transition probabilities between channels and study how they interact between each other. In this version I set "Null" to specify the end of a path for a specific user.

To run this code you need a database with some essential information:
- A unique Client ID (mine was cookie based)
- The associated page seen by the client ID or just the channel of the mentioned page 
- A timeline that will be associated to the paths (I had a daily granularity, hence I aggregated the clients' search history by weeks)

That's all you need :)

Thanks, for checking me out and I hope you like it


