# Naive-Bayes-Classifier-to-Filter-Spam-Emails
A Naive Bayes classifier is a simple and effective method for filtering spam emails. It's based on the principles of Bayesian probability and assumes that the features (words) in an email are independent of each other. Despite its simplicity, Naive Bayes often performs well in practice.


<div style="display: flex;">
    
  <div style="flex: 50%; padding: 5px;">
    <img src="./SpamData/assets/thumb-up.png" alt="Thumb Up" style="width: 50%;">
    <img src="./SpamData/assets/thumb-down.png" alt="Thumb Down" style="width: 50%;">
  </div>
</div>

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Preprocessing](#preprocessing)
- [Training](#training)
- [Testing](#testing)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
Spam emails are unsolicited messages sent in bulk to a large number of recipients. They are a nuisance to email users and a serious problem for email service providers. Spam filters are designed to detect spam emails and prevent them from reaching users' inboxes. A Naive Bayes classifier is a simple and effective method for filtering spam emails. It's based on the principles of Bayesian probability and assumes that the features (words) in an email are independent of each other. Despite its simplicity, Naive Bayes often performs well in practice.

## Data
The dataset used in this project is the [SpamAssassin Public Corpus](http://spamassassin.apache.org/old/publiccorpus/). It contains 3,375 ham (non-spam) emails and 1,500 spam emails. The emails are stored in two directories: `spam` and `easy_ham`. The `spam` directory contains 500 spam emails and the `easy_ham` directory contains 2,375 ham emails. The dataset is stored in the `SpamData` directory.

### Email Preprocessing

