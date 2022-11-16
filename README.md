# Assignment-5-Continual-ML-and-Active-Learning
Continual ML and Active Learning

# NOTE-  PART 3- https://github.com/akanksha0911/assignment-5_part-3 , in this repository.


# Part 1- https://colab.research.google.com/drive/1K28HlJddGhlckmBp0c9yMgyplVjBDCHR?usp=sharing-

Avalanche is an End-to-End Continual Learning Library based on PyTorch, born within ContinualAI with the unique goal of providing a shared and collaborative open-source (MIT licensed) codebase for fast prototyping, training and reproducible evaluation of continual learning algorithms. Avalanche can help Continual Learning researchers and practitioners in several ways: Write less code, prototype faster & reduce errors

Improve reproducibility

Improve modularity and reusability

Increase code efficiency, scalability & portability

Augment impact and usability of your research products

*****************************************************************************************************************************************************

# Part 2-  https://colab.research.google.com/drive/19pvJw7hkE6JYm3m4AQ6_JBDwmcwYBQ7_?usp=sharing

End to end demonstratation of active learning with lightly- Classification Task

Ref: https://docs.lightly.ai/tutorials/platform/tutorial_active_learning.html#active-learning

I have used logistic regression on top of the embeddings as a classifier. This is the same as using the embedding model as a pretrained backbone and putting a single layer classification head on top of it while fine-tuning only the classification head on the labeled dataset, but keeping the backbone frozen. Since the embeddings are already computed, we can use them directly as input to the classification head.

This workflow has the following structure:

Choose an initial subset of your dataset, e.g. using one of our selection strategies like the CORESET selection strategy. Label this initial subset and train your model on it.
Next, the active learning loop starts:

Train a classifier on the labeled set.

Use the classifier to predict on the unlabeled set.

Calculate active learning scores from the prediction.

Use an active learning agent to choose the next samples to be labeled based on the scores.

Update the labeled set to include the newly chosen samples and remove them from the unlabeled set.

I have used the clothing-dataset-small.


*****************************************************************************************************************************************************

# Part 3: Part 3 is in this repository-  https://github.com/akanksha0911/assignment-5_part-3.  with all the artifacts and code.
