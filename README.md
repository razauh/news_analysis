# Climate Change News Analysis

## Introduction

Over the past decade, the topic of climate change has been widely discussed, giving rise to various narratives among politicians, scientists, and economists. These narratives focus on the implications of climate change for our environment and daily lives. This project aims to analyze these narratives, uncover underlying sentiments and themes, explore their evolution over time, and understand how mainstream media presents news related to climate change.

The dataset used in this project is sourced from the Internet Archive's Television News Archive via GDELT's Television Explorer. It comprises over 95,000 mentions of climate change and related phrases across four major news stations: BBC News, CNN, MSNBC, and Fox News. The dataset covers the period from 2009 for CNN, MSNBC, and Fox News, and from 2017 for BBC News. Each record includes metadata such as the precise time, station, show, a 15-second captioning snippet, and a URL to the original clip for comprehensive context.

## Project Goals

The primary goals of this project are as follows:

1. **Analyze Mainstream Media Narratives**: Analyze the narratives presented by mainstream media on the topic of climate change.

2. **Uncover Qualitative and Quantitative Patterns**: Identify qualitative aspects and quantitative patterns based on temporal variations in these narratives.

3. **Topic Modeling**: Apply Latent Dirichlet Allocation (LDA) topic modeling techniques to unveil the core themes discussed in relation to climate change.

4. **Sentiment Analysis**: Perform sentiment analysis on news snippets to measure the tone of discussions surrounding climate change.

5. **Provide Comprehensive Insights**: Present a comprehensive analysis of a decade-long discussion on climate change in television news, offering valuable perspectives on the representation of climate change in the media, the sentiments it conveys, and the evolution of its narrative.

## Getting Started

To run this project and reproduce the analysis:

1. Clone this repository to your local machine.

2. Install the required Python libraries using the provided `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
