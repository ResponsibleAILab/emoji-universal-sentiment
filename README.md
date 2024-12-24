# Unlocking Cross-Lingual Sentiment Analysis through Emoji Interpretation: A Multimodal Generative AI Approach
This repository contains three files related to emoji sentiment analysis and processing. Below is an explanation of each file and its purpose:


## Files overview

### 1. Sentiment of emojis  
standalone_emoji_sentiment_with_pixel_icon_descriptions_by_GPT-4o.txt  
This file contains a dataset that maps emojis to their sentiment scores. Each row represents an emoji and its sentiment value.  
### 2. Collecting emoji representation  
emoji_representation_gathering.py  
This script collects representations of emojis from Emojipedia.org and Unicode.org  
### 3. Combine multiple emoji sentiment  
sentiment_algorithms_by_standalone_emoji.py  
This script contains three algorithms: BSA, DPM, and Majority Voting algorithms to combine emoji representation. It also includes methods to find the best-performing BSA algorithms.  
## Installation

Ensure the following libraries are installed before executing the Python scripts:

```bash
pip install emoji
