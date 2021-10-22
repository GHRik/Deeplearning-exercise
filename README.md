# Deeplearning-exercise
repo to improve my deeplearning knownledg

## Table of contents
1. [ Description ](#repo)
2. [ Technology ](#tech)
3. [ Sylabus ](#syl)
4. [ Theory ](#theo)
5. [ Results ](#res)


<a name="repo"></a>
## Description

This repo was created to improve my Deep learning experience. In this repo i will commit a small project sperate on directory.
All of directory will have own README with theroy and how functions is implemented in code.
To use this repo you should have a small knownledge in python prograing and statictic. <br />

All theory on this repository will be taken from the book "Grokking Deep Learning" Andrew W. Trask . Most of the source codes will be based on the codes used in the book above.<br />

Before you start browsing the projects, I suggest you read the theoretical introduction below.

<a name="tech"></a>
## Technology
[Python 3.9](https://www.python.org/downloads/release/python-390/) - to run my py scripts<br />

<a name="syl"></a>
## Sylabus
- WIP 
- WIP
- WIP
- WIP

<a name="theo"></a>
## Theory
<p align="center">
   <img src="https://www.intel.pl/content/dam/www/public/us/en/ai/images/ai-machine-learning-deep-learning-rwd.png.rendition.intel.web.1648.927.png" width="50%" height="50%" alt="intel-deep.png" />
   [Source](https://www.intel.pl/content/www/pl/pl/artificial-intelligence/posts/difference-between-ai-machine-learning-deep-learning.html)
</p>
### Deeplearning
Deep Learning is a sub-category of machine learning. Deep learning is about creating neural networks. Basically, thanks to neural networks, we can create datasets with which we program (not simply) machine learning.<br />

### Machinelearning
Basically it is what the name implies. It is an attempt to teach the machine to perform a given task. By giving the machine a certain pattern, the machine is able to determine the effects of its work.<br>

We can divide machine learning into supervised and unsupervised learning.

#### Supervised
Transformation of one data set into another. So it can transform what we know into what we want to know.
<p align="center">
   <img src="https://github.com/GHRik/Deeplearning-exercise/blob/weightsAndOneOutput/images/supervised%2Cjpg.JPG" width="50%" height="50%" alt="intel-deep.png" />
</p>
Example:
<p align="center">
   <img src="https://github.com/GHRik/Deeplearning-exercise/blob/weightsAndOneOutput/images/supervised%2Cjpg.JPG" width="50%" height="50%" alt="intel-deep.png" />
</p>

#### Unsupervised
Like supervised learning, we transform one dataset into another. However, in this case, the set we want to obtain is not known and understood. It works more like: "You have information in the file, tell me what you know about it."
<p align="center">
   <img src="https://github.com/GHRik/Deeplearning-exercise/blob/weightsAndOneOutput/images/unsupervised_simple.jpg" width="50%" height="50%" alt="intel-deep.png" />
</p>
Example:
<p align="center">
   <img src="https://github.com/GHRik/Deeplearning-exercise/blob/weightsAndOneOutput/images/unsupervised.jpg" width="50%" height="50%" alt="intel-deep.png" />
</p>
The algorithm does not explain why exactly such labels were assigned to specific objects.

#### Parametric vs non-parametric learning
Parametric learning from non-parametric learning is that in parametric we have a constance number of parameters, and in the second we have an infinite number of parameters (determined by the input data)

#### Supervised Parametric, how it works?
1. Prediction - As it was written before. We have two inputs. Dates for housing prices from 2000-2010 and we want to obtain housing prices from 2011. We are introducing
data from 2000-2009 and we want to get 2010 on the result. Using 2000-2009 data our algorithm tries to predict prices from 2010.
2. Comparing with the pattern - Swoje przewidywania porównuje z cenami z 2010, jeżeli przewidział dobrze lub przewidział źle wprowadza dane do modelu
3. Model learning - At this point, the algorithm sets which of the given criteria have the greatest impact on the price of apartments, whether it is a floor, or maybe the date of construction, etc. With such a ready model it is able to predict prices for 2011

#### Unsupervised Parametric
In other words, it works practically the same as the supervised one, only it differs in the input data and the way of interpreting them. Generally, just as supervised calculated prediction, the unsupervised will calculate the probability of an event occurring in some deduced group.

### Non-parametric
Basically, deep learning relies more heavily on parametric learning. Therefore, this point was mentioned more as a curiosity and will not be discussed further.


<a name="res"></a>
## Results:

