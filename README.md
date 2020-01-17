# Final Project - Personalization Theory

Authors: *Bertrand Thia-Thiong-Fat (bt2513), Jeremy Yao (jy3015), Paul Doan (pqd2001)*

# Directories and files

Please look at the requirements file to learn about dependencies and useful packages to reproduce our results.

We splitted our work in **6 notebooks**. Each of them is independent and the code can be run independently from one or the other. 

The titles explicitly describes the content of each notebook: 
0. **Introduction**
1. **Data Preprocessing**
2. **Baseline Model**
3. **Content-based Model**
4. **Deep Learning Model**
5. **Conclusion**

Finally, please find the datasets used to test our models during this study.

# The Objectives

**Context**

We are placing ourselves in the position of Senior Data Scientists at a company that recommends local businesses. 
We wish to focus on a particular business objective: **predict accurately the latest rating of all active users of the website Yelp.** Being able to accurately predict the last rating of a given user allows for a better understanding of their current preferences well. As a result, we can recommend other businesses that the user could potentially be interested in. This explains why we decided to focus on making accurate predictions to understand consumer preferences and drive valuable insights for Yelp's business.

We will study different models and compare them to suggest the best available tool for Yelp. **Our work attempts at predicting customer ratings accurately and does not address the cold start problem.** 

In the end, we will decide if the created algorithm can really be used in a real situation for Yelp or if more studies and more data need to be available in order to provide an effective and reliable recommender system.

**Content**

To make the data more tractable, we will proceed to reduction of the size of the datasets and strive to obtain unbiased samples. **We will reduce the original data to approximately 500k ratings.**
As a next step, we will develop 3 different models of recommender systems. We will start with a **user-based collaborative filtering model**, which will be also act as a baseline for comparison with other models.
For instance, we will  create **a collective factorization algorithm** and develop **a deep learning model**.

We will also conclude our analysis by comparing the different models and methods to recommend relevant local businesses.

# The data

Our full dataset can be found here: https://www.yelp.com/dataset/challenget

# Quantitative results

See the different Notebooks. They unravel our workflow, from problem definition to our results, limitations and future works.

# References and useful links

scikit-learn documentation: https://scikit-learn.org/stable/documentation.html

keras documentation: Useful to create our AutoEncoder models and train them: https://keras.io

Kuchaiev, Oleksii, and Boris Ginsburg. "Training deep autoencoders for collaborative filtering." arXiv preprint arXiv:1708.01715 (2017).
