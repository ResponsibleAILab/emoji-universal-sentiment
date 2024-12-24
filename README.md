# Unlocking Cross-Lingual Sentiment Analysis through Emoji Interpretation: A Multimodal Generative AI Approach
This repository contains three files related to emoji sentiment analysis and processing. Below is an explanation of each file and its purpose:


## Files overview
1. Sentiment of emojis

File Name: standalone_emoji_sentiment_with_pixel_icon_descriptions_by_GPT-4o.txt
Purpose: This file contains a dataset that maps emojis to their sentiment scores. Each row represents an emoji and its sentiment value.
2. Collecting emoji representation

File Name: emoji_representation_gathering.py
Purpose: This script collects representations of emojis from Emojipedia.org and Unicode.org
3. Combine multiple emoji sentiment

File Name: sentiment_algorithms_by_standalone_emoji.py
Purpose: This script contains three algorithms: BSA, DPM, and Majority Voting algorithms to combine emoji representation. It also includes methods to find the best-performing BSA algorithms.
## Installation

Install the following libraries before executing the commands as shown in the provided Jupyter notebook:

```bash
pip install emoji
