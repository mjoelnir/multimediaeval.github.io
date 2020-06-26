---
# static info
layout: task
year: 2020
hide: true

# required info
title: NewsImages
subtitle: The relation between images and text in news articles
blurb: News articles use both text and images to communicate their message. Online news is no exception. This task investigates the relationship between images accompanying news articles and the textual content of the articles (including text body, and headlines) and to understand the impact of these elements on readers’ interest in the news (measured by the number of views). Participants must automatically predict the image that accompanies a specified news article. The task also explores image features that are correlated with the popularity of news items.
---

<!-- # please respect the structure below-->


#### Task Description

The task provides two subtasks:

1. Image-Text Re-Matching

Journalists select images to accompany stories as visual clues for readers. Images reveal information and draw readers' attention. Participants ought to re-assign the correct images out of a selection.

2. Hot Image Prediction

Retaining readers directly affects publishers revenue through advertisements. Identifying images that let readers extend their visits can give publishers competitive advantages. Participants ought to develop models to anticipate promising images in terms of readers' interactions.

#### Motivation and Background

The media landscape witnesses the interplay of different kinds of actors weaving the strings connecting consumers to content. Historically, journalists guided the process in various roles. As reporters, they relayed information from where the story developed. As writers, they composed drafts. As editors, they checked, corroborated, and selected stories. Finally, presses produced the newspapers to be delivered to subscribers. The advent of digitization has changed the previously streamlined system. Today, subscribers contribute content, new intermediaries collect and present news from different sources, and news distribution has moved to real-time on mobile devices.

Online services---including news publishing---rely heavily on advertisements. Consequently, publishers have started to compete for users’ attention rather than direct compensation for their services. News recommender systems aid keep users on the service by suggesting other stories. These systems answer the question: what makes a promising recommendation? Today, news comes as a blend of modalities. Podcasts and videos complement the traditional display of text and images. But what captures users’ attention?

This task investigates how journalists select images and how users react to them. First, we explore whether machines can learn how journalists match images to articles. Typically, a journalist will have a variety of images available. They somehow decide which image best matches the article content. Deconstructing their thoughts could enable publishers to automatically assign images to articles, thus accelerating the publication process. Second, we examine whether machines can predict the probability of users paying attention to recommendations. A valid model would boost publishers’ business success.


#### Target Group

The task invites participants with background in computer vision, natuaral language processing, and machine learning.

#### Data

The data set comprises X articles and Y images. Articles carry the following features: identifier, headline, text snippet. Images come with an identifier and URL. Due to copyright restrictions, participants have to download the images themselves. The data set is of Z GB large.

#### Evaluation Methodology

##### Image-Text Re-Matching

The training set shows which images journalists have assigned to articles. Participants create models which given an article, which images is most likely selected. This setting gives rise to a binary classification task. Participants predict for each article in the test set, the most likely match.

##### Hot Image Prediction

The training set reveals how engaging (image, article) pairs are. Participants score the hotness/engagement for each image in the test set. Subsequently, the evaluation protocol measures how well the prediction compare to the true ranking of images.


#### References and recommended reading
<!-- # Please use the ACM format for references https://www.acm.org/publications/authors/reference-formatting (but no DOI needed)-->
<!-- # The paper title should be a hyperlink leading to the paper online-->


#### Task Organizers
<!-- # add the email address of the contact organizer-->
[Andreas Lommatzsch](<andreas.lommatzsch@dai-labor.de>)

[Benjamin Kille](<benjamin.kille@dai-labor.de>)

[Özlem Özgöbek](<ozlem.ozgobek@ntnu.no>)

#### Task Auxiliaries
<!-- # if there are people helping with the task, but are not bearing the main responsibility for the task, they are auxiliaries. Please delete this heading if you have no auxiliaries-->

#### Task Schedule
* XX July: Data release <!-- # Replace XX with your date. Latest possible is 31 July-->
* 31 October: Runs due <!-- # Replace XX with your date. Latest possible is 31 October-->
* 15 November: Results returned  <!-- Fixed. Please do not change-->
* 30 November: Working notes paper  <!-- Fixed. Please do not change-->
* Early December: MediaEval 2020 Workshop <!-- Fixed. Please do not change-->

Workshop will be held online. Exact dates to be announced.
