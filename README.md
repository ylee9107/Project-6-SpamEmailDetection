# Project-6-SpamEmailDetection
Project 6 is the detection of spam emails with the Naive Bayes classifier

## Background:
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research.
It contains one set of SMS messages in English of 5,574 messages, tagged according to being legitimate or spam.
The included dataset are rows that contain one message per line. 
Each row is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

## Naive Bayes Classifier Intuition:

![Alt Text]()

It can be seen that the “prior” P(A) and the “evidence” P(B) refer to the probabilities of observing A and B independently from each other. The “posterior” and the “likelihood” components are the conditional probabilities of observing A given B and vice versa.

For email classification in Spam or Legitimate, the probability to compute is:

![Alt Text]()

Where here the "x" is a feature vector containing the words from the Spam (or Legitimate) emails.

The “Naive” assumption that the Naive Bayes classifier makes, is that the probability of observing a word is independent of each other. 


