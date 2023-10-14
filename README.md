# Neural-Networks
Lab Exercises for the Neural Networks &amp; Intelligent Systems course @ ECE NTUA

<br> 
 <details><summary> Lab 1 - Supervised Machine Learning </summary>
<p>

Supervised Machine Learning utilizing different classifiers on two balanced datasets.

## UCI Dataset - Statlog Vehicle Silhouettes
The dataset that was used can be found [here](http://archive.ics.uci.edu/ml/datasets/Statlog+(Vehicle+Silhouettes)).
The training and optimization of the classifiers on the UCI dataset was done exclusively with the skicit-learn functions. After the initial exploratory data analysis we utilised the ***Dummy, Gaussian Naive Bayes (GNB), KNeirestNeighbors (kNN) &amp; Logistic Regression (LR)*** classifiers and evaluated their performance based on ***Accuracy*** and ***F1-score*** metrics. Lastly, the afforementioned classifiers were optimized by setting up pipelines and performing ***Grid Search*** to fine-tune them.

## Kaggle Dataset - CS:GO Round Winner Classification
The dataset that was used can be found [here](https://www.kaggle.com/christianlillelund/csgo-round-winner-classification).
The training and optimization of the classifiers on this dataset was done with the skicit-learn functions and the optuna library. After the initial exploratory data analysis we utilised the ***Mylti-Layer Perceptron (MLP) &amp; Support Vector Machines (SVM)*** and ***Logistic Regression (LR)*** classifiers and evaluated their performance based on ***Accuracy &amp; F1-score*** metrics. Lastly, the afforementioned classifiers were optimized by setting up pipelines and utilizing both ***Grid Search*** and the ***Optuna otimization libary*** to fine-tune them.

</p>
</details>
<br>

-----
<br> 
 <details><summary> Lab 2 - Unsupervised Learning </summary>
<p>

The dataset used is based on the [Carnegie Mellon Movie Summary Corpus](http://www.cs.cmu.edu/~ark/personas/). This is a dataset with 22,301 movie descriptions and for the purpose of this exercise a partition of ***5000*** movies was used.

## Application 1: Implementation of a content-based movie recommendation system

The first application that was developed was a content based recommender system. Recommender systems aim to automatically suggest to the user items from a collection that ideally we want the user to find interesting. The categorization of recommendation systems is based on how the selection (filtering) of the recommended items is done. The two main categories are collaborative filtering, where the system suggests to the user objects that have been positively evaluated by users who have a similar history of evaluations, and content based filtering, where objects are suggested to the user with similar content (based on some characteristics) to those he has previously rated positively.

## Application 2: Topological and semantic representation of movies using SOM

In the second application we relied on the topological properties of Self Organizing Maps (SOM) to make a two-dimensional map (grid) where all the films of the group's collection are displayed in a spatially coherent manner in terms of content and mainly their genre.

</p>
</details>
<br>

-----
<br> 
 <details><summary> Lab 3 - Deep learning </summary>
<p>

## Image Captioning

We studied a problem that combines Computer Vision and Natural Language Processing. Specifically, we build a neural network for producing verbal descriptions from images (Image Captioning).
The dataset used for this exercise is ***flickr30k-images-ecemod***, a split of **Flick30k** specifically set for the needs of our Neural Networks class.
flickr30k-images-ecemod has a similar organization to ***COCO***. Each image has 5 captions made by different people through Amazon's Mechanical Turk service.
The model is based on the general architecture of transformers. A convolutional neural network is used as an encoder of the visual information and a series of transformer-decoder layers produce the verbal description. Transformer-decoder levels also include attention levels. The model's performance was evaluated using ***BLEU (Bilingual Evaluation Understudy) score***. Diffrent Embeddings were utilized to test the model's performance and ***Beam Search*** was implemened for better sentence generator accuracy.

</p>
</details>
<br>

-----
<br> 
 <details><summary> Collaborators </summary>
<p>

| Name                                | Εmail                  | AM         |
| ----------------------------------- | ---------------------- | ---------- |
| Papanikolaou Ioannis                | *el18064@mail.ntua.gr* | 031 18 064 |
| Andreas Chrysovalantis-Konstantinos | *el18102@mail.ntua.gr* | 031 18 102 |
| Maniatis Andreas                    | *el18070@mail.ntua.gr* | 031 18 070 |

</p>
</details>
<br>
