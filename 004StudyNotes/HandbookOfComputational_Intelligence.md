[TOC]



# CH 29 machine learning



## Summary 

* A tutorial on machine learning toolbox
  * Supervised learning
  * Unsupervised learning
  * Reinforcement learning

## Overview

<u>__Machine learning__</u> 

* Computational tools and techniques that support __understanding__ and __extraction__ of __useful knowledge__ from complicated data sets. 
* Enable the system to do the __same task__ or __task draw from the same population__ more effectively 
* Emphasize the system ability to __adapt__ or __change__
* After learning or adaption, the system is expected to have __better performance__ on the __same__ or a __relevant task__ 



<u>**Two perspectives**</u>

* **Learning intelligent system** =solving three levels of inverse problem
  * Pattern recognition
  * Parameter learning = estimating unknown parameters in the system
  * Model selection = shaping system configuration to describe the regularities underlying a finite size of sample
  * Learning algorithms differs in 
    * __Learner__ = a system
    * __Theory__ = guide learning
    * __Algorithm__ = implement learning 
* __Machine learning toolbox__ --> this chapter



<u>__Three learning paradigms__</u>

* Supervised learning
  * Provide inputs with the corresponding desired output 
* Unsupervised learning
  * Finding certain dependence structure underlying data via _optimizing learning principle_ 
* Reinforcement learning
  * A learning process makes a series of actions with received total award maximized
  * _Unlike supervised learning_, the learner gets guidance from external evaluation
* Other variants
  * Hybrid of the three kinds
  * E.g. semi-supervised learning (use both labeled and unlabeled data)



## Supervised learning

### Basic Concepts

* Training samples = inputs with corresponding outputs

* Features

* Feature vector

* Feature space = the space of all possible feature combinations

* Dirty data

  * Incomplete (missing attribute values), outliers, errors, inconsistency, redundant

* Training sets

* Over-fitting

  * Model captures the trends of the noise underlying the data 

  * Model performs better than other models on the training data but worse on the entire 

    ​



### Classification 

__Classification__ = Assign input patterns to different category

<u>__Types__</u>

* Binary classification
  * Decision boundary = feature space is partitioned into two regions
  * Classifiers --> differ in model parameters 
    * Linear classifiers 
      * Features: weight on each feature = slope of the linear boundary, bias = offset  
    * Quadratic classifiers -->  
    * Decision tree classifier
    * Bayesian classifier
    * Support vector machine (SVM)



### Regression

__Regression__ = predict a real value or a vector associated to the input





# Appendix

## Markdown Inline Template

<font color = 'red'> red </font>