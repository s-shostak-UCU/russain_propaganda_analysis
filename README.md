# README for russian Propaganda Dataset Analysis

## Getting Started

- You can use Google Colab to run the code

## Project Overview

This project comprehensively analyzes a dataset containing messages from various russian propaganda telegram channels. The analysis covers various aspects, including general channel metrics, reactions analysis, content analysis, network analysis, and time series analysis. The goal is to uncover patterns, trends, and insights into the nature of content and audience engagement in these channels.

### Prerequisites

- Ideally, you need a Google Colab Pro account
- At least 12 GB of RAM is required if you want to run the code on the local machine. 
- Knowledge of Python for Data Analysis, basic ML, and NLP.

## Data Loading and Preprocessing

The dataset was previously collected from russian telegram channels in 2022. Preprocessing includes filtering, aggregation, and transformation of data for various analyses. The data includes metrics like the number of posts, comments, views, and reactions.

## General Analysis

The initial analysis focuses on identifying the most popular channels based on views, posts, and comments. It also examines the distribution of views across all channels and within specific top channels. Key findings include:

- Channels with the most views include Russian politicians, bloggers, and media channels.
- The distribution of views is right-skewed, indicating a few posts with exceptionally high views.
- Channels with frequent posts don't necessarily have high views, suggesting quantity doesn't equate to popularity.

## Reactions Analysis

This section analyzes the total reactions per channel, the most common reactions, and the correlation between reactions and views. Key observations:

- The channels with the most reactions are primarily politicians, military correspondents, and bloggers.
- Positive reactions dominate across channels, indicating a preference for propaganda content.
- The correlation between reactions and views is relatively low, suggesting other factors influence engagement.

## Content Analysis

The content analysis involves examining frequently used words, common bigrams, and bigrams with the highest TF-IDF scores. It also includes a specific focus on bigrams related to Ukraine and russia. Insights include:

- Frequent mentions of russia, putin, and military-related terms.
- Bigrams indicate narratives around Ukraine as an object influenced by external forces.
- TF-IDF analysis highlights significant bigrams that shape the channels' narratives.

## Network Analysis

Network analysis is conducted to identify clusters of channels with similar content based on message similarity and bigram usage. The analysis uses TF-IDF vectorization, cosine similarity, and network graph visualization. Findings:

- Channels with similar content form clusters, indicating shared narratives or themes.
- The network analysis based on bigrams shows less pronounced clusters, suggesting diverse usage of frequent bigrams across channels.

## Time Series Analysis

The time series analysis examines how posting frequency and reactions vary over time. Key points:

- Posting frequency peaked at the start of the war and declined in April, with smaller peaks observed later.
- Positive reactions consistently outnumber negative reactions, with spikes in negative reactions corresponding to significant military events.


---
