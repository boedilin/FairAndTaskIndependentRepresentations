# FairAndTaskIndependentRepresentations

Training fair machine learning models, aiming for their interpretability and solving the problem of domain shift has gained a 
lot of interest in the last years. There is a vast amount of work addressing this topics, mostly in separation. 
In this work we show that they can be seen as a common framework of learning invariant representations. 
The representations should allow to predict the target while at the same time being invariant to sensitive attributes which 
split the dataset into subgroups. Our approach is based on the simple observation that it is impossible for any learning algorithm to 
differentiate samples if they have the same feature representation. This is formulated as an additional loss (regularizer) enforcing a 
common feature representation across subgroups. We apply it to learn fair models and interpret the influence of the sensitive attribute. 
Furthermore it can be used for domain adaptation, transferring knowledge and learning effectively from very few examples.
In all applications it is essential not only to learn to predict the target, but also to learn what to ignore.

The notebooks in this repository were used in the paper "Learning to Ignore: Fair and Task Independent Representations" by Linda Boedi and Helmut Grabner.
